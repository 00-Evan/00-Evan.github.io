---
title: "Coming Soon to Shattered: Talented Heroes!"
excerpt: "I've been teasing this for a while now. A little bit way back in 2019, and in earnest since the beginning of this year. So, it's finally time for me to talk about v0.9.0, which is adding a new gameplay system to Shattered Pixel Dungeon!"

header:
  image: /assets/images/2020/2020-09-23/header.png
  teaser: /assets/images/2020/2020-09-23/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: TALENT"]
---

Hey rat punchers!

I've been teasing this for a while now. A little bit way back in [2019](/blog/shattered-pixel-dungeon-in-2019.html#new-gameplay-system), and in earnest since [the beginning of this year.](/blog/shattered-pixel-dungeon-in-2020.html#new-gameplay-system) So, it's finally time for me to talk about v0.9.0, which **is adding a new gameplay system to Shattered Pixel Dungeon!**

## The Impetus for a New Game System

So, why add another new gameplay system? Especially after the complexity of the v0.7.0 alchemy overhaul, many of you might be understandably wary of another big moving part in the game. I'm designing this system to be much less complex than alchemy, and want to add it because I see a specific issue in the game that needs to be addressed:

<u><b>Leveling up in Shattered isn't fun.</b></u>

The game is full of fun progression when it comes to items, but for the hero the fun only happens at hero select, subclass select, and when class armors are granted. The frequent levelling that the player gets is necessary for the stat boost but does nothing for the game’s fun factor. 

This is hardly a Shattered-exclusive problem, and a bunch of other games have their own various systems for this. You can call them skills, abilities, perks, etc. but the core idea is the same: give the player some incremental and customizable power as their hero levels up. This deepens the game’s strategy and gives another source of progression and consistent fun. So, in v0.9.0 I am adding a **Talent System** to Shattered Pixel Dungeon!

## How Should Talents Work?

So then, what exactly are talents going to be? There are a wide range of possible effects, but I think they fit into three categories:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mage-robe.png){: .align-left}
Probably the most obvious type of talent is something with an **active effect that’s triggered whenever the player wants.** I’m a bit wary of these as the game already has a bunch of player-controlled effects via items. Adding even more of these threatens to make the game too complicated. That’s not to say they should be avoided entirely though, just used very sparingly.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/upgrade-scroll.png){: .align-left}
Another obvious type is something with a **passive effect that manipulates stats.** I worry these will be too boring though, as they often don’t noticeably affect gameplay. This is the opposite problem of active abilities, which may influence gameplay too much. Just like with actives, that doesn’t mean purely passive effects are totally out though, they just have to be used judiciously.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ration.png){: .align-left}
I think the best type of talent is one with an **effect that activates on a specific trigger.** I feel pretty confident that these will make up the bulk of the system, as I’ve had a lot of success with these effects in other parts of Shattered’s design. They enhance the player’s interaction with specific parts of the game without the complexity burden of activating them directly.

## How Should the System Be Structured?

Now that we have an idea of how an individual talent might work, the next question is how will talents be structured to make a complete system? Unlike talent types, which can be mix and matched, we can only have one structure for the system, so making the right choice here is paramount.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tree-struct.png){: .align-left}
Probably the default structure for a system like this is a skill tree or similar, but I don't think this is the right fit for Shattered. Skill trees are complex and geared toward a completed build, with branching paths and lots of dependencies. This creates a structure that’s really satisfying to plan out and see completed, but runs don’t always make it that far in Shattered. Additionally, skill trees would force the player to plan out their build from the start of the game. Imagine the frustration of making build choices in the earlygame that don't end up fitting the gear you find.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/linear-struct.png){: .align-left}
So then if a tree is too complex, what about something that's very simple? Some games have a system with just one or two choices at each level. Sometimes the choices are the same every game, or they might be randomly selected from a pool of possible choices. While this could work, I think it's too far on the simple end. If the choices are the same every time then player choice ends up being limited, and the system will feel repetitive very quickly. Random choices would make the player even more at the mercy of RNG, and there won't be a clear sense of talent progression as the hero levels.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/layered-struct.png){: .align-left}
So, can we have a system that preserves players choice and progression, but also isn't overly complex or reliant on build planning? Yes! I've decided to go with a layered system for Shattered Pixel Dungeon's talents. Talents are split into multiple tiers that span ranges of hero levels. When the player gains a level, they get a point to spend on talents within that tier. Talents within one tier are totally independent of talents in other tiers. This keeps the number of choices in check, preserves player choice and a feeling of progression, and doesn't require the player to plan out a build that they may never achieve.

## Implementing the First Tier

*Please keep in mind that balance and visuals here are still a WIP. Some of the stuff I'm showing off may change before or shortly after full release.*

The system's first tier is going to span levels 1 to 6, with a total of five points to spend. Each hero has their own set of 4 talents, which can take a max of 2 points each, so the player can fill a max of 5/8 talent point slots in this tier.

Talents in this tier are mainly focused on earlygame effects that don't scale well into the mid or lategame. I'm designing the tier this way as I don't want players to feel like they need to sacrifice earlygame power for lategame power right when the run has just started.

I'm not looking to make the earlygame way easier though, so I'm also taking the opportunity to reposition a few hero innate abilities into talents. For instance, every hero now has a talent that works with food, instead of the Warrior and Mage have innate food-related powers. I'm also throwing in an extra requirement to try to better encourage new players to eat when they're injured:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/food-talents.png){: .align-center}

I'm also giving each hero a talent relating to identification speed, which should be quite useful in the earlier stages of the game when the player is trying to ID gear to use. For the Mage this replaces his innate wand identifying power:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ID-talents.png){: .align-center}

Not all talents follow the same theme though, there are some more varied ones as well:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/misc-talents.png){: .align-center}

## When Is This Releasing?

Historically v0.X.0 updates take a long time. v0.7.0 and v0.8.0 both took around six months, as I was implementing huge gameplay changes all in one big update. [I'm changing my design strategy though](/blog/coming-soon-to-shattered-better-bosses.html#changes-to-development-philosophy), and so am releasing the new talent system one tier at a time. This does mean v0.9.0 isn't as massive as v0.7.0 or v0.8.0, but it also means it gets released much faster!

[![](/assets/images/SHPD-icon.png){: .align-left}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) So with that in mind, v0.9.0 is going to beta ... right now! And I plan to release to everyone at the end of September! [If you're a Google Play user, you can opt into betas here](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon). [You can also get the latest release of the game (including betas), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)

## Anything Else?

While talents take center-stage, there are some other significant additions and changes coming in v0.9.0 too.

With these new talents and the fifth equip slot from v0.8.2 the game is getting a bit easier, so I'm adding a new challenge to keep things interesting for veteran players. The new challenge is called **Hostile Champions**, and focuses on amping up the danger of the game's enemies. Each regular enemy has a chance to spawn with a special champion buff that can increase their stats or provide other effects. There are six champion types, which should make for some nice variety.

There are a bunch of smaller adjustments and improvements too:
 - I've made a few adjustments to some existing challenges to reduce the number of items they remove from the game, without substantially changing their difficulty.
 - There's now a little health total in the main UI.
 - The badges screen now shows which badges the player is missing.
 - Based on feedback, I've made hero unlocking a bit easier.
 - There's another load of tiny tweaks and bugfixes as well, I'm homing in on less than 1 crash every 10,000 game sessions.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/future-tiers.png){: .align-left}
Finally, though only the first tier of talents is coming in v0.9.0, I'm already getting to work on designing later tiers. I'm not going to spoil things just yet, but expect some more complex talents which won't be restricted to earlygame power. In particular I'm very excited for how talents are going to tie in to some other hero progression mechanics...

---

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) If you like this update, please consider making a supporter purchase on [Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon), or supporting me on [Patreon](https://www.patreon.com/ShatteredPixel)! Patrons get weekly mini-blogs, and can vote in polls about content direction. Patrons have known about hero talents for about the last two months, and are the reason the new challenge is focusing on enemy variety! Over the next few months they'll be the first to hear about how I'm expanding on the talent system.

---

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/iym060/)