---
title: "Shattered Pixel Dungeon v3.1.0!"
excerpt: "Hey Dungeoneers, Shattered v3.1.0 has been released! This update includes a mini Warrior Rework, new terrain/rooms, a new trinket, and a bunch of other smaller changes and additions!"
header:
  image: /assets/images/2025/2025-06-02/header.jpg
  teaser: /assets/images/2025/2025-06-02/header-small.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon for display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: CHANGES"]
---

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>Hey Dungeoneers, Shattered v3.1.0 has been released!</u></b> You can get it:
<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) for Android.
<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) for iOS.
<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) or [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon) for Computers.
<br>- On [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon) or [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Computers.
</div>

To celebrate v3.1.0's release, Shattered is also [![](/assets/images/icons/steam.png){: .rounded .text-inline}40% off on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) right now!

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline} Pixel Dungeon Lemmy Community](https://lemmy.world/post/30664094), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/games/1769170/announcements/detail/519714948911204583)!

## What's new in v3.1.0

v3.1 includes a mini Warrior Rework, new terrain/rooms, a new trinket, and a bunch of other smaller changes and additions!

I talked about this update in one previous blog post:
- [Coming Soon to Shattered: Warrior Mini Rework and More!](https://shatteredpixel.com/blog/coming-soon-to-shattered-warrior-mini-rework-and-more.html)

One notable new addition that I didn't share in that earlier post is a re-done splash art for the Warrior to go along with his gameplay mini rework! This new splash is once again done by [Aleksandar Komitov](https://akomitov.artstation.com/). The original Warrior splash was the first one Aleks did, and so this remake is the most significant of the hero splash art changes. Aleks was keen to make corrections to armor design and proportions to bring the splash up to his current standards.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/warrior.jpg){: .rounded-large .align-center}

Here's the full changelog for v3.1.0! Click or tap on each entry to read more. Note that this changelog will become slightly outdated as patches are released and dev commentary is added, so check the changes screen in-game for the most up to date version.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new.png){: .align-center}
**New Content**
<ul>
<li><details markdown="1"><summary>Dev Commentary</summary><blockquote markdown="1">
- Released June 2nd, 2025
- 95 days after v3.0.0

Dev commentary will be added here in the future
</blockquote></details></li>
<li><details markdown="1"><summary>Warrior Mini Rework</summary><blockquote markdown="1">
**The Warrior has had a mini overhaul to his broken seal ability, and new visuals for his splash art and broken seal!**

The seal's shielding now triggers in bursts with a cooldown, when the Warrior is below 50% HP. It should feel more impactful and interactive while still being easy to use for new players.

The Warrior's new splash art is once again done by Aleksandar Komitov. The original Warrior splash was the first one Aleks did, and so this remake is the most significant of the hero splash art changes. Aleks was keen to make corrections to armor design and proportions to bring the splash up to his current standards.

Here are the detailed changes to the broken seal shielding mechanics:
- Broken Seal shield no longer passively builds, it now triggers all at once just before the Warrior gets damaged to 50% health or lower.
- Max shield is now based on armor tier, scaling from 5-13 (max of 15 with iron will talent).
- This shielding does not decay, but ends shortly after combat
- This shielding has a 150 turn cooldown, unused shield refunds up to 50% cooldown.
- The broken seal can now be applied to known-uncursed armor.
- When swapping armor, the Warrior now gets a prompt to swap his seal too.

Various other Warrior mechanics have been adjusted to compensate for the seal changes:
- **Provoked Anger** talent now triggers when any shield buff breaks, and grants +3/+5 bonus damage, up from +2/+3.
- **Iron Will** talent unchanged, still grants 1 or 2 max shield.
- **Liquid Willpower** talent now grants regular barrier equal to 6.5%/10% of max HP, instead of recharging 50%/75% of max seal shield.
- **Lethal Defence** talent now reduces seal cooldown, instead of recharging seal shield.
- **Gladiator** will retain any active shielding from his broken seal as long as he has combo.
- **Berserker** enrage shield is now its own separate shielding buff, and has its own scaling separate from the seal's max shield.
</blockquote></details></li>
<li><details markdown="1"><summary>New Rooms and Terrain Types</summary><blockquote markdown="1">
This update includes an **expansion to the dungeon's standard rooms!**

- **New decorative terrain** has been added to each region, largely inspired by details from the region splash arts. 
- **5 new standard rooms** have been added that use these new terrain objects, one per region.
- **8 existing standard rooms** have been modified to use the new terrain objects.
- **10 new entrance/exit variants** of standard rooms have been added as well. two per region.
- **Boss Arenas** also use these new terrain types in a few places
- **Plain empty rooms** no longer spawn normally.
</blockquote></details></li>
<li><details markdown="1"><summary>Ferret Tuft</summary><blockquote markdown="1">
**A new trinket has been added to the game!**

The **Ferret Tuft** is a simpler evasion-boosting trinket with more of a cute aesthetic. It's a little reference to a favourite lime ferret.

Choosing and upgrading the trinket will cause all characters to gain evasion, including enemies! That might sound like a mixed bag, but keep in mind that there are lots of ways to counter enemy evasion.
</blockquote></details></li>
<li><details markdown="1"><summary>New Badges</summary><blockquote markdown="1">
v3.1 also includes **four new badges**, each themed around a specific challenge:

- **Safety Hazard** is a gold-tier badge that requires using terrain against enemies
- **So Many Colors** is a platinum-tier badge that requires having a bunch of buffs/debuffs at once
- **Pacifist Ascent** is a diamond-tier badge that require surviving an ascension without any enemy kills.
- **Taking the Mick** is a diamond-tier badge that requires defeating the final boss with a VERY high level pickaxe

I've also reduced the difficulty of the **Big Game Hunter** badge. It now requires discovering 10 types of rare enemies, down from all of them.
</blockquote></details></li>
<li><details markdown="1"><summary>New Rare Enemies</summary><blockquote markdown="1">
**Two new rare enemies** have been added to the sewers:

**Gnoll Exiles** are exceptionally strong, but also wary of combat. They won't attack unprovoked, so you can just let them pass, but maybe you'll be interested in the loot they carry...

**Hermit Crabs** are sturdy but slow crabs that use a broken barrel for extra support. They're a bit tough to fight, but much easier to run away from, and have a good chance to drop some armor for you.
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/changes.png){: .align-center}
**Changes**
<ul>
<li><details markdown="1"><summary>Exploration and Quest Score</summary><blockquote markdown="1">
I've made adjustments to how score is calculated to balance the difficulty of the various score categories a little better:

**Exploration Score** is no longer all-or-nothing for each floor. It is now based on how many rooms were not fully explored. For each floor, score is reduced to 50%/20%/0% for 1/2/3+ missed rooms. The criteria for whether something is 'fully explored' is unchanged.

**Quest Score** can now be reduced in a similar manner to boss score. Make sure to position well to avoid penalties! This reduction includes telegraphed attacks/effects (e.g. crystal spire, gnoll geomancer), and regular attacks that you should be able to always avoid (e.g. rot lashers, fetid rat's ooze). Cases where attacks are sometimes unavoidable (e.g. corpse dust wraiths, gnoll trickster) have some leeway before penalties apply.
</blockquote></details></li>
<li><details markdown="1"><summary>20+ Misc. Changes</summary><blockquote markdown="1">
**Highlights:**
- Various small color tweaks to health bars, inventory buttons, and flare vfx to improve the experience for colorblind players
- Custom notes for items can now be created or edited from the item's info window
- Hero renaming can now be done in the hero info window while a run is in progress
- All potions now refresh the duration of their specific effects. Previously the duration of some potion effects could stack on themselves
- Added discovery hints for all catalog entries
- Added landmark entries for lost backpack and beacon of returning

**Items:**
- Slightly reduced telekinetic grab's sale/energy value, so that it can't be used to effectively turn high-tier thrown weapons into energy
- Unidentified wands can now be imbued in the mage's staff
- Partially IDed items can now be used with the dried rose

**Characters:**
- Improved Tengu's AI, he can now switch targets if he is unable to attack the hero
- Defeating Dwarf King now cleanses the player of the degraded debuff

**Effects:**
- Smaller shorter-term shielding buffs are now consumed before larger longer-term ones
- The gravity chaos cursed wand effect now has its own debuff icon
- When using metamorph, food talents that grant the same type of recharging can now stack
- Improved VFX for activating or deactivating brawler's stance
- Guiding Light's spell icon is now brightened when it is free to cast

**Misc:**
- The inventory button gold indicator on mobile now shows when buying items
- Rooms with a chasm in the center must now be at least 3x3, up from 2x2
- Increased the minimum supported iOS version to 12, from 11
- Moved the notification position to the top-left on the Steam version. It should no longer obscure UI elements
</blockquote></details></li>
<li><details markdown="1"><summary>30+ Bugfixes</summary><blockquote markdown="1">
Fixed the following bugs:

**Highlights:**
- Thrown weapons gaining or losing more accuracy than intended based on enemy adjacency
- Shocking enchantment triggering its damage twice in many cases since v3.0
- Runs in progress older than 2 months showing 'NO TEXT FOUND'
- Allies not waking from magical sleep after it has healed them
- Desktop versions downloaded via github not properly notifying when updates are available

**Characters:**
- Swapping places with allies not being counted as movement for shuriken's instant attack
- Exploits where sheep could last forever if game was frequently saved/loaded
- Mirror images not benefitting from body form or holy weapon if the Cleric was unarmed
- Light Ally and Shadow Clone having very slightly more accuracy/evasion than the hero at base

**Effects:**
- Hallowed ground producing furrowed grass more often than intended in some cases
- Ascended form ending early if its shielding was reduced to 0
- Metamorphed cleanse clearing lost inventory debuff
- Metamorphed aggressive barrier using incorrect logic
- Lay on Hands sometimes applying 0 barrier to allies
- Death via the Cleric's life link not being recorded in rankings
- Targeting traps having very slightly less range than intended
- Duelist being able to stack invisibility using the sneak weapon ability
- Metamorphed holy intuition deleting armor in rare cases

**Items:**
- Players being able to take smith rewards multiple times in specific cases
- Stone glyph not considering some evasion/accuracy buffs
- Brimstone glyph not properly scaling past +50% glyph power
- Boomerangs disappearing if the game was closed during their circle back animation
- Crystal path rooms sometimes sorting items incorrectly when player had exotic crystals
- Cursed wand of warding not using autotargeting

**Misc:**
- Shattered locking to 60fps on 120hz iOS devices
- Custom notes not properly applying to specific rings, wands, & trinkets
- Paralysis vfx on enemies sometimes cancelling animations as it ends
- Rare cases of wonky display scaling on Linux systems
- Various minor visual & textual errors
- Various rare crash errors
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/buffs.png){: .align-center}
**Buffs**
<ul>
<li><details markdown="1"><summary>Cleric Buffs</summary><blockquote markdown="1">
Overall the Cleric is doing well following their initial release. Their winrate is low currently, but they are also very popular so I expect some of that is people still figuring them out. For the moment I'm focusing on multiple targeted buffs to specific Cleric mechanics that are weaker vs. others.

**Base class:**
- **Guiding light** base damage up to 2-8 from 2-6
- **Holy Weapon & Ward** are now cast instantly
- **Shield of Light** duration up to 5 from 4
- **Divine Sense** is now cast instantly

**Paladin:**
- **Lay on Hands** healing up to 15/20/25 from 10/15/20
- **Aura of Protection** dmg resist up to 20%/30%/40% from 15%/23%/30%

**Priest:**
- **Illuminate** bonus damage up to 5+lvl from lvl
- **Radiance** now triggers and applies illuminate
- **Holy Lance** cooldown down to 30 from 50
- **Hallowed Ground** heal up to 15 from 10
- **Hallowed Ground** root up to 2 turns from 1
- **Mnemonic Prayer** is now cast instantly

**Ascended Form:**
- **Divine Intervention** duration extension up to 3/4/5/6 from 1/2/3/4
- **Judgement** extra dmg increased to +33% per spell from 5-10 per spell

**Power of Many:**
- **Life Link** duration up to 10/13/17/20 from 6/8/10/12
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/nerfs.png){: .align-center}
**Nerfs**
<ul>
<li><details markdown="1"><summary>Cleric Nerfs</summary><blockquote markdown="1">
A few Cleric mechanics are standouts in terms of power though, so I am scaling some of those back:

- **Searing Light** dmg down to +3/+5 from +4/+6
- **Enlightening Meal** charge gain down to +0.67/+1 from +1/+1.5
- **Cleanse** is no longer cast instantly
- **Hallowed Ground** barrier now caps at 30
- **Flash** starting charge cost up to 2 from 1
- **Stasis** charge cost up to 2 from 1, but duration +50%
</blockquote></details></li>

</ul>

## What's coming next?

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/upcoming.png){: .align-center}

<ul>
<li><details markdown="1"><summary>Overview and ETA</summary><blockquote markdown="1">
The next major update to Shattered will be v3.2, which will include an overhaul to thrown weapons!

Due to deadlines relating to supporting old versions of Android, v3.2 has to release relatively quickly. Expect to hear more from me about it sometime probably toward mid or late July.

<u><b>Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!</b></u>
</blockquote></details></li>
<li><details markdown="1"><summary>Thrown Weapon Overhaul</summary><blockquote markdown="1">
The biggest content change I have planned for v3.2 is something I didn't originally plan for 2025, an overhaul to thrown weapons! I've settled on a design I like, and want v3.2 to be fairly quick, which is why this has taken priority for the moment.

The plan is to make thrown weapons behave a bit more like wands, by having them drop in 'sets' that have a fixed quantity, but which can be upgraded as a unit. This should make investing upgrades in thrown weapons much more appealing, as you'll no longer be limited to upgrading one at a time.
</blockquote></details></li>
<li><details markdown="1"><summary>Misc and Behind the Scenes Changes</summary><blockquote markdown="1">
As always, v3.2 will include some smaller misc. changes and balance tweaks, but I expect it will be lighter on them than usual as I'm working on a deadline in order to ensure old Android and Java users will still get v3.2.

If there's time, I would also like to make some internal changes in prep for a new city quest toward the end of the year.
</blockquote></details></li>
<li><details markdown="1"><summary>Older Android and Java Support</summary><blockquote markdown="1">
Unfortunately, due to changes to code libraries and build tools that Shattered depends on, I will have to make some changes in the next few months that will remove support for **Android 4.0-4.4** and **Java 8-10**.

Devices with these platform versions should still receive v3.2 and any immediate patches, but will not receive updates after that. These devices will be able to continue playing v3.2 indefinitely.

Android 4.4 was succeeded by Android 5.0 in 2014, ~1% of Android Shattered players are using Android 4.4-. Java 10 was succeeded by Java 11 in 2018, but can run on computers from 2010 and earlier.

Note that the Java requirement only applies to the plain .JAR desktop builds of Shattered, which require a separate Java install. If you're unsure which desktop build you're using, it probably isn't the Java one.
</blockquote></details></li>
</ul>


If you're like more frequent incremental updates, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>
