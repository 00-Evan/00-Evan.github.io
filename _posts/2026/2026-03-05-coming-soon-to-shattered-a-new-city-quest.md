---
title: "Coming Soon to Shattered: A New City Quest!"
excerpt: "Hey folks! In this blog post I'm going to go over all of the things I've added in v3.3 patches, and how I think they're going to fit together into a new quest!"

header:
  image: /assets/images/2026/2026-03-05/header.png
  teaser: /assets/images/2026/2026-03-05/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v533: sprites/demon.png, 0, 0, 13, 14"]

---
 
Hey folks!

v3.3 released a little while ago now, and (after the holidays) I've been busy with expanding the tester area for the new quest in patches to v3.3. v3.3.7 is releasing today, and with that the tester area has progressed to a point where I think it's time for me to stop releasing patches and lock in on putting everything together into a complete quest.

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>You can try out everything I mention here in the tester area in-game:</u></b>
<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) for Android.
<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) for iOS.
<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) or [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon) for Computers.
<br>- On [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon) or [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Computers.
</div>

In this blog post I'm going to go over all of the things I've added in v3.3 patches, and how I think they're going to fit together into a new quest!

## Level Shape

Firstly, as I've already shown when v3.3 went to beta, the new quest area exists in a new type of level that uses a unique grid-based layout. This features new 9x9 rooms that all fit into the grid shape. Things have progressed a LOT since the initial tester area though, which was basically just rigidly coded:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/330-tester-area.png){: .align-center .rounded-large}

The area now uses proper level generation logic and supports all the sorts of variance that regular dungeon levels can have. There's also a load of new rooms designed to use the new features and hazards of the quest area:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/337-tester-area.png){: .align-center .rounded-large}

There's still quite a lot more for me to implement before a proper beta, but all of the things I've added in the tester area give a pretty good idea of where things are going, so lets go over them in a little more detail.

## New Enemy Behavior

Stealth is a major part of this quest, as the player starts out with no gear and has to work their way back up. Enemies will be present obviously, but the existing enemy AI doesn't really work in this case. The existing AI is designed around the player almost always wanting to fight, and so enemies are pretty sticky. That doesn't work so well here, so I've made two major changes just for enemies in the vault.

The first major change is a new enemy AI state: investigating. Enemies will now investigate when they first notice you instead of immediately starting to hunt you. Investigating enemies still move toward you, but won't attack and will give up earlier than usual if they lose sight of you. In most cases this gives you 1-2 extra turns to duck behind a door or corner to shake an enemy before they start pursuing you more aggressively.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/emo-icons.webp){: .align-center .rounded-large}

Second, enemies that are nearby but behind walls can be 'heard' in the vault. This is represented as some VFX that play as enemies move in tiles outside of your FOV. This gives you a way to know enemy movement without exposing yourself to them.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/movement-detection.webp){: .align-center .rounded-large}

Lastly, enemy detection chances are different in the vault:
- Detection chance is a bit lower across the board.
- Sleeping enemies won't notice you at all outside of 3 tiles of distance. Silent steps talent still reduces this to 2 or 1 tiles.
- Enemies often patrol in pre-set locations while wandering, and won't notice you outside of 2 tiles behind their movement direction.

These changes reduce the chance of detection if you keep your distance, and also create much more opportunity to sneak around/behind enemies as long as you time your movement well.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/wandering-detection.webp){: .align-center .rounded-large}

Currently every enemy in the tester area is just a simple rat, but the full quest will make use of a variety of enemies at different levels of strength. Some enemies will be able to be tackled early on, while others are best avoided until you've geared up.

## Static Hazards

Of course a big vault needs some static hazards too! I've added three new hazards that test positioning skill:

Firstly we have **Scanning Sentries**, which act a bit like a classic security camera. They sweep the environment using pre-programmed cone patterns. The number of cones and pattern locations are highly flexible. I've yet to decide what the penalty for being spotted will be, something like a lightning shock to the player, or an alert to nearby enemies, sounds likely. Here's one example that puts a sentry in the center of a room:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sentry-circle.webp){: .align-center .rounded-large}

Next we have **Fire Vents**, which ignite anything on their location based on a pre-programmed delay. They can only threaten one tiles each, but can be placed a lot more flexibly. Here's an example that covers a room and vents fire in an alternating pattern:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/fire-traps.webp){: .align-center .rounded-large}

Lastly there are **Laser Sentries**, which act a bit like scanning sentries but with a single laser beam and potentially more variable cooldown. Like fire vents, these work a bit better for coating a room than scanning sentries, and can make a pretty complex hazard pattern with a bit of randomness:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/lasers.webp){: .align-center .rounded-large}

Of course these hazards can work to just make regular traversal more tricky, but they're at their best when they're guarding something!

## Treasure Rooms and Progression

While some loot will be found just laying around, single-entrance treasure rooms are going to be the primary way that the player finds better gear and progresses through the quest. In many ways this is a bit of a remix of how special rooms work in the normal dungeon, which is very much intentional.

However, there needs to be some stratification to the types of treasure rooms and treasure room rewards. Some rooms are going to need to be solvable right away, where others are going to require certain gear (or at least be extremely difficult without that gear). Currently this is forming into three tiers:

**Tier 1** treasure rooms contain low tier loot and are mostly going to make use of hazards or prison-level enemies that can be avoided or defeated fairly easily. As an example, this treasure room looks intimidating with its waves of progressive fire traps, but can be solved purely through positioning.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/fire-rows.webp){: .align-center .rounded-large}

**Tier 2** treasure rooms will have mid tier loot and involve a couple caves-level enemies or hazards configured in a way that the player will need some better equipment and/or a consumable to overcome them. As an example, this room uses bookcases to hide its real loot, so you'll need an item capable of burning them down.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/bookcases.png){: .align-center .rounded-large}

**Tier 3** treasure rooms will have the best loot, and so will be substantially more difficult. They'll likely have multiple city-level enemies, or hazards that require a specific high-value consumable to overcome. As an example, this room is filled with more than enough sentries to make looting impossible. You'll need a high-value item like a potion of invisibility or the Rogue's cloak of shadows.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/many-sentries.webp){: .align-center .rounded-large}

My goal is for these tiers of treasure rooms and variance of enemy strength to create a nice gameplay flow through the quest. The player starts out by sneaking around, identifying the rooms they can solve, and steadily gets stronger and becomes able to confront the hazards they previously avoided.

---

All of these things lead up to bigger enemy hazards, regaining unique hero items, and eventually a quest boss and quest reward! Expect more coverage of that in the next blog post in about two months, when the quest will hopefully be close to completion.

**(Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don’t hear from me by the ETA, it means I’m still busy with the update!)**

If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/43893325), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/806844795448340772)!