---
title: "Coming Soon to Shattered: The Vault Quest!"
excerpt: "Hey Dungeoneers, after far too long of a wait, v4.0.0 is finally ready for beta! This update ended up ballooning in size from just adding a new quest, I'd say it's arguably Shattered's biggest update yet at this point! There's a massive new quest, a bunch of new in-game art, 6 new enchantments, and plenty smaller changes and adjustments. In this blog post I'm going to quickly show off some of the now-finished new quest. Don't expect all the details though, I wouldn't want to spoil everything!"

header:
  image: /assets/images/2026/2026-08-15/header.jpg
  teaser: /assets/images/2026/2026-08-15/header-small.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v533: sprites/demon.png, 0, 0, 13, 14", "SHPD_ICON_v897: sprites/imp.png, 0, 0, 13, 14"]

level-gallery:
  - url: /assets/images/2026/2026-08-15/330-tester-area.png
    image_path: /assets/images/2026/2026-08-15/330-tester-area.png
  - url: /assets/images/2026/2026-08-15/337-tester-area.png
    image_path: /assets/images/2026/2026-08-15/337-tester-area.png
  - url: /assets/images/2026/2026-08-15/400-vault-final.png
    image_path: /assets/images/2026/2026-08-15/400-vault-final.png

elemental-gallery:
  - url: /assets/images/2026/2026-08-15/fire-wave.webp
    image_path: /assets/images/2026/2026-08-15/fire-wave.webp
  - url: /assets/images/2026/2026-08-15/frost-cone.webp
    image_path: /assets/images/2026/2026-08-15/frost-cone.webp

---

Hey Dungeoneers, after far too long of a wait, v4.0.0 is finally ready for beta!

This update ended up ballooning in size from just adding a new quest, I'd say it's arguably Shattered's biggest update yet at this point! There's a massive new quest, a bunch of new in-game art, 6 new enchantments, and plenty smaller changes and adjustments.

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v4.0.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

In this blog post I'm going to quickly show off some of the now-finished new quest. Don't expect all the details though, I wouldn't want to spoil everything!

## A Quick Recap & Improvements

I already shared a lot of the base details for the quest in [a previous blog post back in March](https://shatteredpixel.com/blog/coming-soon-to-shattered-a-new-city-quest.html), and gave a small update (along with sharing details on new art) in [another post in June](http://shatteredpixel.com/blog/coming-soon-to-shattered-new-enchants-and-pixel-art.html). Those details haven't really changed, but the implementation has been refined a lot even since June. Read over those two posts if you want every detail, but I am going to quickly go over everything and what improvements I've made:

### Level Shape & Rooms

This new quest involves the Ambitious Imp tasking you with raiding an ancient dwarven vault! The vault is full of hazards, **and you can't take any of your gear with you**, but the treasures within the vault are also great!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/vault-entry.png){: .align-center .rounded-large}

The vault is still built out of a number of square rooms in a grid, but the specific shape has been improved a LOT:
- I've toned down the total number of rooms in the vault to prevent the quest from being overly long.
- A few new rooms of each type (regular and treasure rooms) have been added to improve variety, and the boss room has been filled in.
- I've made some big improvements to overall level shape and interconnectedness. This cuts down on dead ends and feeds into the vault looking like a structured grid of rooms.
- There's lots of smaller refinements too, including specific room adjustments, preventing identical rooms from being adjacent to each other, and ensuring the final room is a minimum distance from the entrance.

Here's what that all those improvements like in practice:

<center>{% include gallery id="level-gallery" caption="From left to right these images are from November, March, and Today" %}</center>

### Enemies, Hazards, & Loot

Lots of the base nuts and bolts are the same here too, but things have been heavily expanded from the tester area in v3.3.8:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/wandering-detection.webp){: .align-center .rounded-large}

- Enemies in the vault still use new less aggressive AI behavior to facilitate stealth gameplay, little has changed there.
- There are now a total of 7 different enemy types, which lean heavily on existing enemies from the prison to the city. Using these enemy designs makes it easy for the player to tell how dangerous each enemy is.
- The three static hazards (scanning sentries, laser sentries, and fire vents) show up in a few more rooms now, and I've made some adjustments to ensure they aren't overly punishing to mis-steps.
- Overall loot quantity has been increased, and I've added some guardrails to ensure a minimum amount of every kind of equipment gets generated.
- Better loot is guarded by stronger obstacles, and I've spent a long time refining things to create a satisfying little microcosm of progression within the vault.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/target-cells.webp){: .align-center .rounded-large}

## What's New?

Okay so I've spent a lot of time finishing up and polishing things that I've already talked about, but is there anything totally new? There are two major additions that I hinted at two weeks ago in [a status update post](https://shatteredpixel.com/blog/status-update-v40-beta-soon.html), let me elaborate on them a bit more:

### Dwarf Tokens and the Mirror

Each treasure room and enemy drops a single dwarf token, ten of which are used to unlock a door in a special room a little bit deeper into the vault. Each token is equally important for this, so there's a reason to clear weaker enemies and treasure rooms even after you've started powering up.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mirror.png){: .align-center .rounded-large}

In addition to high-tier regular loot, you'll also find a mysterious mirror here. I won't spoil exactly how, but this mirror will let you **access your hero's signature items!** This means that each hero gets access to a large chunk of their abilities that require their item, which were lost upon entering the vault. The Duelist is a little different and gets a guaranteed strong weapon here instead.

I'm really pleased with this mechanic, as it helps to regulate the fact that some heroes have powers that are highly dependent on upgrading equipment (Warrior, Mage, Duelist) and others get abilities that scale more strongly with their level (Rogue, Huntress, Cleric). By taking away signature hero items, everyone starts on a roughly equal playing field (no nuking early enemies with Holy Lance!), but after enough powering up it's safe to re-introduce these items and let each hero lean back into their distinct powers.

### The Boss and Quest Reward

If you've regained your signature item and acquired an arsenal of other loot, you're probably about ready to head into the final vault chamber and square off against the boss!

The final chamber of the vault is guarded by a new enemy: **The Greater Elemental!** I've already shown off a bit of it in the previous status update post, but here's two gifs of its attacks in case you missed them: (Note that the visuals here are a WIP and not final)

<center>{% include gallery id="elemental-gallery" %}</center>

And here's one more, showing off a third shocking form:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/lightning-bolt.webp){: .align-center .rounded-large}

I'm going to be light on the details here as I think it's best for players to experience the boss without any major spoilers, but I am very excited to see how people handle this design. It's easily one of most complex boss fights I've ever added to the game, and is specifically designed to test how well you use the variety of loot you've aquired in the vault. Expect to do a lot of adapting on the fly!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/vault-rewards.png){: .align-center .rounded-large}

All of this leads up to the final room in the vault and the quest's reward! Reach the Imp's prize and he'll let you take **any item you like back out of the vault with you!** The best loot in the vault is all comparable to the reward from the classic Imp quest (a +2 to +4 ring), but there is a much greater variety of possible options. Doing well in the quest will also convince the Imp to set up shop for you further down in the dungeon.

Even if you can't quite defeat the boss, the Imp will still give a partical reward for exploring and clearing out the vault. If you do a good job of that but don't kill the boss, you can expect to take a lesser item (no higher than +1) out with you, and the Imp will still set up shop later in the dungeon.

---

I really hope everyone enjoys v4.0.0! It's ended up being a much bigger and longer developed update than I initially thought, but hopefully all the new stuff in it will have been worth the wait. There's still a few things to polish up on (visuals and balance, mainly), so I expect this beta will be a bit longer than normal, but short for a major update. Maybe 2-3 weeks.

If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, an exclusive discord, monthly content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/50703173), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/84031737849653609)!