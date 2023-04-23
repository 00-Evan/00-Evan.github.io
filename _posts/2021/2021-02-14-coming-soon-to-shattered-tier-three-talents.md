---
title: "Coming Soon to Shattered: Tier Three Talents!"
excerpt: "v0.9.2 is just about ready for primetime now, and I've for a bunch of details to share about it! The most significant addition is of course tier three talents, but there are some significant changes to existing content as well."

header:
  image: /assets/images/2021/2021-02-14/header.png
  teaser: /assets/images/2021/2021-02-14/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: TALENT"]
---

Hey folks, happy Valentine's Day! I don't have flowers or chocolate for you, but I do have a Shattered update!

Apologies for the delay in this post, I originally promised it at the end of January but things ended up taking longer than expected. v0.9.2 is just about ready for primetime now, and I've for a bunch of details to share about it! The most significant addition is of course tier three talents, but there are some significant changes to existing content that I'd like to cover first:

## Existing Content Changes

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tengu.png){: .align-left}
v0.9.1 bumped winrates up a decent bit, and v0.9.2 will only continue that trend. So, I've decided to **ramp up the game's difficulty to compensate for the player's increased power**. I'm doing this by tuning up several of the game's less lethal enemies, so that they are a bit more likely to bring your run to an end. Most of these buffs are focused toward lategame enemies, and I'm not touching enemies that are already strong or frustrating.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/rogue.png){: .align-left}
I'm also making a more specific change to **the Rogue**, who is the best performing class in the game as of v0.9.1. In particular the rogue excels at being able to just ignore encounters thanks to his on-demand invisibility. I don't want to remove this entirely of course, but forcing him to take a few more fights should help bring his winrate back into line. With that in mind I'm reducing his turns of invisibility per cloak charge to 4 from 5.

As always, I intend to keep an eye on game balance and will make other adjustments as needed when the dust settles from v0.9.2.

---

With tier three talents affecting levels 13-20, v0.9.2 is also the perfect opportunity to make some subclass adjustments. While every subclass is getting at least a few changes, the two most significant are the Gladiator and the Freerunner:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gladiator.png){: .align-left}
Back in July 2020 **the Gladiator** won a [patreon poll](https://www.patreon.com/posts/39005311) over which subclass should receive a rework in the future. People generally disliked how all or nothing the combo mechanics felt, and how that led to a majority of gladiator runs relying on low combo moves like clobber. To address this, I've made combo significantly easier to build and have redesigned several combo moves around this. There should be more opportunity for interesting combo sequences, and you won't need a ring of accuracy to pull them off!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/freerunner.png){: .align-left}
I'm also making some changes to **the Freerunner** because he is hugely less popular than the Assassin, likely due to how little the player can interact with his mechanics. When [I initially reworked him](https://shatteredpixel.com/blog/coming-soon-to-shattered-the-rogue-rework.html#the-freerunner) I tried to make the Freerunner's power more engaging, but clearly I didn't go far enough in this direction. So, I'm keeping the momentum mechanic but the player now needs to activate the momentum to start 'freerunning' and gain bonuses to speed and evasion. This boost is temporary, and there's a cooldown before freerunning again. My hope is that this will make the freerunner feel more powerful and interactive.

## Tier Three Talents!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/talent.png){: .align-left}
Tier three talents are a bit different from the talents in the lower tiers. Tier 1 and 2 talents are designed around encouraging the player to spread their points a bit, but by tier 3 I'm expecting the player to have a build in mind. Because of this each T3 talent accepts up to 3 talent points, and I'm balancing them to not discourage putting multiple points into one talent. These talents are also tied to subclass as well as class! Tier 3 will have 2 class-based talents and 3 subclass-based talents. All of this should create a talent tier that encourages specialization that's geared toward the players current run.

Some T3 talents are mainly meant to reposition subclass powers that used to be innate. I'm doing this more to the subclasses that are currently performing best, and where I think an innate power could be fun if it were made stronger via spending talent points:

- **Cleave** is now an automatic power instead of a finisher move, which should help the Gladiator preserve combo between fights.
- **Soul Eater** locks hunger restoration behind a talent for the Warlock, but adds a neat on-kill effect to it.
- **Assassin's Reach**, when upgraded, lets the Assassin blink distances toward enemies even at very low prep charge.
- **Durable Tips** gives a dart-wielding Warden the option to more heavily invest in tipped dart gameplay.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/talents1.png){: .align-center}

Of course, other T3 talents offer new subclass effects entirely. For each of these I've tried to use the talent to open up new gameplay and synergy options for subclasses:

- **Enraged Catalyst** opens up some enchantment synergy potential for the Berserker, which was previously only available to the Gladiator.
- **Mystical Charge** gives the Battlemage options for artifact charging synergy, in addition to his obvious synergy with wands.
- **Projectile Momentum** gives the Freerunner a potential reason to invest in thrown weapons, instead of all that incentive belonging to the huntress.
- **Shared Enchantment** allows the Sniper to proc enchantments on her throwing weapons, which opens up new gameplay options for them.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/talents2.png){: .align-center}

And the base classes are getting a few talents too! Here are four of the more interesting ones, each opening up new gameplay/item interaction that could be useful for either subclass:

- **Hold Fast** gives the Warrior a bit of position-based gameplay, and rewards him with his favorite: more durability.
- **Ally Warp** gives some new positioning options to an ally-focused Mage build. Even at short ranges this is surprisingly useful.
- **Lightweight Cloak** finally detaches the Rogue from his cloak a bit. He can choose to use it unequipped, but at a big penalty.
- **Seer Shot** lets the Huntress gain vision on a specific location, perfect for seeing through grass or beyond your vision range.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/talents3.png){: .align-center}

In total there are 32 talents being added in this update, substantially more than the 20 added in 0.9.1 and the 16 in 0.9.0. After this we've just got the fourth tier left!

[![](/assets/images/icons/SHPD.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) I'm planning to fully release v0.9.2 in about a week, but you can play it in beta right now! [If you're a Google Play user, you can opt into betas here](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon). [You can also get the latest release of the game (including betas), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy ShatteredPD and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, a monthly Q&A livestream, and also help determine content direction through community polls!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/lk19mp/)