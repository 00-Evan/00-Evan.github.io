---
title: "Coming Soon to Shattered: Sub-Floors and Digging!"
excerpt: "Hey Dungeoneers! In this blog post I'm going to go over some of the new technical additions to Shattered in v2.1.3, and how they're going to allow for future content. In particular, I plan to use these additions in a reworked blacksmith quest in the next major update!"

header:
  image: /assets/images/2023/2023-06-29/header.png
  teaser: /assets/images/2023/2023-06-29/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#452 = pickaxe sprite in v0.9.0+
#468 = pickaxe sprite in v2.3.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 452", "SHPD_ICON_v756: ITEM: 468"]
---

Hey Dungeoneers!

In this blog post I'm going to go over some of the new technical additions to Shattered in v2.1.3, and how they're going to allow for future content. In particular, I plan to use these additions in a reworked blacksmith quest in the next major update!

Shattered Pixel Dungeon is also [![](/assets/images/icons/steam.png){: .rounded .text-inline}25% off on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) right now, as part of the Steam Summer Sale!

## Sub-Floors and Mining

Firstly, this new quest will not take place in a regular floor of the dungeon, but instead will appear in a brand new special sub-floor that will exist purely for the quest!

Currently, Shattered uses a numerical value called 'depth' to keep track of where the player is in the overall dungeon. You can think of this as all of the levels existing in a 1-dimensional line, where the depth value determines how far along the line we are.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/depth.png){: .align-center}

To allow for sub-floors I've added a second number called 'branch', which effectively turns the 1-d line into a 2-d grid. When you descend to the blacksmith's quest area, depth won't change, but branch will go up by 1. Returning from the quest area sets branch back to its default of 0.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/depth-branch.png){: .align-center}

This change also includes code that lets levels have multiple entrances and exists that go to different locations! A lot of the code to support this has actually been in the game since v1.4, but I've added some more code recently in v2.1 patches so that sub-floors can actually exist. Here's a little gif showing off how this all works in practice:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sub-floor.gif){: .align-center .rounded-large}

In that sub-floor the player will be tasked with mining though walls in search of rare ores for the blacksmith. Mining itself was actually fairly easy to implement, as Shattered's systems for managing terrain changes are already pretty robust. A few bits of new logic in a few spots and everything was working! To mine the player simply moves to a wall tile and their character will get to work, assuming that they have a pickaxe and are in the quest area, of course.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mining.gif){: .align-center .rounded-large}

**You can test these new mechanics out right now in v2.1.3!** This initial implementation is a simple empty tester floor that just exists to let players try this out. There aren't any special mechanics around mining yet, and being in the tester area pauses hunger/regen effects.

## Making a Quest

These new mechanics are neat on their own, but what matters far more is how they're going to work in a completed quest!

In my initial concepting for this, back around v1.3, I wanted the to quest play a bit like a minigame, where Shattered's main gameplay was set aside in favor of something that felt very different. In such a design the player would be expected to mine through a level that's mostly filled with walls, somewhat like a game of [Motherload](https://store.steampowered.com/app/269110/Super_Motherload/) or [Dome Keeper](https://store.steampowered.com/app/1637320/Dome_Keeper/).

I had trouble 'finding the fun' with this design though, which is why the quest rework ended up getting delayed so much. It kept feeling like I needed to add more complexity to make these new mechanics interesting. This made the quest design become extremely large and cumbersome. Eventually I realized that my minigame approach wasn't working. Trying to put an entire extra game within a regular run of Shattered was just far too much.

I went back to the drawing board and instead tried to design the quest's mechanics to complement existing gameplay interactions, rather than replace them. This would mean that the quest would play more like regular Shattered with some extra spice added in from the mining mechanic. Here are a few examples of how that might work:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/examples.png){: .align-center .rounded-large}
- A passageway blocked by traps or other hazards is a big annoyance in regular Shattered, but during the quest it would be possible to mine around them.
- A level usually has to be pretty structured and interconnected, but with mining these levels could be much more free-form, possibly including rooms that are totally isolated.
- Large enemies normally can't chase you into a hallway, but in a more free-form level the mining mechanic could be what controls which areas of the level they can access.
- If the player can see some parts of the level before they mine to them, they would be able to choose how the level becomes interconnected and traversible.
- Of course, the player's ultimate goal is going to be to mine for gold, so the way that resource is placed in a level will influence how the player wants to dig to reach it.

These are some examples of how regular Shattered gameplay could be augmented a bit by the new quest's mechanics. I don't have the specifics of this pinned down just yet though, as I've mostly been busy with the technical implementation. There's quite a lot of work to be done on specific hazards and environments that would make use of the mining mechanic.

---

I'm going to get to work on designing and implementing the environments of the quest itself. **If all goes well you should hear from me about it in late July or August.** Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!

If you'd like some incremental updates on this leading up to the next blog post, consider following me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel) or [![](/assets/images/icons/twitter.png){: .rounded .text-inline}Twitter](https://www.twitter.com/ShatteredPixel)!

<div markdown="1" class="img-text">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider supporting me on [![](/assets/images/icons/patreon.png){: .rounded .text-inline}Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>


You can discuss this blog post on the [![](/assets/images/icons/reddit.png){: .rounded .text-inline}Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/14ma90g/coming_soon_to_shattered_subfloors_and_digging/), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3812908758669140297)! Note that the Pixel Dungeon Subreddit is currently set to NSFW in protest against Reddit Inc.'s recent actions. The subreddit does not actually contain any adult content.