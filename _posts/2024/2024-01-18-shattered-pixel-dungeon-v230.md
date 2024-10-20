---
title: "Shattered Pixel Dungeon v2.3.0!"
excerpt: "Hey Dungeoneers, Shattered v2.3.0 has been released! v2.3.0 includes a second gnoll-themed variant for the new caves quest! There are also some smaller item additions, visual improvements to floating text, and the usual slew of small tweaks and bugfixes."
header:
  image: /assets/images/2024/2024-01-18/header.png
  teaser: /assets/images/2024/2024-01-18/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon for display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: CHANGES"]
---

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>Hey Dungeoneers, Shattered v2.3.0 has been released!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon)<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

To celebrate v2.3.0's release, Shattered is also [![](/assets/images/icons/steam.png){: .rounded .text-inline}33% off on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) for the next week!

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline} Pixel Dungeon Lemmy Community](https://lemmy.world/post/10875995), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/4132682727127456731)!

## What's new in v2.3.0

v2.3.0 includes a second gnoll-themed variant for the new caves quest! There are also some smaller item additions, visual improvements to floating text, and the usual slew of small tweaks and bugfixes.

I talked about this update in two previous blog posts:
- [Shattered Pixel Dungeon in 2024](/blog/shattered-pixel-dungeon-in-2024.html)
- [Coming Soon to Shattered: The Gnoll Caves Quest!](/blog/coming-soon-to-shattered-the-gnoll-caves-quest.html)

Here's the full changelog for v2.3.0! Unlike in previous update posts, I've included the entire changelog text, but put it under expandable text. Click or tap on each entry to read more. Note that this changelog may become slightly outdated as patches for v2.3 are released, so check the changes screen in-game for the most up to date version.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new.png){: .align-center}
**New Content:**
<ul>
<li><details markdown="1"><summary>Developer Commentary</summary><blockquote markdown="1">
- Released January 18th, 2024
- 92 days after Shattered v2.2.0

v2.3.0 was originally going to contain two new variants for the caves quest, but after a longer than expected dev cycle plus the holidays, I opted to release v2.3.0 with just one more variant and move on to other content for a while, instead of spending even more time on the caves quest.

More dev commentary will be added here in-game the future.
</blockquote></details></li>
<li><details markdown="1"><summary>Gnoll Caves Quest</summary><blockquote markdown="1">
**A second variant has been added to the caves quest!**

This variant features **gnolls and earth-moving magic.** Expect to spend a bit more time digging, as this environment features collapsed walls, boulders, and angry gnolls wielding spears and earth-moving devices. Their magic is quite chaotic, so be ready to dodge and possibly get the gnolls caught in their own attacks.

The boss for this variant is the **gnoll geomancer,** an experienced gnoll with access to lots of mobility and earth-moving power.
</blockquote></details></li>
<li><details markdown="1"><summary>Remains Items</summary><blockquote markdown="1">
**Heroes remains now contain a new unique item that varies based on the class of the hero that died.**

These items are single use consumables that provide a small benefit that's themed after the hero who died. There are also two new badges relating to these items.

Remains now always contain a signature remains item in addition to an extra item from the previous run, if one was chosen. This replaces the previous behaviour, where remains would contain 50 or 10 gold if no eligible item could be chosen.

Additionally, remains which contain a stackable item from the previous run now cap the quantity of that item at 3.
</blockquote></details></li>
<li><details markdown="1"><summary>New Holiday Items</summary><blockquote markdown="1">
Shattered has had little holiday food items that temporarily replace cornish pasties ever since 2016, but only for Halloween and the Winter Holidays. Throughout 2024 you'll see a bunch of new items for more holidays through the year, which all have different tiny bonus effects when eaten.

For now I have implemented items for Lunar New Years and Easter, with more on the way in future updates.

I've also shortened the duration for Halloween and the Winter Holidays after 2023, so as not to make the game overly festive in the later months of the year, and nerfed the healing effect on Halloween pumpkin pies.
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/changes.png){: .align-center}
**Changes:**
<ul>
<li><details markdown="1"><summary>Floating Text Icons</summary><blockquote markdown="1">
The little bits of floating text that appear above characters to indicate damage, positive effects, and currency gain now have tiny icons to indicate the type!

For damage, it is now shown whether the damage is physical, magical, or if it comes from a particular debuff or DOT effect. There are separate physical damage icons depending on whether armor reduces the incoming damage. Armor never reduces magical or DOT damage. Damage text is also now always red, warnings and negative effects are always orange.

For positive effects, icons are now shown for healing, shielding, and exp gain. Loads of healing or shielding effects which previously didn't show floating text now do as well.
</blockquote></details></li>
<li><details markdown="1"><summary>20+ Misc. Changes</summary><blockquote markdown="1">
**Highlights:**
- Improved the sprites for Armored Brutes and DM-201s
- The troll blacksmith no longer works on cursed items
- Reduced the chance for sleeping enemies to clump together in caves quest levels
- Random scroll and potion drops are now more consistent throughout a run

**Enemies:**
- DM-300's rockfall attack now uses positional danger indicators
- Improved visual clarity of sparks in the DM-300 fight
- Removed unnecessary game log entries when DM-300 uses abilities
- Phantom piranhas now die on land if there is no water to teleport to

**Items:**
- Added a warning when trying to steal from shops with less than 100% success chance
- Curse infusion now preserves an existing curse on items that don't have the curse infusion bonus yet
- long pressing on the ghost equip window now shows the stats of equipped items

**Allies:**
- Ghosts and Rogue's shadow clone are now considered inorganic (immune to bleed, toxic, poison)
- Corrupted allies no longer attack passive enemies
- Spirit hawk now interrupts the hero when it expires

**Misc:**
- Added a bit of clarity text to some parts of the blacksmith quest/rewards
- Surface scene now shows night later in the evening as well as after midnight
- Did a consistency pass on heal over time effects interrupting the hero resting
- Long-press to assign quickslot now works in the full UI inventory pane, just like the mobile inventory window
- Added support for themed icons on Android 13+
- Removed support for saves prior to v1.4.3
- Added developer commentary for v1.2.0
</blockquote></details></li>
<li><details markdown="1"><summary>45+ Bugfixes</summary><blockquote markdown="1">
Fixed the Following bugs:

**Highlights:**
- Enemies continuing to fight each other after amok expires in many cases
- Some inter-level teleportation effects working inside caves quest level
- Transmutation being usable on the pickaxe during the caves quest
- Unintended changes to reforge functionality when both items are the same level
- Rounding errors causing tipped darts to last longer than intended in some cases

**Quests:**
- Crystal spire being considered a mini boss, not a full boss
- Crystal spire attacks ignoring damage-resisting effects
- Cases where remains would fail to appear in the new mining level
- Blacksmith landmark entry not clearing when you have spent all favor
- Rare cases where hero could appear to be on top of crystal spire
- Corpse dust quest tracking all wraiths instead of just the ones it spawned
- Some cases where new rot garden room could spawn much smaller than intended

**Enemies:**
- Final boss fight not properly interacting with the into darkness challenge
- Monk ability use disqualifying for dwarf king's 'no weapons' badge when a weapon was equipped
- Tengu behaving slightly incorrectly when taking massive damage
- Mimics not dropping their loot if corrupted while hiding
- Rare cases where DM-300 finale music would play before the fight
- Rare errors in DM-201 target selection

**Items:**
- Rotberry seed being deleted in rare cases
- Rare cases where the game would freeze after reviving via unblessed ankh
- Some bombs and explosion-spawning effects incorrectly dealing magic damage
- Foresight effects not triggering after level transition
- Projecting missile weapons not working on enemies inside solid terrain
- Cursed wand of warding having different targeting properties than other wands
- Thrown potions not clearing fire/ooze if they shattered out of view
- Retribution and psionic blast not applying to all visible characters in very rare cases
- Degrade debuff not applying to thrown weapons
- Cloak of shadows not losing charge if it is dispelled as it is activated
- Items being assignable to non-visible quickslots in specific cases
- Rare quickslot errors when bags which already contain items are collected

**Hero & Allies:**
- Thrown potions not triggering Liquid Agility talent
- Sneak ability working while Duelist is rooted
- Damage from Body Slam talent ignoring armor
- Lunge ability incorrectly interacting with movespeed in some cases
- Cases where prismatic images could keep appearing and then disappearing
- Hero not being able to self-trample plants when standing on stairs
- Berserker being able to rage without his seal equipped in some cases
- Allies rarely spawning on hazards after ankh revive
- Ally warp working on corrupted DM-201s
- Duelist's lunge ability not correctly applying range boosts in rare cases

**Misc.:**
- Various rare crash and freeze bugs
- Various minor visual and textual errors
- Tutorial becoming stuck in rare cases
- Beta updates setting not working as intended
- Music fading not working in rare cases
- Scrolling pane in journal window freezing in rare cases
</blockquote></details></li>
</ul>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/buffs.png){: .align-center}
**Buffs:**
<ul>
<li><details markdown="1"><summary>Hero Abilities</summary><blockquote markdown="1">
No nerfs this time, and just a couple targeted buffs to hero abilities/talents. 

- **Rogue's Foresight** talent trigger chance increased to 60% at +1 and 90% at +2, up from 50% at +1 and 75% at +2.

- **Elemental Strike** ability base range increased to 4 from 3.
</blockquote></details></li>
</ul>

## What's coming next?

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/upcoming.png){: .align-center}

- The next update will be v2.4.0, including a new type of item called trinkets!
- Trinkets are a new item type that are more about tweaking gameplay variables than giving direct power or utility. You'll be able to get one trinket per run (with some choice), which will change up the game slightly with effects such as increasing rare enemy spawn rates or making enchantments and curses more likely. Trinkets will be upgradeable via alchemical energy, increasing the strength of their effect.
- As always, v2.4.0 will include some smaller changes and fixes as well. Right now I'm considering making some targeted balance and design tweaks to various hero abilities, but I haven't locked that in yet as there are lots of little things I could choose to look into changing or improving.
- The next update will also be dropping support for iOS 9 and 10, which currently make up ~0.05% of Shattered's iOS playerbase. I'm making this change due to an update to Shattered's game library (libGDX), and to remove the requirement to include 32-bit iOS code with the game. iOS 9 and 10 players will still be able to continue playing Shattered Pixel Dungeon v2.3.

I'd like to try and release v2.4.0 fairly quickly to put us onto a good pace for 2024, but we'll see how well that actually turns out. Expect to hear something from me one way or another later in early to mid March. Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!

In the meantime you can subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline} Shattered Pixel Newsletter](/newsletter), or follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline} Mastodon](https://mastodon.gamedev.place/@ShatteredPixel) if you'd like more frequent incremental updates.

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>
