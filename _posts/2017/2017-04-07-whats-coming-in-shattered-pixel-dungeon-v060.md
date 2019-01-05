---
title: What’s coming in Shattered Pixel Dungeon v0.6.0 pt.1
---
Hey folks, after my little April Fools joke, I imagine many of you are wondering what I’m actually doing for the next Shattered Pixel Dungeon update. The next update is still at least a couple of weeks off, so I thought it would be a good idea to start more publicly sharing what it is I’m working on! The next update is v0.6.0, and it’s going to make some very big changes to how levels are generated.

I’m going to write two posts about these changes, to start with I’m going to explain some of the more technical changes, and in part 2 I’m going to show off some of the new features that will be coming in v0.6.0

Let’s start with a simplified explanation of how levelgen currently works. The current algorithm takes what I like to call a ‘map first’ approach to levelgen, where the general structure of a level is defined first, and then more specific details are filled in.

We start with a blank map, think of it like a big sheet of blank grid paper, with 32 by 32 squares. We then fill in a straight line of squares along either a row or column. The position we draw this line at is totally random, but we must leave at least 2 squares of width on each side. So now we have a grid with one line dividing it into two areas, we treat each of these areas like a new, smaller grid, and repeat the line drawing process for each of them. We keep doing this until we have no areas left that are larger than 8 by 8. We then also fill in all the squares around the edges. All of the empty squares that we have are the rooms of the level, and we now need to decide what types the rooms are, and how they are connected.

We randomly pick two rooms that aren’t too close to each other to be the entrance and exit. We then trace two paths between the entrance and exit, through other currently unused rooms. These paths are both fairly straight, but appear snaky due to how the rooms were initially drawn, they can overlap but usually don’t. We then randomly add a few short branches to these paths through other unused rooms. All the rooms that are part of these paths are used, and the rest are discarded.

There are three types of rooms: tunnel, standard, and special. Tunnel rooms are thin snaky paths between other rooms. Standard rooms are open with doors, and contain most of the regular enemies and loot. Special rooms contain unique enemies and special loot, and can only have one entrance which is often locked. Some of the rooms at the ends of branches are chosen to be special rooms, and all the other rooms are randomly either tunnel or standard rooms. Finally, we look at adjacent standard rooms, and will sometimes knock down the walls between them, which produce the game’s larger, L and T shaped standard rooms.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levelgen-anim.gif" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levelgen-anim.gif"/>
  <figcaption>
   I made a little animated gif to illustrate this process
  </figcaption>
 </a>
</figure>

This algorithm produces a great variety of compact levels, but it has a few serious drawbacks. I used the term ‘map first’ initially, and that approach leads to some restrictions because rooms themselves have very little control over how they are placed in a level. In my opinion, the starting point for levelgen should be the rooms themselves, meaning that a level decides what rooms it has first before coming up with how they’re put together. As you might have guessed, I’m calling this approach ‘room first’, **and it has led me to completely redesign how levels are generated in ShatteredPD.**

This new approach splits level generation into three phases, which I like to call Initialize, Build, and Paint. Each one is responsible for a different distinct part of generating a level. Initialize defines what rooms a level will have (minus tunnels), without any consideration for how big they are or how they’ll be laid out. Rooms are able to specify what size range they can be, allowing specific rooms to be much larger than the previous algorithm’s cap of 8x8. Rooms can define how they would like to connect with other rooms, including maximum or minimum connections, and denying connections on certain sides.

Build takes those rooms and defines exactly how they will be laid out to form a level, including connections and added tunnel rooms. Build is extremely flexible in that it works on free-form positioning rather than predefined lines along a grid. This also means that levels don’t have to fit into a predetermined size, allowing for levels of all sorts of shapes. While this does make it more complicated to build levels well, it also allows for many more possibilities. Build algorithms are also interchangeable, so the same set of rooms can generate wildly different levels depending on which build algorithm is used.

Paint takes the now defined level structure and specifies the values of all the tiles on the level, meaning that the map is finished and ready to be filled with enemies and loot. Each room is responsible for painting its own contents, but can also specify which tiles the paint algorithm is allowed to make its own changes to. These changes take the form of grass, water, and traps currently.

Initially I’m working on getting everything functional and having it pretty closely emulate how levels are laid out already, but there is now so much more potential for cool new things. Look forward to the second post about 0.6.0 in the coming weeks, which will feature lots of information about new content that’s taking advantage of these technical improvements. In the meantime though, here are a few simple examples that I’ve already got working:
  
<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/bigger-rooms.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/bigger-rooms.png"/>
  <figcaption>
   Thanks to the more freeform layout, rooms can be as big as they like, here’s a huge fissure room
  </figcaption>
 </a>
</figure>

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/line-level.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/line-level.png"/>
  <figcaption>
   All sorts of layouts are possible, here’s a level built with a thin snaky level builder
  </figcaption>
 </a>
</figure>

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/large-level.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/large-level.png"/>
  <figcaption>
   Making huge levels is as easy as initializing with lots of rooms, here’s that same snaky level builder with 5x the number of rooms (click for full resolution)
  </figcaption>
 </a>
</figure>

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/64a08o/whats_coming_in_shattered_pixel_dungeon_v060_pt1/?st=j19vip5e&sh=041e54ac)

