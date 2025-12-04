---
title: "Shattered Pixel Dungeon v3.3.0!"
excerpt: "Hey Dungeoneers, Shattered v3.3.0 has been released! v3.3 includes a tester area for the upcoming overhaul to the city quest, new items, and a bunch of smaller tweaks and improvements."
header:
  image: /assets/images/2025/2025-12-04/header.png
  teaser: /assets/images/2025/2025-12-04/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon for display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: CHANGES"]
---

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>Hey Dungeoneers, Shattered v3.3.0 has been released!</u></b> You can get it:
<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) for Android.
<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) for iOS.
<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) or [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon) for Computers.
<br>- On [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon) or [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Computers.
</div>

Along with this update, Shattered is [![](/assets/images/icons/steam.png){: .rounded .text-inline}45% off on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) for the next week!

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/39719486), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/693120661167636505)!

## What's new in v3.3.0

v3.3 includes a tester area for the upcoming overhaul to the city quest, new items, and a bunch of smaller tweaks and improvements.

I talked about this update in one previous blog post:
- [Coming Soon to Shattered: Imp Quest Tester Area!](https://shatteredpixel.com/blog/coming-soon-to-shattered-imp-quest-tester-area.html)

Here's the full changelog for v3.3.0! Click or tap on each entry to read more. Note that this changelog will become slightly outdated as patches are released and dev commentary is added, so check the changes screen in-game for the most up to date version.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new.png){: .align-center}
**New Content**

<ul>
<li><details markdown="1"><summary>Dev Commentary</summary><blockquote markdown="1">
- Released December 4th, 2025
- 122 days after v3.2.0 (66 days after v3.2.5)

Dev commentary will be added here in the future.
</blockquote></details></li>
<li><details markdown="1"><summary>Initial Imp Quest Tester Area</summary><blockquote markdown="1">
**While v3.3 does not include the new quest, it does include a tester area for it, similar to the tester area that existed before the new caves quest!**

This tester area can be accessed from a new room that spawns in the city, this room also contains the Imp who gives his old quest. Simply walk onto the large vault entrance to be offered a teleport into the new area.

Currently the new area has fully functional storage of your current items, very basic level generation, and no quest hazards. **I intend to continue iterating on and improving this tester area during the release of v3.3 and in followup patches. The quest itself isn't coming in a patch however.**
</blockquote></details></li>
<li><details markdown="1"><summary>New Artifact and Trinket!</summary><blockquote markdown="1">
**Two new equipment items have been added to the game!**

The **Skeleton Key** is a new Artifact that grants the player new ways to control the dungeon environment! It can be used to open almost any lock in the dungeon, lock doors that weren't previously locked, and create temporary magical walls! The existing skeleton key item (dropped by Goo) has been renamed to 'worn key',

The **Cracked Spyglass** is a new Trinket that's a sort of milder version of the Mimic's Tooth. It generates extra items in the dungeon, but those items are very hard to see, so keep your eyes peeled!
</blockquote></details></li>
<li><details markdown="1"><summary>Randomize Options</summary><blockquote markdown="1">
**It's now possible to play runs with randomly selected game options!**

This includes a random class and challenges (optionally) in hero select, and random talents, subclass, and armor ability within the game! This add some replayability for experienced players, or just another option for people who aren't sure about what they want.

There's also a **new badge** to earn! To get it you need to win a run with a random hero, talents, subclass, and armor ability.
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/changes.png){: .align-center}
**Changes**

<ul>
<li><details markdown="1"><summary>Hostile Champions and Albino Rats</summary><blockquote markdown="1">
I'm making a few early game tweaks, mainly meant at smoothing out difficulty spikes caused by hostile champions and floor 1 albino rats. In exchange though, the hostile champs challenge is getting a bit harsher later in the game.

**Hostile Champions:**
- The following enemies can no longer spawn as champions: Crabs on F3, Thieves on F4, Guards on F7, and Bats on F9.
- Champion enemy spawn rate now scales up to 1/6 as dungeon depth increases, instead of always being 1/8.

**Albino Rats:**
- HP down to 12 from 15
- Bleed damage now always starts at 2-3 if the rat did damage, instead of being based on damage dealt. This means it no longer benefits excessively from bonus damage effects.
</blockquote></details></li>
<li><details markdown="1"><summary>Chalice of Blood Upgrading</summary><blockquote markdown="1">
The Chalice of Blood has received significant changes to how its upgrade mechanics work. Previously the player was given no direct info about the damage it would deal when upgraded, which led to most people just looking the numbers up on the internet.

The player is now told the damage the chalice will deal, but the chalice deals a range of ~83% to ~117% of its current static damage. The player is told the exact % chance this damage has of killing them before damage-reducing effects are considered.

Additionally, damage from the chalice is now reduced by ALL damage-reducing effects, instead of just ones that apply to physical damage.
</blockquote></details></li>
<li><details markdown="1"><summary>~20 Misc. Changes</summary><blockquote markdown="1">
**Highlights:**
- The 4th trinket option is no longer hidden until selected.
- Damage-dealing Cleric spells (holy lance, most notably) now disqualify for the "No Weapons in His Presence" badge.
- Hitting an enemy no longer resets Gladiator's combo time down to 5 if it was above 5 already.
- Hero movespeed is now calculated based on the terrain the hero is moving toward, not moving from.

**Levels:**
- Slightly tweaked gold generation in the caves quest. The player now always must find 1/2 secret rooms to reach 40 gold. This eliminates cases where the player had to find 1/1 or 2/2 secret rooms, which could be excessively frustrating.
- Gardens and magic well rooms are now locked and require an iron key.
- Large or giant sewer pipe rooms with only two doors now lay themselves out with a 3rd phantom door to ensure they aren't overly tiny.

**Characters:**
- Tengu now has a one-turn delay before he starts attacking
- Warrior's shielding buff now has a dedicated icon and description if cooldown is negative
- DM-200s and Golems are now more willing to swap targets if they can't reach their current one
- Characters spawned due to an action occuring on a partial turn now have their time moved forward to the next whole turn

**Items:**
- Added vfx to movement-speed influencing glyphs to show when they are active
- Heavy Crossbow now more directly shows the damage it grants to darts
- Elixir of Honeyed Healing recipe cost down to 2 from 4, energy value down to 8 from 12

**Misc:**
- Removed support for runs in progress from prior to v2.5.4 (Oct. 2024)
- Added a warning when the player attempts to energize their trinket
- Adjusted ascension challenge text to make it more clear whether the player has killed any enemies so far
- Updated various internal code libraries
- Shattered's Windows version now requires Windows 10, up from 7
- Sharing gameplay data on iOS now requires iOS 15+, up from 12+
</blockquote></details></li>
<li><details markdown="1"><summary>~20 Bugfixes</summary><blockquote markdown="1">
Fixed the following bugs:

**Highlights:**
- Freezes caused by enemies dying to DOT effects while thrown weapons were attached to them
- Exploits that could result in certain Imp shop items being free
- Rare cases where thrown weapons would not disintegrate when they should

**Characters:**
- Cleric's holy ward not applying to damage from bone explosions or Chalice of Blood
- Characters being able to wander into the entryway of toxic gas rooms
- Monk not gaining energy back if she kills with an ability while at full energy
- Mimics being susceptible to surprise attacks after they surprise the hero
- DM-200s and Golems not switching from targets they can't reach
- DM-300 still sometimes using abilities right out of supercharge
- DM-300's gas shot dealing damage instantly in specific situations
- Demon Spawners not being recorded as alive in very specific cases

**Items:**
- Transmuting tipped darts destroying the original dart stack
- Unstable Spellbook not triggering Siren's Song effect properly if the hero is also under time freeze
- Charge count on Duelist's weapons being always set to 2 in rankings
- Spirit Form not properly working with ring of force

**Misc.:**
- Compass pointing to exit staying visible if exit becomes hidden
- Very rare cases where doors would not properly hide and then reveal in the tutorial
- Extremely rare cases where the game could hang while generating the wandmaker's quest
- Specific cases where Goo's pump up warning vfx could be in incorrect positions
- Very rare cases where tunnel rooms could generate tiny tunnels to nowhere
- Various minor errors with multi-touch and scrolling panes
- Various cases where translations did not fit in the UI and could be shrunken or repositioned
- Various minor visual and textual errors
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/buffs.png){: .align-center}
**Buffs**

<ul>
<li><details markdown="1"><summary>Thrown Weapon Talents</summary><blockquote markdown="1">
A lot more data has come in after v3.2 increased thrown weapon usage, and there's room to buff up some of the changed talents after that update:

- **Projectile Momentum** bonus damage nerf reverted, damage bonus up to 15/30/45% at +1/2/3, from 10/20/30% at +1/2/3

- **Durable Projectiles** nerf reverted, bonus durability up to +50%/+75% at +1/+2, from +33%/+50% at +1/+2
- **Point Blank Shot** Accuracy boost up to +25/50/75% at +1/2/3, from +20/40/60% at +1/2/3
</blockquote></details></li>
<li><details markdown="1"><summary>Thrown Weapon Buffs</summary><blockquote markdown="1">
Thrown weapons are mostly in a pretty good place balance-wise since the patches to v3.2, but I'm making two targeted buffs regardless:

- **Telekinetic Grab** is now cast instantly if the only items it picks up can be instantly collected (i.e. throwing clubs and throwing hammers)
- **Tomahawk** bleed now has its own damage range, instead of being directly tied to damage dealt. Bleed amount increased by ~20% on average.
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/nerfs.png){: .align-center}
**Nerfs**

<ul>
<li><details markdown="1"><summary>Bolas and Boomerangs</summary><blockquote markdown="1">
There are also a few targeted nerfs to specific thrown weapons:

**Bolas** continue to do really well despite their nerfs in v3.2. Clearly the cripple effect they have is almost worth it on its own, so I'm scaling back the damage further:
- **Bolas** base damage down to 4-9 from 6-9, damage scaling down to 0-2 from 1-2.

**Boomerangs** also continue to do extremely well, especially for the Huntress. I'm holding off on larger changes here for now, but in general it seems like the circle back effect is so strong because of how dependant thrown weapons can be on the telekinetic grab spell.
- **Boomerang** circle back delay increased to 5 turns from 4.
</blockquote></details></li>
</ul>

## What's coming next?

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/upcoming.png){: .align-center}

<ul>
<li><details markdown="1"><summary>Overview and ETA</summary><blockquote markdown="1">
The next major Shattered update will be v3.4 or v4.0 (I haven't decided on a version number yet) and will, finally, feature an overhaul to the Ambitious Imp quest in the metropolis!

While work has started on the new quest, I do still expect this update to take some time. You'll hear from me in patches to v3.3, and early in the new year with my usual year in review blog post. I expect I'll be able to give a more solid eta in one of those.

**Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don’t hear from me by the ETA, it means I’m still busy with the update!**
</blockquote></details></li>
<li><details markdown="1"><summary>Expanding Tester Area in Patches</summary><blockquote markdown="1">
Just like with v3.2, I expect that v3.3 is going to have a longer than usual patch cycle. I've purposefully designed the new quest tester area such that it can be iterated on and expanded in patches to v3.3. This lets me make relatively quick experiments relating to the layout and some of the hazards in the new quest area.

I don't think that the tester area will end up looking complete in v3.3 patches, but it's going to get a whole lost closer than it is currently.
</blockquote></details></li>
<li><details markdown="1"><summary>Imp Quest Overhaul</summary><blockquote markdown="1">
After v3.3 patches are done and the tester area is getting closer to finished, It'll be time to step back, take a bit longer, and eventually release the overhauled imp quest as primary content in the next update!

As mentioned before, the new quest will have you infiltrate a dwarven vault full of danger and treasure! It's going to be a new kind of challenge, as you won't be able to take your existing items with you, but I expect the reward will be well worth it!
</blockquote></details></li>
<li><details markdown="1"><summary>Other Changes</summary><blockquote markdown="1">
I expect the next update to be fairly light on smaller changes, as I want the focus to be on the new quest. There will surely be the usual amount of smaller tweaks and bug fixes though, and in particular I expect there will be at least a little balancing to follow up on the new items and item changes in v3.3.
</blockquote></details></li>
</ul>

If you're like more frequent incremental updates, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>
