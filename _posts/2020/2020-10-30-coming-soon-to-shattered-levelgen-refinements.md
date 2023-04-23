---
title: "Coming Soon to Shattered: Levelgen Refinements!"
excerpt: "Hey Dungeoneers, v0.9.1 is progressing nicely, so it's time for me to share one of the two major things I'm working on for it! In addition to new talents (more on that soon), v0.9.1 will feature some big improvements to the game's level generation algorithm!"

header:
  image: /assets/images/2020/2020-10-30/header.png
  teaser: /assets/images/2020/2020-10-30/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon for display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: DEPTH"]
---

Hey Dungeoneers, v0.9.1 is progressing nicely, so it's time for me to share one of the two major things I'm working on for it! In addition to new talents (more on that soon), v0.9.1 will feature some big improvements to the game's level generation algorithm!

## Why Levelgen?

Way back in v0.6.0 I reworked Shattered's level generation algorithm with the goal of making it much more flexible and powerful. You can read a bit more about that here: [part 1](/blog/whats-coming-in-shattered-pixel-dungeon-v060-2.html), [part 2](/blog/whats-coming-in-shattered-pixel-dungeon-v060.html). Aside from [adding secret rooms in v0.6.2](/blog/coming-soon-to-shattered-better-secrets.html), I haven't done that much with the new levelgen system though. Things have been largely unchanged from v0.6.0, with just a few small improvements here and there. 

After v0.9.0 was released, I decided to do a poll on [Patreon](https://www.patreon.com/ShatteredPixel) with a few options for what content I could add in v0.9.1 alongside new talents. Levelgen was one of the options, and won by a pretty commanding margin. So, for v0.9.1 I've taken a look into the levelgen system and identified what I think are the easiest, but also most impactful improvements I can make. 

## New and Improved Rooms

Let's start with the simplest change, I've added one new room to each of the game's five regions, and made improvements to several of the game's existing region-specific rooms!

For the new regional rooms, I tried to focus on more distinct room shapes that worked best at large room sizes. Historically rooms like this (such as sewer pipe rooms and cave rooms) have had the most meaningful impact on how distinct each region feels. Ideally I want each region to have a bunch of diversely shaped rooms that make them feel different from each other.

- The sewers is getting a large circular sewer basin room.
- The prison is getting a large cell block room.
- The caves is getting a room with chasm fissures that are connected via bridges.
- The dwarven city is getting a more enclosed segmented library room.
- The demon halls is getting a room with semi-randomly placed chasm tiles.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-rooms.png){: .align-center}

I've also made some improvements to existing regional rooms. The goal here was to try to take some of the most bland rooms and make them a bit more interesting. Lots of rooms received changes, here are the most significant ones:

- Pillar rooms have been moved to the prison from the dwarven city, and now always spawn with four pillars if they are large or giant.
- Statue rooms have been moved to the dwarven city from the prison, and now sometimes spawn statues in their center.
- Hallway rooms have been tweaked to spawn a statue in the center of their path.
- Circular skull rooms now always spawn as large or giant.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/changed-rooms.png){: .align-center}

## New Level Feelings

I also looked into expanding the game's level feelings. 'Feelings' are a type of level variation that randomly occurs and is announced to the player when they descend to a new floor. The game currently has four of them (grass, water, chasm, and dark), and I'm adding three more:

(you can click/tap on each picture to view a larger version)

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
<a href="/assets/images/2020/2020-10-30/large-feeling.png" title="A large level in the sewers." class="image-popup">
    <img src="/assets/images/2020/2020-10-30/large-feeling.png" alt="" width="200px" class="align-left">
</a>
The first is a **large level feeling**, which amps up the number of rooms generated and the overall contents of a level. Large levels always spawn with 1.5x their max room count, but also have more items, food, and a bonus special room to reward the extra walking time.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
<a href="/assets/images/2020/2020-10-30/traps-feeling.png" title="A traps level in the prison, look at all the (deadly) colors!" class="image-popup">
    <img src="/assets/images/2020/2020-10-30/traps-feeling.png" alt="" width="200px" class="align-left">
</a>
Next is a **trap level feeling**, which amps up the danger along the ground of a level. A trap floor has 5x the total number of traps it would normally spawn with, but 4/5 of those traps are always visible. This leads to a more crowded floor layout with lots of chances to use traps against your enemies, rather than more opportunity to just step onto traps.
</div>

<div markdown="1" style="display: inline-block;">
<a href="/assets/images/2020/2020-10-30/secrets-feeling.png" title="A secrets level in the city, where many doors are hidden." class="image-popup">
    <img src="/assets/images/2020/2020-10-30/secrets-feeling.png" alt="" width="200px" class="align-left">
</a>
Lastly, I decided to add a **secret focused feeling**. Levels with a secret feeling contain a bonus guaranteed secret room, but also have an increased number of hidden regular doors. Normal levels have a rule where there must always be an unhidden path to every non-secret room, but secret floors ditch this limit, and so might be quite tricky to navigate!
</div>

## Big Layout Improvements

While new rooms and feelings are great, the bulk of my dev effort has been spent on more in-depth improvements to the levelgen algorithm itself. As mentioned, I initially rewrote levelgen in v0.6.0 with the intention of improving it in the future, and so some of that is long overdue!

(you can click/tap on each picture to view a larger version)

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
<a href="/assets/images/2020/2020-10-30/loop-layout.png" title="An example of a more interconnec loop-based level." class="image-popup">
    <img src="/assets/images/2020/2020-10-30/loop-layout.png" alt="" width="200px" class="align-left">
</a>
**Firstly, I've made a bunch of small tweaks to the existing layout logic.** Mainly I've made a level's core shape a bit less prominent, and increase the chance for rooms to be placed near to each other and be connected. These tweaks make level layouts more diverse and interesting, without any changes to the level layout algorithm itself.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
<a href="/assets/images/2020/2020-10-30/merging.png" title="An example of room merges with a giant room involved." class="image-popup">
    <img src="/assets/images/2020/2020-10-30/merging.png" alt="" width="200px" class="align-left">
</a>
**I've also made some big improvements to how the algorithm handles adjacent rooms.** Back in the original Pixel Dungeon it was possible for connected adjacent rooms to be merged, or for there to be chasm between two adjacent rooms in the caves. Both of these are technically possible in Shattered currently, but weren't properly adapted to the new system and so happen very rarely. Merges can now happen in a bunch more cases, which can create some really interesting room layouts.
</div>

<div markdown="1" style="display: inline-block;">
<a href="/assets/images/2020/2020-10-30/figure-eight.png" title="An example of a level build using a figure-eight pattern." class="image-popup">
    <img src="/assets/images/2020/2020-10-30/figure-eight.png" alt="" width="200px" class="align-left">
</a>
**Lastly, I have added a new level layout!** Currently all standard levels use a builder algorithm that lays out an initial loop of rooms, but in v0.9.1 I'm adding one that uses a figure-eight shape! The figure eight layout ends up looking like a denser room cluster or a line depending on how the two loops take form. I’ve designed the layout to place the largest room in the center most often, which helps take some of the game’s more distinctive large rooms and make them the centerpiece of a level.
</div>

## What About Talents!?

With all of this talk of levelgen improvements, you might be wondering if something happened to the plans for talents! Rest assured, I am also well into designing tier 2 talents, and am also working on some improvements to tier 1 based on feedback. In particular, while I think it's fine for some talents to be more short-term than others, even at tier 1, I agree with the sentiment that there are some t1 talents that are too useful in the later stages of the game. I plan to adjust or move some of the t1 talents to correct this.

I'm going to write another blog for talents in two or three weeks, which is will also be when v0.9.1 goes to beta!

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, and also help determine content direction through community polls! As mentioned, Patrons helped determine the content direction for v0.9.1, and have been getting early info about levelgen changes for the last month.

---

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/jl37c2/)