---
title: "Coming Soon to Shattered: New Content and Steam!"
excerpt: "Hey Dungeoneers! Sorry for the wait, but v1.2.0 is finally getting close to release! v1.2.0 will be fully launching on all platforms on Wednesday March 23rd at Noon EDT! The biggest story with v1.2.0 is definitely the Steam release, but I've already spent a lot of time talking about that. For the rest of this blog I'll be focusing on the other game content coming in v1.2.0."

header:
  image: /assets/images/2022/2022-03-17/header.png
  teaser: /assets/images/2022/2022-03-17/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#241 = Armband item sprite in v0.9.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 241"]
---

Hey Dungeoneers! Sorry for the wait, but v1.2.0 is finally getting close to release!

<div markdown="1" style="display: inline-block;">
![](/assets/images/2022/2022-01-09/steam.png){: .align-left .rounded-large }
The beta is available now, and v1.2.0 will be fully launching on all platforms on <u><b>Wednesday March 23rd at Noon EDT!</b></u>

Most notably, this will be the first version of the game to release on Steam!
</div>

The biggest story with v1.2.0 is definitely the Steam release, but I've already spent a lot of time talking about that. For the rest of this blog I'll be focusing on the other game content coming in v1.2.0. If you want to learn more about the Steam release, consider reading these past blogs, or [trying out the demo!](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/):
- [ShatteredPD will be at Steam Next Fest!](/blog/shatteredpd-will-be-at-steam-next-fest.html)
- [Shattered Pixel Dungeon is Coming to Steam!](/blog/shattered-pixel-dungeon-is-coming-to-steam.html)

## New Boss Music!

Just as in v1.1.0 and v1.0.0 before it, v1.2.0 has some new music! This time the game is getting a track for each of the five bosses. They're much more intense than the region tracks, but definitely still have a similar feeling. You can give them a listen below, or play through the game if you'd like to hear them in action for the first time:

{% include video id="xtwotR7NeXw" provider="youtube" %}

Just as before, these tracks were composed by [Kristjan Thomas Haaristo](https://www.youtube.com/channel/UCL1e7SgzSWbD_DQxB_5YcLA)! There may still be more music to come, but after these boss tracks Shattered will have a proper soundtrack! If you like the music, we're working on a few ways for the soundtrack to be directly purchasable in the future.

## Alchemy Item Balance

Back when v1.1.0 released, I promised to do a full pass on alchemy balance once the dust had settled. So far it seems that the changes made to alchemy in v1.1.0 have been a great success, with usage of exotic scrolls and potions up across the board. Not all other recipes are doing so well though, so I'm making a variety of improvements, mainly focused around recipes that use a lot of energy:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/alchemy.png){: .align-center}

- Exotic bombs are getting big cost reductions across the board, and several brews and spells are getting smaller cost reductions.
- Elixirs are actually doing fairly well, so I'm not planning any direct changes there yet, as I wanted v1.2.0 to focus more on buffs.
- Caustic Brew is getting a flat +1 to its damage, which should let it more effectively out-pace the damage from potions of toxic gas.
- Curse Infusion is going to boost an item’s level by a small % instead of just +1. This makes it a lot more worthwhile on highly-upgraded gear.
- Phase shift is going to actually properly clear enemy aggro and stun its target for 10 turns (bosses are immune). This makes it much more effective at delaying enemies, but also makes it quite dangerous to use on yourself.
- Aqua blast is going to get a larger water AOE and will throw targets around like a geyser trap.
- Summon elemental is getting more uses and scaling stats depending on the dungeon region. Newborn elementals in particular are getting buffed to start at full health as well. The spell will also be re-castable, to return a summon elemental to your position.
- Lastly, while they don't use any energy, I'm also making a bunch of buffs to a variety of tipped dart effects. Ally effects in particular are getting big duration boosts.

## New Special Rooms!

v1.2.0 also includes some levelgen improvements in the form of more special rooms! Shattered has had loads of changes and additions to level layours, and every other room type, so it's about time for special rooms to get some love. I"m adding six new special rooms in total:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/crystal-rooms.png){: .align-center .rounded-large }
Firstly, two new rooms (and one existing room) will use crystal doors! These doors let you see through them and require a crystal key to open. Just like with existing crystal chest rooms, this opens up some neat possibilities, as seeing loot doesn't mean you can go grab it yet.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/hazard-rooms.png){: .align-center .rounded-large }
Next, there are three new rooms with hazards that you’ll need to overcome. There are multiple solutions, just like other hazard rooms, but the default solution to each room involves a potion of purity, frost, or haste. Be careful, as the hazards in these rooms can deal some serious damage if you don’t properly mitigate them.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sacrifice-rooms.png){: .align-center .rounded-large }
Finally, I’m reintroducing sacrifice rooms! These rooms are from the original Pixel Dungeon and granted a scroll of ‘wipe out’ if enough enemies were defeated atop the sacrificial fire. I’m changing up the reward these rooms give, but their mechanics are otherwise very similar to the original Pixel Dungeon.

I've also included a few small tweaks to level feelings. The secrets level feel should be less aggressive in how it hides individual rooms, and the game's depth indicator now includes separate icons for each type of level feeling.

## Armband Rework!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/armband.png){: .align-left } v1.2.0 also includes a rework to the Master Thieves' Armband! Currently the armband suffers from having extreme usefulness in shops, and being a waste of an equip slot everywhere else. I'm redesigning it to charge based on exxp gain instead of gold collected, and giving it a new abiltiy so it can be useful anywhere in the dungeon.

You can still steal from shopkeepers, but can now also use the armband to rob regular enemies! Doing this will give you an extra chance to get an item drop, and also briefly disorients the enemy. As the armband levels the chance for loot and debuff duration increase. Robbing an enemy takes no time, so it has use as a utility combat action as well as a looting tool.

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/SHPD.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) The beta for v1.2.0 is live right now! You can get it on [Google Play](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon), on [Apple TestFlight](https://testflight.apple.com/join/4PWFyask), or directly download for Android or Desktop via [Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases/). Note that the TestFlight release is currently awaiting approval from Apple. The game's demo on Steam will also be updated for the v1.2.0 beta in another day or two, once any serious bugs have been ironed out.
</div>

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider buying the game when it releases on steam, [or supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls.
</div>

Expect another blog post once v1.2.0 releases next week, where I'll detail my plans for v1.3.0. With the Steam release I think the long saga of porting updates is ending, and I can finally start focusing on game content!

You can discuss this blog post on the [Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/tgi73b/), or on the [Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3191369524222268369)