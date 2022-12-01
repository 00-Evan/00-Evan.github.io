---
title: "Coming Soon to Shattered: A New Hero!"
excerpt: "Hey Dungeoneers! v2.0.0 is unfortunately still a little ways off, but I am far enough into development that I've got a bunch of details to share! While there are a few other odds and ends in v2.0.0, the major focus is a brand new hero! This blog will go over some of my design thoughts and early implementation work on this new hero."

header:
  image: /assets/images/2022/2022-12-01/header.png
  teaser: /assets/images/2022/2022-12-01/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#116 = sai sprite in v0.9.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 116"]
---

Hey Dungeoneers! v2.0.0 is unfortunately still a little ways off, but I am far enough into development that I've got a bunch of details to share!

While there are a few other odds and ends in v2.0.0, the major focus is **a brand new hero!** This blog will go over some of my design thoughts and early implementation work on this new hero.

## What Should a New Hero Do?

Each hero in Shattered Pixel Dungeon attempts to fill out a fairly broad gameplay and thematic archetype. A new hero should fit into an open space within that roster, both in terms of theme and gameplay.

Currently we have two heroes focused around agility and the environment (Rogue and Huntress), one hero focused around magic (Mage), and one hero focused around direct combat (Warrior). Thinking of the heroes this way creates a clear opening for another magic user and another direct fighter.

Of those two openings, I'm working on a new direct fighter first: **The Duelist!** She focuses on weapons and activated abilities, to contrast with the Warrior's focus on armor and passive durability. Here's an early peek at her splash art:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/duelist-tease.jpg){: .align-center .rounded-large}

## Weapon Abilities!

The Duelist fills in a sorely needed gap when it comes to the game's existing weapon mechanics. Weapons are foundational to gameplay in Shattered, so I kept them simple to create room for more complex mechanics elsewhere (artifacts, wands, rings, etc.). Nevertheless, this ends up making weapons feel a bit lackluster. A very common point of feedback I get is that players would like to see weapons themselves do more.

The Duelist is a perfect opportunity to address that feedback. Her primary power is a **unique ability that changes on a per weapon basis**. These abilities are meant to augment gameplay and also provide a more visible and interactive power to each weapon.

Here are a few examples of weapon abilities that I've already fully designed and implemented:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/weapons.png){: .align-center}

- The Duelist can **lunge** with her rapier starting weapon. This attack requires an enemy to be 1 tile away, but is guaranteed to hit and deals a whopping +67% damage. This makes weapon abilities a significant part of the Duelist's earlygame power and encourage a little bit of early positioning gameplay.
- The Duelist can **cleave** an enemy with regular sword type weapons. This is a fairly simple ability that guarantees a hit and does a little bonus damage. It's best used as a finisher, as a kill makes cleave instantaneous and lets you cleave again for free. Lower tier swords get slightly more bonus damage.
- While it is a sword, the runic blade has a unique **runic slash** ability. This is still guaranteed to hit, but offers a bunch of extra enchantment power instead of cleave's other benefits.
- The Duelist can **sneak** with dagger type weapons, blinking her to a nearby tile and granting her 1 turn of invisibility. This is great for repositioning or guaranteeing a surprise attack hit. This ability costs 2 charges, and lower tier daggers get a bit more blink range.
- The Duelist can **spike** enemies with the tip of a spear or glaive. This attack doesn't work on adjacent enemies and deals reduced damage, but is guaranteed to hit and knocks the enemy one tile back. This is very handy for working around a spear weapon's low speed.
- The Duelist can **guard** herself with a round shield or a greatshield. This completely negates the next physical or magical attack made against her. Starting to guard spends a turn, so it's best used to block a single heavy attack or in anticipation of an approaching enemy.

## Subclass Designs

While they're not quite as solid as the various weapon abilities just yet, I do have two very promising subclass designs to share as well:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/subclasses.png){: .align-center}

- The Duelist's first subclass directly enhances weapon abilities, by letting her **equip two weapons at once**. This subclass will let the Duelist freely switch the weapon she is attacking with and use either weapon's ability whenever she wants. If one of her equipped weapons is higher level and the same or higher tier, it will also share its upgrade level with the weaker weapon!

- The Duelist's second subclass focuses on **physical technique and martial arts**. This subclass will build up power during combat, which can then be spent on a number of abilities, mainly focused around utility and defense. The class might end up playing like a more relaxed and utility-focused version of the Gladiator, where points are easier to build and maintain but are less useful for outright killing enemies.

## Beta When?

Implementation work on the Duelist is now going full steam ahead, but unfortunately I'm not in a position to commit to a beta date yet, especially with the holidays coming up.

I think it's most realistic to expect something in January. This gives me enough time to ensure everything is working well, and also means I'm not rushed to get something out before the holidays start.

You can look forward to another blog post when the beta is ready, which will provide more detail on the Duelist's subclasses, armor abilities, and talents!

You can also get some quicker small updates by [![](/assets/images/twitter-icon.png){: .rounded .text-inline} following me on Twitter](https://www.twitter.com/ShatteredPixel). Due to recent events I am actively considering moving away from Twitter, but if that happens I will post on Twitter to let people there know about the move.

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/patreon-icon-2021.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/reddit-icon.png){: .rounded .text-inline} Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/z9vrho/coming_soon_to_shattered_a_new_hero/), or on the [![](/assets/images/steam-icon.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3713810544734832979)!