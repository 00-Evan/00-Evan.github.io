---
title: "Coming Soon to Shattered: Seeded Runs!"
excerpt: "I've got some news to share about v1.3's development! I've implement support for custom seeds, a new scoring system, and a few other miscellaneous changes. However, development on v1.3 has been going slower than planned, so I don't have a beta or release date to share yet."

header:
  image: /assets/images/2022/2022-05-02/header.png
  teaser: /assets/images/2022/2022-05-02/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#371 = Sungrass seed item sprite
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 371"]
---

Greeting Dungeoneers!

I've got some news to share about v1.3's development! I've implemented support for custom seeds, a new scoring system, and a few other miscellaneous changes. However, development on v1.3 has been going slower than planned, so I don't have a beta or release date to share yet.

Also in non-development news, Shattered is part of Steam's "Going Rogue" sale that runs this week! The game is 15% off on Steam during the sale, and I've taken the opportunity to [spruce up the game's store listing as well.](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/)

[![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/going-rogue.png){: .align-center .rounded-large}](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/)

## Custom Seeds!

Probably the largest single feature coming in v1.3 is support for custom seeds! When the game generates the dungeon, a lot of purely random calculations are involved. If they're given a numerical 'seed', then these calculations always give the same result. Normally the game generates a random seed each time, but starting in v1.3 players who have won at least once can optionally enter a custom seed!

Each seed is represented by nine uppercase English letters, with optional dashes in between for readability. You can also enter whatever you want in the text box (like a name or place) and the game will convert it to a seed behind the scenes.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/seed-entry.png){: .align-center}

As an example, the header image for this blog post is the first floor from my in-development version of v1.3 with the seed ABC-ABC-ABC.

I'm also planning on using this functionality to add daily runs! Each day you'll be able to start a run with a pre-determined seed that's the same for everyone! This makes it easy to play the same game as everyone else, without having to directly share seeds with each other. Note that daily functionality will be pretty basic to start, there won't be any online leaderboards.

## A New Scoring System

With seeded runs being added, now seemed like an excellent time to improve the game's scoring system too! The current system is very simple, with just 3 components:

- **Progression**, which determines most of the score; it maxes at 78k.
- **Treasure**, which is just equal to total gold collected.
- **Winning** will also double your score.

In total a winning run will be worth about 85-100k points before the win multiplier, but an infinite score is technically possible with gold farming. I'm planning to implement a new scoring system that should measure overall run performance much more effectively:

- **Progression** will be scaled back to make room for more score categories.
- **Treasure** will include held items and will have a cap to prevent score farming.
- **Exploration** will grant a bonus for each floor that's reasonably fully explored.
- **Bosses** will grant a bonus based on how often you were hit by avoidable attacks or hazards.
- **Quests** will give a fixed bonus for completion, but may be performance-based in the future.
- **Winning** will still double score, but you'll get a slightly bigger multiplier for a surface win.
- **Challenges** will provide an additional multiplier that stacks with itself.

Overall I'm expecting a perfect score to be about 100-120k before multipliers, though winning with a bunch of challenges enabled will be able to easily push this past 1 million. This, combined with seeds and dailies, should make it much more possible to compare your skills against other players!

## Other Changes

There are a few other significant adjustments that I already have in place for v1.3:

I've implemented a change that makes it possible to have more than one floor at a particular depth! This opens up a lot of possibilities, as the dungeon doesn't need to be a straight line from floor 1 to 26 anymore! To start with, I'm planning on using this so that quests can have their own sub-levels. If all goes well, I'll rework the blacksmith's quest in v1.4 to use this new functionality.

I've also made a few improvements to the scroll of metamorphosis. Currently there are 10 talents which are excluded from appearing for other classes, but I've whittled that down to just two. These talents will now have a slightly different effect when metamorphed, mostly to help other classes use the effect without unique class items. A few are a bit of a stretch, but most of them are essentially the same as their regular versions.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/metamorph.png){: .align-center}

Lastly, based on the results of a poll from [![](/assets/images/patreon-icon-2021.png){: .rounded .text-inline} Patreon](https://www.patreon.com/ShatteredPixel) I've gone over all of the buff icons in the game and eliminated (almost) all cases of duplicates. There are still plenty of recolors, but it should be basically impossible to have two buffs with the exact same icon now. I've also added icons to a couple of buffs that needed them. Here are a few examples, from left to right, old on top new on bottom: featherfall, targeted, adrenaline, cloak of shadows, fire imbue, and nature's power.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/buff-icons.png){: .align-center}

## Still Some Work To Do

I've still got a fair bit to add before v1.3.0 is ready for beta and release though, Here's a quick rundown of what I'm still planning:

- I'm going to be making several **UI and UX improvements** as a followup to v1.2. In particular I want to add better enemy info in the new full UI, radial menu support for controller players, better controls tutorialization, a better settings menu, and support for 6 quickslots on the mobile portrait view.
- I'm also making some more **incremental badge improvements** in v1.3. Expect some adjustments to existing badges and several additions. In particular I'm adding some more 'death by X' badges, and a new challenge badge for each of the game's bosses.
- A few **curses** are also getting improved in v1.3. Some curses are a lot more interesting than others and so I'm going to be taking the most boring and directly harmful ones and change them to give the player a little more to work with.
- Lastly, I'd also like to make some specific changes to the game's **ascension route** to make it more challenging. Currently it's too easy to simply run back to the surface, and enemies become trivially weak after only a few floors. The changes in v1.3 won't be a full rework, but I would like to improve on these issues.

Expect another blog post with a beta in about another month, hopefully in late May or early June. In the meantime I'm going to try to post at least once a week on [![](/assets/images/twitter-icon.png){: .rounded .text-inline} Twitter](https://twitter.com/ShatteredPixel), if you'd prefer news at a quicker pace.

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/patreon-icon-2021.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider buying the game on Steam, [or supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls.
</div>

You can discuss this blog post on the [![](/assets/images/reddit-icon.png){: .rounded .text-inline} Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/ugv2d1/), or on the [![](/assets/images/steam-icon.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3273564019260330643)!