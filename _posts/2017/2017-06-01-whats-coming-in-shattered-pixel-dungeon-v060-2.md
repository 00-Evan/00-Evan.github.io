---
title: What’s coming in Shattered Pixel Dungeon v0.6.0 pt.2
---
Hey everyone! After a bit of delay, here is part 2 of what’s coming in 0.6.0, as promised. Last time I focused primarily on the technical changes in levelgen, and while there will still be a bit of that, this time around the primary focus is on new content. You’ll need to have read [Part One](/blog/whats-coming-in-shattered-pixel-dungeon-v060.html) to understand everything here, but it’s definitely not necessary.

## What’s coming in 0.6.0

The new levelgen algorithm in 0.6.0 is going to let me make a lot of cool new things going forward, but I also wanted to get at least some improvements into 0.6.0 itself. You can expect all of these things to release with 0.6.0 in early June.

As discussed in my last blog, one of the big segments of 0.6.0’s levelgen logic is the builder, which takes the rooms a level is going to have and figures out where they all go. The builder that all regular levels use right now is what I call the loop builder. The loop builder places some rooms roughly along a main loop, and then the rest along branches for variety. The entrance is placed on one end of the loop, and the exit (if there is one) is placed on the opposite end. This very closely emulates the structure of the previous levelgen algorithm. This main loop is a plain circle by default, but it can warped and skewed to make the main path into any sort of circle or oval-based shape.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/loop-example.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/loop-example.png"/>
  <figcaption>
   Here’s an example, with the main path highlighted in blue and branches in red
  </figcaption>
 </a>
</figure>

Rooms now have no hard limit on how big they can be, but most rooms will still only go as big as the old maximum of 8x8. Some standard rooms are capable of being larger though, and go all the way up to 16x16. I’m categorizing these as ‘large’ and ‘giant’ standard rooms for now, and they have dimension ranges of 8-12 and 12-16 respectively. Naturally, having these big rooms be totally empty simple wouldn’t do, so there are a few interesting new room layouts that only occur at larger sizes.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/large-layouts.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/large-layouts.png"/>
  <figcaption>
   Here we have large layouts for striped and study rooms, and a giant layout for platform rooms
  </figcaption>
 </a>
</figure>

Finally, because rooms are initialized separately from the creation of a level, it’s now extremely easy to have room types and quantities that vary by floor. Right now, this takes the form of levels getting larger each chapter, and each chapter having one type of standard room that’s unique to it. Eventually I want to use flexibility like this (along with variable builders) to make each chapter quite unique, but for now there’s just a bit more variety between each one.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sewers-v-caves.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sewers-v-caves.png"/>
  <figcaption>
   Sewer floors are usually quite small, but deeper down levels will get bigger and bigger
  </figcaption>
 </a>
</figure>
<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-rooms.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-rooms.png"/>
  <figcaption>
   Ring, segmented, cave, and pillar rooms. Each of these rooms are unique to their chapter
  </figcaption>
 </a>
</figure>

## What’s coming later

I’m going to be a bit more vague here, as none of these things are final yet, but I do have some pretty solid plans for cool new things that will (hopefully) feature in future updates. No screenshots for these ones I’m afraid.

Being able to add new rooms that fit into the existing room types is one thing, but another thing I have planned is new room types entirely. One of those types that’s looking quite promising are landmark rooms. Landmark rooms would appear exactly once per floor and are primarily meant to enhance visual and layout variety. As the name implies, these rooms would be quite distinctive, and I’d also like them to vary based on the chapter of the game.

I also want to experiment with builders that use rooms other than the entrance as a starting point. As an example, a builder could take the level’s landmark room and create a main path by having a small number of long lines spreading from that room, with the entrance down one line and the exit down one other. Branches could then be added as short extra lines sprouting from any room. The one huge advantage of a builder like this is that it gives a single room lots of opportunity to influence levelgen. Take, for example, a landmark room for the caves which is an extremely tall chasm with a bridge in the center. This landmark room only accepts connections on its middle left and middle right, and by having levelgen start from it this room would effectively segment the level into two parts, one to the left of the giant fissure and one to the right of it.

To go along with the theme of rooms influencing level generation, another thing I want to experiment with is rooms inside of rooms. Now that rooms can be massive there’s no reason why they couldn’t contain smaller rooms inside of themselves. These sub-rooms wouldn’t be placed by levelgen, but would instead be placed within their parent room, by that parent room. As a simple example, ring rooms could contain another room if their center pillar is large enough for it. This could allow a special room (connects only once) to be part of a larger room connection structure, as the special room would have one connection to the ring room it is inside of, and then the ring room could have multiple connections to other parts of the level. It would even be possible to have one gargantuan room contain all the other rooms the level has!

Lastly, the new connection structure and purposeful choosing of rooms would allow for much more interesting secrets. Currently secret rooms are just normal rooms with their door hidden. There’s no reason why secrets couldn’t instead be their own category of room, perhaps with unique layouts and rewards…

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/6eqa1u/whats_coming_in_shattered_pixel_dungeon_v060_pt2)

