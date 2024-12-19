---
title: "Coming Soon to Shattered: The Cleric!"
excerpt: "Hey Dungeoneers, v3.0.0 and the Cleric are finally ready for beta! In this blog post I'm going to share more details about the Cleric! Just as with the Duelist, I'm releasing the Cleric's beta a little early. There's still one subclass and two armor abilities to implement before the Cleric is content-complete and ready for release."

header:
  image: /assets/images/2024/2024-12-19/header.jpg
  teaser: /assets/images/2024/2024-12-19/header.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#62  = tome of mastery sprite in v0.9.0+
#263 = holy tome sprite in v3.0.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 62", "SHPD_ICON_v803: ITEM: 263"]
---

Hey Dungeoneers, v3.0.0 and the Cleric are finally ready for beta!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v3.0.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via their beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop
</div>

In this blog post I'm going to share more details about the Cleric! Just as with the Duelist, I'm releasing the Cleric's beta a little early. There's still one subclass and two armor abilities to implement before the Cleric is content-complete and ready for release.

<b><u>Note that visuals and specific balancing are still a work in progress. Details may change significantly before full release.</u></b>

## Introducing the Cleric!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/cleric.jpg){: .align-center .rounded-large}

I went over a lot of the Cleric's base class features in the [last blog I wrote](/blog/coming-soon-to-shattered-a-sixth-hero.html). As a quick recap, the Cleric is an ability-focused spellcaster who gains access to a variety of supportive spells through the talent system! They cast these spells using charges from their holy tome artifact, and the variety of spells they can access makes them very flexible. I already shared several T1 and T2 spells last time, but here's a couple more, with animated GIFs!

**Recall Inscription** lets you spend tome charges to repeat the effect of the last runestone or scroll you used. There are almost 40 different items you can duplicate, though some are more expensive than others.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/recall-glyph.gif){: .align-center .rounded-large }

**Bless** increases accuracy, evasion, and shielding when the Cleric uses it on themselves. When used on allies it offers a longer buff and healing instead!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/bless.gif){: .align-center .rounded-large }

## Subclasses

Each of the Cleric's subclasses include a new innate spell, a buff to some starter spells, and three additional spells that are learned via talents. As usual both subclasses also get two shared talents, one of which is a spell as well.

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/priest.png){: .align-left}
**The Priest** is all about magical ranged combat. All of their spells work from a distance, and they gain a buff to **Guiding Light**, which lets them cast it for free once every 100 turns, and trigger the resulting illuminated debuff using allies or magical items. When triggered in this way, Illuminated deals bonus magic damage.
</div>

Probably the two flashiest spells the Priest gets access to are **Holy Lance** and **Hallowed Ground**. Holy Lance is a devastating ranged spell that can absolutely obliterate a single target, but comes with a hefty charge cost and cooldown.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/holy-lance.gif){: .align-center .rounded-large }

Hallowed Ground, meanwhile, is a much more strategic spell that creates advantageous 'hallowed' terrain for 20 turns. This spreads grass, lightly heals allies, and impedes enemy movement.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/hallowed-ground.gif){: .align-center .rounded-large }

There's also the innate spell **Radiance** that momentarily stuns all enemies and applies illuminate to them, and the very tactical **Mnemonic Prayer** spell. Mnemonic prayer extends buff/debuff duration on allies/enemies, including re-applying illumate! I'm very interested to see people's creative uses of Mnemonic Prayer in particular, it interacts with almost every buff and debuff in the game.

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/paladin.png){: .align-left}
**The Paladin** is a simpler subclass that's all about close combat. All of their spells are closer-ranged, and they gain buffs to **Holy Weapon** and **Holy Ward**, increasing their effectiveness and allowing them to work with existing enchantments and glyphs.
</div>

Unfortunately I haven't implemented the Paladin yet, and so don't have anything to show you, but here are some spell designs I'm pretty solid on:

- **Smite** is a fantasy Paladin staple, and will be the Paladin's innate spell. I expect it to be a fairly straightforward physical attack buff, granting the Paladin a guaranteed hit, and probably some mix of extra damage and enchantment power.
- **Lay on Hands** is another Paladin classic, and will probably be the Cleric's only 100% direct healing spell in the game. Lay on Hands will grant a nice chunk of shielding if the Paladin uses it on themselves, or healing if it's used on an adjacent ally.
- **Cleanse** is actually the spell that's shared between both subclasses, so Priest gets it too. It's a useful defensive spell that removes debuffs from the Cleric and allies, applies shielding, and can even grant brief debuff immunity.

## Armor Abilities

I'm going to be a bit lighter on info here to avoid lategame spoilers, and as two of the abilities aren't implemented yet. Just like with subclasses, each armor ability has three unique spells that are learned and upgraded via talents.

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ascended-form.png){: .align-left}
**Ascended Form** causes the Cleric to assume a glowing radiant form for 10 turns. In this form they gain +2 attack range, access to new spells, and shielding for every holy tome charge they consume. This ability and its associated talent spells are expensive, but you can always just plan around benefiting from the extra reach or bonus shielding instead.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trinity.png){: .align-left}
**Trinity** (not yet implemented) is unique in that rather than being a single armor ability, it's a collection of three individual talent spells that each cost both tome and armor charges! To go along with the themeing here, I'm considering have the spells work with weapons/armor (body), wands (mind), and rings/artifacts (soul).
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/power-of-many.png){: .align-left}
**Power of Many** (not yet implemented) is a more collaborative version of ascended form. The Cleric either produces an ally, or empowers an existing one. This ability has three talent spells that are cast from this empowered ally instead of the Cleric themselves.
</div>

## Conclusion & Release Plans

The Cleric is shaping up to be the most complex and strategically flexible hero in the game, and I'm very excited for people to start playing with them. I expect they'll be a treat for experienced players in particular, who are going to have quite a few options available via all the different spells. Please let me know what you think of the Cleric in v3.0.0's beta!

I expect the beta to last a fair bit longer than usual, both due to the work still needing to be done, and the upcoming holidays. I'm going to be taking things easy for the next week or two, so expect for the Cleric to start getting filled in during January, and for v3.0.0 to start getting ready for release around late January or early February.

Finally, some of you may be wondering about the in-game visual improvements I shared in the [10th anniversary blog post](/blog/ten-years-of-shattered-pixel-dungeon.html#new-pixel-art). I'm afraid there's nothing new to share there yet, but I might have a couple other visual improvements cooking for v3.0 instead...

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/title.gif){: .align-center .rounded-large }

<u>Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!</u>

---

I'll be a little quiet over the holidays, but if you'd like more frequent incremental updates on Shattered's development (including further work on the Cleric!), you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/23320823), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/595135813103128726)!