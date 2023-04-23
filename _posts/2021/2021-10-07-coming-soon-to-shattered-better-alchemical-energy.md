---
title: "Coming Soon to Shattered: Better Alchemical Energy!"
excerpt: "v1.1.0 is focused on making improvements to the alchemy system and the various recipes it has. I'm doing a complete redesign of alchemical energy, lots of balance changes and tweaks to existing recipes, and adding a few new recipes as well."

header:
  image: /assets/images/2021/2021-10-07/header.png
  teaser: /assets/images/2021/2021-10-07/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#??? = Alchemical Catalyst item sprite in v0.9.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 349"]
---

Hey Dungeoneers, It's time to share some details on v1.1.0!

Sorry for the longer than usual lull in updates after v1.0.0 released. I've been very busy with some real-life stuff over the last few weeks, which meant having to push back plans for Shattered a little.

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/roguelike-celebration.png){: .align-left .rounded}](https://roguelike.club/) One of those real-life things is something you might be interested in though. I'm going to be giving a talk at this year's [Roguelike Celebration](https://roguelike.club/) on [October 16th at 6:30pm EDT!](https://www.timeanddate.com/worldclock/fixedtime.html?iso=20211016T1830&p1=3918&am=30) The talk is titled "Community-Driven Roguelike Development", you can find more details about it [Here.](https://roguelike.club/speakers2021.html#evan-debenham)
</div>

v1.1.0 is focused on making improvements to the alchemy system and the various recipes it has. My original plan was for alchemy to add cool new mechanics based on consumable items and easy ways to recycle consumable items you don’t want. The system *sort of* does this currently but has a lot of problems. Alchemy is complex, only marginally helps with recycling items, and a majority of its produce is overly situational or just plain underpowered. To improve this, I'm doing a complete redesign of alchemical energy, lots of balance changes and tweaks to existing recipes, and adding a few new recipes as well.

## Exotic Scrolls and Potions

Before delving into alchemical energy, let's go over some buffs and redesigns that I'm planning for exotic potions and scrolls. I want exotics to do a similar job to their regular counterpart, but to be generally more powerful and also work in a different way. Right now though many of them are too limited or situational, so I'm taking pretty much all of the less popular exotics and giving them some help.

Here are some of the changes coming to exotic potions:
<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gasses.png){: .align-left}
**Corrosive Gas and Storm Clouds** are both getting a simple straightforward buff. I’m boosting the starting damage on corrosive gas by 1 and having both potions start their AOE out in a 3x3 area, instead of at a single cell.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/shrouding-fog.png){: .align-left}
**Shrouding Fog** is currently quite hard to use well. I'm adjusting the smokescreen to still block vision for enemies, but the hero and allies will be able to see through it.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/magical-sight.png){: .align-left}
**Magical Sight** has an interesting tradeoff of vision range for more information and more duration, but clearly that tradeoff needs to be more generous. I’m buffing the vision range to 12 tiles, from 8.
</div>

And some of the changes coming to exotic scrolls:
<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/foresight.png){: .align-left}
**Foresight** is getting a BIG boost to its range, making it a bit more comparable to magical sight, but all about mapping. Of course 600 turns of this would be ridiculous, so it's getting a duration reduction in compensation.
</div>
<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dread.png){: .align-left}
**Petrification** is getting reworked into **Dread**. Rather than just being an AOE debuff, this scroll doubles down on enemy removal by making enemies so afraid they leave the dungeon entirely!
</div>
<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/challenge.png){: .align-left}
**Confusion** is getting reworked into **Challenge**, which might be a familiar scroll name for players of the OG Pixel Dungeon. This scroll emphasizes the enemy-attracting mechanic by drawing enemies to you and debuffing them.
</div>

Here's a little gif of the reworked scroll of foresight in action, quite a bit more impressive!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/foresight.gif){: .align-center .rounded-large}

## Alchemical Energy

Currently alchemical energy is a mostly arbitrary resource that the game just gives you as you find alchemy rooms. There is often more than enough energy for the player to craft what they want and so mostly energy ends up just adding complexity, rather than improving alchemy in any meaningful way.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/energy.png){: .align-left}
I think the best way to improve alchemical energy is to make it a much more integrated part of the alchemy system, so **I'm changing many recipes to use energy instead of seeds/stones, heavily reducing the energy that alchemy pots start with, and letting the player make more energy by sacrificing consumable items.**
</div>

This repositions energy as the core resource for alchemy. It would become a primary driving force both for the cost of recipes and for recycling consumables. Crucially, this would also be a lot more flexible than the current system, as once an item is turned into energy it could be used on anything. This also means several existing recipes can be made simpler. Exotic potions/scrolls will simply require a bit of energy instead of seeds/stones, and I may even do the same for catalysts as well.

## The Alchemy Interface

While the alchemical energy change should improve alchemy overall, it also means that one set of ingredients can have multiple possible recipe outputs. The alchemy UI needs to be adjusted to compensate for this. You can see a WIP draft of that changed interface below.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/alch-ui.png){: .align-right .rounded-large}
Consider the player putting a scroll into the pot, do they want to scrap it for energy, turn it into stones, or spend some energy and turn it into an exotic scroll? With the previous alchemy recipes the only option was to turn the scroll into stones, so there only needed to be one output. However, now I'm redesigning the interface to work with up to 3 or 4 potential outputs for one item.

There is a risk of adding too much complexity here, so I'm going to do my best to ensure this change doesn't make the alchemy interface too cumbersome or visually cluttered. If I do it right this change should be mostly a good thing from a usability standpoint, as recipes will be simpler and it'll be easier to see what produce a particular item can generate at a glance. There's definitely some work to do from the draft image though, such as adding a confirmation window, or info buttons for each potential recipe output.
</div>

## Beta When?

Unfortunately the beta for v1.1.0 is a little ways off still, but I won't be silent for all of October! There's going to be another blog post very soon that's about new platforms, and then there will be another post a little later (probably early November) with a beta for v1.1.0.

In the meantime, I plan to be sharing some smaller updates on [![](/assets/images/icons/twitter.png){: .rounded .text-inline} Twitter!](https://www.twitter.com/ShatteredPixel) This will include some GIFs showcasing various alchemy recipes as I buff and adjust them. That GIF of the scroll of foresight rework was actually shared on twitter last week!

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, and recently started getting access to early playtests of content updates!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/q3j5yg/)