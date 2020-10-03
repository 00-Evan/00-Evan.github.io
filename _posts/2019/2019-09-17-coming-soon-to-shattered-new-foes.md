---
title: "Coming Soon to Shattered: New Foes!"
excerpt: "0.7.5 is the first in a series of two updates that are aimed at improving and expanding the enemies within the dungeon. In 0.7.5, I'm expanding the early stages of the game by focusing on the sewers and prison."

header:
  image: /assets/images/2019/2019-09-17/header.png
  teaser: /assets/images/2019/2019-09-17/header.png
  width: 1260px

#This field is parsed by Shattered Pixel Dungeon to display an ingame icon in its news feed
tags: ["sprites/necromancer.png, 0, 0, 16, 16", "SHPD_INGAME"]
---

Hey Dungeoneers, the next Shattered update is coming soon, here's what to expect!

0.7.5 is the first in a series of two updates that are aimed at improving and expanding the enemies within the dungeon. In 0.7.5, I'm expanding the early stages of the game by focusing on the sewers and prison. Here's a look at the major things coming:

## New Enemies

There are a total of three new enemies being added, two in the sewers and one in the prison!
*(Note that some of these sprites are still WIP, I intend to improve them before full release)*

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/snake.png){: .align-left}
**Snakes** are a new earlygame enemy, meant to complement rats and gnolls. They have the lowest HP of any standard enemy, but make up for it by being very evasive. Snakes will go down very quickly if the player uses magic or surprise attacks, but otherwise they have more effective HP than a sewer crab! Snakes are meant to emphasize the importance and value of surprise attacks, and should give players a bit more control over the earlygame as a result.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/slime.png){: .align-left}
**Slimes** appear later in the sewers, and are meant to be at a similar power level to sewer crabs. Slimes aren't acidic like Goo, and are instead more elastic. This bounciness gives them a unique form of damage resistance: there is a hard cap to the amount of damage they can take from a single hit. Slimes are an introduction to enemies with unique abilities and enemy types which reward the player for having defense instead of offense. Lucky adventurers might find a weapon stuck into a slime after killing it, though it probably won't be of a high tier.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/necromancer.png){: .align-left}
**Necromancers** are a new powerful prison enemy, but their power doesn't come from their stats alone. Necromancers have no direct attack power, and instead fight by summoning and buffing skeletons! This presents a new challenge to players, as a necromancer's summons are expendable, you'll need to get to them to win the fight. Necromancers are also an interesting mix between ranged and melee, as they won't attack from a distance, but can summon skeletons from a distance.

## Boss Improvements

I'm improving the mechanics of the boss fights in the first two regions as well!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/goo.png){: .align-left}
**Goo** is already a fairly solid first boss, so I'm focusing on refining what is already present.

Goo's floor is getting a brand new layout, with unique new rooms that Goo will spawn within. I'm also making a couple specific balance changes to Goo. Back in 0.6.1 I added some ring-based tunnel rooms, and gave these rooms a high chance to spawn on Goo's level. My thought process was that these ring rooms would give players more space to maneuver, but experienced players used them to trick Goo's AI and rack up a large number of free surprise attacks. While I'm certainly not opposed to giving experienced players ways to excel, this was a little too extreme. I'm removing these ring hallways to level the playing field between new and experienced players a bit, and I'm also reducing Goo's damage slightly to compensate. This should make the boss a little easier for everyone, not just veterans.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tengu.png){: .align-left}
As for **Tengu**, I already gave this fight a huge overhaul way back in v0.3.2, but large aspects of that rework didn't quite fit right. While the fight is nicely cinematic on your first run though, the mazes and chasing quickly become a chore, and the fight overall was a bit too easy. So, in 0.7.5 I'm keeping a similar theme but reworking the fight once again!

Tengu is getting several new abilities, which should make the fight much more dynamic and interesting. While some amount of mazes and tengu-chasing are still present, it's now much more tightly focused, which should keep things feeling like you're fighting an actual boss, and not navigating a level. I'm pretty confident that after these changes Tengu will be the most interesting boss in Shattered, at least until I change the later bosses as well! 

## LibGDX Conversion

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/libgdx.png){: .align-left}
A bit of an aside, this change is actually already ingame as of 0.7.4b, but I didn't feel it justified its own blog post. Shattered is now mostly running through the multiplatform game library [LibGDX](https://libgdx.badlogicgames.com/)! This is a major step towards releasing Shattered on other platforms, as I first mentioned in my [2019 plans blog post](/blog/shattered-pixel-dungeon-in-2019.html). There is still more technical work to be done on this front though. I'm fixing several bugs caused by the conversion in 0.7.5, and text rendering and software keyboard input are still coupled to Android.

Even when the game is working 100% through LibGDX, there will still be more work needed before I can actually release on other platforms. Some of that is still technical, such as supporting keyboard and mouse input on desktop. Other parts are more logistical, as no Pixel Dungeon version other than the original has yet released on places like Steam of the iOS appstore. At this stage I can at least guarantee that Shattered will release on desktop via itch.io, but the rest is still a bit up in the air.

---

I'm expecting to release 0.7.5 in about a week and a half, so look forward to these additions soon!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/d5zmgi/)

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel)
If you'd like to support the development of Shattered Pixel Dungeon, please consider either making a purchase in the Google Play version of the game, or [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) The Patreon was **recently expanded to include new benefits**, and I intent to keep building it over time.