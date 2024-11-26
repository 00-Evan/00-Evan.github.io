---
title: "Coming Soon to Shattered: A Sixth Hero!"
excerpt: "Hey Dungeoneers! Progress has been made on the next major update to Shattered Pixel Dungeon, and it's finally time for me to start showing some things off! v3.0.0 will feature the game's second new hero: The Cleric! This blog will go over some of my design thoughts and early implementation work on this new hero."

header:
  image: /assets/images/2024/2024-11-26/header.png
  teaser: /assets/images/2024/2024-11-26/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#62  = tome of mastery sprite in v0.9.0+
#263 = holy tome sprite in v3.0.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 62", "SHPD_ICON_v803: ITEM: 263"]
---

Hey Dungeoneers! Progress has been made on the next major update to Shattered Pixel Dungeon, and it's finally time for me to start showing some things off!

v3.0.0 will feature the game's second new hero: **The Cleric!** This blog will go over some of my design thoughts and early implementation work on this new hero.

## The Sixth Hero

Two years ago, when I started work on the Duelist, I talked about how I wanted six heroes: two fighters <u>(Warrior & Duelist)</u>, two agile tricksters <u>(Rogue & Huntress)</u>, and two magic users <u>(Mage & Cleric)</u>. You can also look at this in terms of game mechanics: two simpler equipment focused heroes <u>(Warrior & Mage)</u>, two environment focused heroes <u>(Rogue & Huntress)</u>, and now two ability focused heroes <u>(Duelist & Cleric)</u>.

So what would an ability focused magic user looks like? The Duelist's ability focus took the form of a special attack being given to every melee weapon in the game. For the Cleric I'm taking a bit of a different approach, the Cleric's abilities tie into the talent system!

The Cleric will posses a holy tome artifact which they can use to cast a variety of spells that mainly focus on defense and utility. The Cleric unlocks and upgrades spells via the talent system!

Here's an early low-res peek at their splash art:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/cleric-tease.jpg){: .align-center .rounded-large}

## Divine Magic!

<u>(Note that the visuals below are a work in progress and subject to change)</u>

Currently talents are all passive or triggered effects because I didn't want them to warp Shattered's gameplay too much by being too complicated or powerful. In a way the Cleric is an exploration of the inverse approach, with more powerful talents that are active abilities.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/base-cleric.png){: .align-center }

The Cleric's holy tome artifact makes this possible, as even though most of their talents are now stronger player-triggered effects, they're all accessed from a single place in the UI, and all share a charge system. Scrolls of upgrade will still be the biggest source of power for the Cleric, of course, but expect talents to play a much bigger role for the Cleric than other heroes.

So what sort of spells can the Cleric actually cast using their tome? Firstly, the Cleric starts with three innate spells:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/base-spells.png){: .align-center }

- **Guiding Light** is a basic ranged attack option that deals a little damage and guarantees the next physical attack on its target will hit.
- **Holy Weapon** is an offensive buff that's best early on when you have no weapon enchantment. This spell temporarily replaces the weapon's enchantment with a damage boost.
- **Holy Ward** is Holy Weapon's defensive counterpart, adding a temporary glyph that increases damage blocking.

Here's a little GIF showing off those three spells:
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/innate-spells.gif){: .align-center .rounded-large }

All the other base Cleric spells are tied to talents. Most Cleric talents let you cast a new spell at +1, and make the spell more potent at +2. Here's a few examples:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/more-spells.png){: .align-center }

- **Detect Curse** is a T1 talent/spell that acts as the Cleric's talent option to help with identification. For a fairly hefty charge cost, the Cleric is able to tell whether an unidentified item is cursed or not.
- **Shield of Light** is a T1 talent/spell that is a great defensive panic button. For a short duration, the Cleric gains a significant armor bonus against a single target, and the spell is cast instantly!
- **Sunray** is a T2 talent/spell that gives the Cleric a stronger ranged option. The spell deals a bit more damage than guiding light, and blinds the target for a few turns. Casting the spell twice in a row will upgrade the blind to a stun, but this can only be done once per enemy.
- **Divine Sense** is a T2 talent/spell that gives the Cleric a visibility option. For a moderate charge cost the Cleric gains temporarily mind vision in a fairly wide (but not level-wide) area.

And here's a little GIF showing off sunray, the flashiest of these spells:
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sunray.gif){: .align-center .rounded-large }
 
Of course this just covers some of the Cleric's powers up to level 12. It's looking like there will be about 30 Cleric spells in total. Some of these are tied to the base class like the ones above, but others are tied into things like subclasses...

## Subclass Designs

I'm currently working towards Cleric subclass choice being about choosing a set of abilities/spells that each synergize with different classes of items.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/priest.png){: .align-left .rounded}
**The Priest** will focus more heavily on direct spell power and synergy with more magical items like wands and artifacts. Their abilities will likely not do much for weapons and armor or attacking in melee range. Experienced players tend to prefer more positional gameplay and use of wands, so the priest is likely to be the more popular choice for them. 
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/paladin.png){: .align-left .rounded}
**The Paladin** will, by contrast, more heavily focus on weapons and armor synergy over raw spell power. Somewhat like the berserker, I expect the Paladin would lean more toward defense than offense. The Paladin will probably be simpler to play due to their reliance on simpler equipment, and so they'll probably be the more popular subclass overall.
</div>

## Beta When?

Unfortunately the Cleric isn't quite playable in their current state. I want to at least have the base class, one subclass, and one armor ability fully implemented before starting the beta.

Things might be a little rough, but I would like to try and push for a beta release of v3.0 around mid to late December, just before the holiday season. That'll give everyone a chance to try the Cleric out and for me to gather feedback to start to push for a release in the new year.

...Of course, I do also release Alphas on [![](/assets/images/icons/patreon.png){: .rounded .text-inline}Patreon](https://www.patreon.com/ShatteredPixel) a bit before betas go out, and am less concerned about the Cleric not being fully playable there. I'm not able to commit to an exact timeframe, but I expect Patreon folks will be getting Alpha access sometime this week...

<u>Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!</u>

In the meantime, if you'd like more frequent incremental updates on Shattered's development, you can subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter), or follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)!

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/bluesky.png){: .align-left .rounded}](https://bsky.app/profile/shatteredpixel.com) [I've also now got an account on Bluesky!](https://bsky.app/profile/shatteredpixel.com) While I still prefer Mastodon, any platform is better than Twitter at this point, and if the majority of people want to migrate there I'm happy to post there as well. Bluesky will get the same posts I send to Mastodon or the Newsletter.
</div>
---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/22466145), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/4638240281918974827)!