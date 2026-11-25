---
title: "Shattered Pixel Dungeon v4.0.3!"
excerpt: "Hey Rat Punchers! v4.0.3 doesn't have any new game content (hence why it's not v4.1.0), but is still a pretty big patch, and so deserves a little announcement post!"
header:
  image: /assets/images/2026/2026-11-25/header.jpg
  teaser: /assets/images/2026/2026-11-25/header-small.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon for display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: CHANGES"]
---

Hey Rat Punchers!

v4.0.3 doesn't have any new game content (hence why it's not v4.1.0), but is still a pretty big patch, and so deserves a little announcement post!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>Shattered Pixel Dungeon v4.0.3 has been released!</u></b> You can get it:
<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) for Android.
<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) for iOS.
<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) or [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon) for Computers.
<br>- On [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon) or [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Computers.
</div>

Both for this big patch, and for Black Friday, Shattered is 50% off on [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/GOG.png){: .rounded .text-inline}GOG](https://www.gog.com/en/game/shattered_pixel_dungeon), and [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon) for the next few days!

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/54845657), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/564800414277501047)!

## What's new in v4.0.3

v4.0.3 includes three pretty significant new features to the game, and while they don't affect gameplay itself, they should be pretty important for the people who they're targeted at:

Firstly, Shattered now supports a new language: **Arabic!** Arabic has long been requested as a language for Shattered, but as it's read from right to left actually getting it implemented into the game was something I always considered infeasible. However, after a recent round of investigating (with the help of an Arabic translator) it ended up being more realistic than I thought! There are probably still a bunch of little things to fix, but Shattered now (mostly) works with a RTL language for the first time!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/arabic.png){: .align-center .rounded-large}

Secondly, Shattered's **brightness slider has been overhauled**, and now increases (or decreases) brightness/contrast for the entire game in addition to lightening the fog of war. Previously brightness only adjusted the opacity of the fog of war, which was a decision mainly made to improve performance on old devices about 10 years ago. A lot of time has passed, and even super old phones nowadays have no problem with doing some more color math on each pixel, so the brightness slider now applies to the whole game!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/brightness.gif){: .align-center .rounded-large}

Lastly, The OSS Android version of Shattered now has a **local backup & restore system**! It was previously impossible for de-googled Android users to back up or migrate save data, as all Android OS backup/restore features are proprietary these days. It's now possible for those users to create a local backup file and transfer their rankings/badges/journal between devices. All other versions of Shattered already have accessible save data (e.g. desktop) or existing backup solutions (e.g. Google Play, AppStore, Steam).

## Other Changes

While those three are the big headline features, there's also a bunch of balance changes, smaller misc. adjustments, and bugfixes. Here are all of the smaller changes:

<ul>
<li><details markdown="1"><summary>Many Balance Changes</summary><blockquote markdown="1">
**Imp Quest** reward scaling is now more generous. The ability to take out higher upgraded items and unlocking the imp shop now both occur at lower levels of exploration. Taking out any item you want still requires defeating the boss however.

**Paralysis resist** now always guarantees that a character will get to take 1 action before being able to be paralysed again.

**Poison** has received a couple tweaks, mainly aimed at lightly nerfing venomous:
- **Poison** debuff now deals 1 damage for the last 3 turns of duration, up from the last 2. This means it now deals 1 dmg as many times as every other damage number.
- Various non-venomous poison sources adjusted to compensate (in general they deal 1 more total dmg and last 1 more turn).
- Poison effect from mystery meat nerfed, no longer deals absurd dmg at high max HP.

**Misc:**
- **Force cube** base dmg reverted to 10-25 from 10-30, but now deals 1/2 dmg to allies and self
- **Holy lance** charge cost reduced to 3 from 4
- **Exotic Crystals** now give a 0/33/67/100% chance (based on level) to drop an extra potion or scroll each floor.

**Rings:**
- **Force** soft STR scaling cap up to 20 from 18, weapon bonus dmg now applies to thrown weapons, and dmg bonus to weapons can now scale from 1-1 to 1-3 based on weapon tier. Bonus dmg to weapons now also respects weapon augment.
- **Sharpshooting** durability boost per level up to 25% from 20%
- **Might** max HP boost level level up to 5% from 3.5%

**Artifacts:**
- **Sandals of nature** now require 3/5/7 seeds to level up, down from 3/6/9
- **Master Thieve's Armband** now also weakens an enemy if they are surprised
- **Talisman of foresight** now more responsively warns you about traps, scrying now charges faster and occurs in a larger area. levelling up is slightly faster but less exp is gained from scanning empty spaces & traps.

**Champion Enemies:**
- **Giant** champion % dmg reduced down to 75% from 80%
- **Growing** champions now power up more slowly over time, most noticeable after 2x power

**Enchantments & Glyphs:**
- **Crystal** enchantment no longer destroys the weapon when it breaks, only the enchantment is lost
- **Viscocity** base dmg deferred up to 25% from 17%
- **Flow** speed boost now persists for an extra 0.25 turns per level, but speed boost is down to 2x, from 2x + 0.5x per lvl
- **Affection** base proc chance up to 20% from 15% and scaling increased
</blockquote></details></li>
<li><details markdown="1"><summary>Misc. Changes</summary><blockquote markdown="1">
- Large enemies should no longer stand completely still when being attacked around corners
- Spinner webs are no longer impassable for large characters (they are still rooted)
- Artifacts are no longer usable in the dwarf vault, to prevent exploits
- Enemies can no longer randomly wander into shops
- Summoning traps and multiplicity curse are no longer capable of spawning champion enemies
- Unstable brew no longer has a chance to trigger purity effect when thrown
- Recycle spell item now re-shows its item selector after each use
- Improved occlusion shadowing visuals around doorways
- hotkeys for selecting a particular bag now open the inventory UI if it was closed
- Slightly improved the visuals when the greater elemental spawns and swaps forms
- Removed support for iOS devices with A8- processors
- Removed 10 year old rendering optimizations that are no longer relevant
- Added 'pressing' vfx/sfx to several buttons and button-like objects that were lacking them
- Improved wording on potion of purity and parts of Imp quest
- Updated various internal code libraries
</blockquote></details></li>
<li><details markdown="1"><summary>Bugfixes</summary><blockquote markdown="1">
Fixed the following bugs:
**Caused by v4.0.1/v4.0.2:** 
- Crystal enchantment never breaking in most cases
- Standard rooms with stronger enemies still rarely connecting to the vault entrance

**Caused by v4.0.0:**
- Cursed wand transmutation effect applying to spirit bow or mage's staff when triggered via wondrous curse
- Rare game freezes in crystal caves quest
- Rare cases where the hero could teleport into walls
- Unstable enchant never triggering crystal
- UI not properly updating if enemies become visible because of upgrading a talent

**Existed Prior to v4.0:**
- Scroll of Teleportation placing the hero right next to their previous location in some cases
- Incorrect interactions between fury and time freeze or lethal momentum
- Specific errors involving Duelist's challenge ability and moving between floors
- Ripper demons not swapping targets in lots of cases where they should
- Beaming ray's distance check incorrectly interacting with stasis
- Rare quirks with hiding mimic sprites
- Rare cases of skeletons summoned by necromancers becoming visually desynced
- Very rare cases where Duelist's challenge ability wouldn't apply to all enemies
- Golems being able to teleport large characters into enclosed spaces
- Beacon of returning not blinking when it should
- Temporary strength boosts not always showing in game in progress summaries
- Various minor visual and textual errors
- Various rare crash bugs
</blockquote></details></li>
</ul>

## What about v4.1?

With v4.0.3 ending up being quite a bit bigger than I expected (plus some other obligations and troubles making it a bit hard to focus on work in the last couple months), I expect v4.1 is probably not going to be releasing this year. I still plan for it to be a relatively small update focused on adding some new items though, and I DO want to get started on it before the holidays. Hopefully I'll have another blog post with more details on v4.1 before the end of December.

If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, an exclusive discord, monthly content polls, physical loyalty rewards, and early alpha access to updates!
</div>