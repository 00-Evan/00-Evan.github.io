---
title: "Coming Soon to Shattered: New Enchants and Pixel Art!"
excerpt: "Unfortunately v4.0 is still a little ways out, it's ended up as a much bigger update than expected! In this blog post I'm going to share a quick update on the vault quest, then go over some very exciting things also coming in v4.0."

header:
  image: /assets/images/2026/2026-06-01/header.png
  teaser: /assets/images/2026/2026-06-01/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#63 = Amulet of Yendor item sprite in v0.9.3+
tags: ["SHPD_INGAME", "SHPD_ICON_v533: ITEM: 61"]

gallery:
  - url: /assets/images/2026/2026-06-01/new-special-rooms.png
    image_path: /assets/images/2026/2026-06-01/new-special-rooms.png
  - url: /assets/images/2026/2026-06-01/new-secret-rooms.png
    image_path: /assets/images/2026/2026-06-01/new-secret-rooms.png

---

Hey folks!

Sorry for the extended wait, I'm back with some news on v4.0 and a new ETA! Unfortunately v4.0 is still a little ways out, it's ended up as a much bigger update than expected! Currently I <u>estimate that v4.0 will ready for beta sometime in July</u>, hopefully earlier in the month.

In this blog post I'm going to share a quick update on the vault quest, then go over some very exciting things also coming in v4.0.

**(Please keep in mind that while I always try to keep to the ETAs I provide, they are just estimates. If you don't hear from me by the ETA, it means I'm still busy with the update!)**

## Vault Quest Progress Update

Last time you heard from me [in early March](http://shatteredpixel.com/blog/coming-soon-to-shattered-a-new-city-quest.html) I had progressed the vault tester area to the point where I was finished updating it publicly. Basically everything about the quest has been expanded on since then, but a few highlights are:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-vault-entry.webp){: .align-center .rounded-large}

- The vault now has a variety of enemies, heavily based on existing enemies in the prison, caves, and city. This makes it easy to tell the threat level of each enemy at a glance. I would like to at least make sprite tweaks though so they're a bit more distinct before release.
- I've added more rooms to the vault since the tester area's last update, and also made several tweaks to level layout so that the vault is a little more interconnected. Finding a good room quantity and level shape is crucial so that the quest isn't overly long.
- The vault is now filled with much more purposefully placed loot, giving the player a nice progression of gear and consumables as they get stronger. I do plan to do more tuning here though, as there need to be a few more guardrails to prevent cases of bad luck.
- Dwarf Tokens are making a return as guaranteed loot from each vault enemy! I plan to make tokens an important part of vault progression, tieing into a powerup you'll receive in the back-half of the quest.
- Lastly, I've started proper concepting work on the quest's boss! I have a very promising idea here, but for now all I'll say is that the vault does a good job of ensuring players enter the boss with a variety of ways to deal damage, and I intend to make you use them!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/elementals.webp){: .align-center .rounded-large}

## New Enchants

v4.0 is coming with more gameplay content than just the quest though, there are also going to be four new weapon enchants and two new curses! For these I've tried to emphasize two things: bringing back old enchantment effects that were previously removed in v0.7.2 (~7 years ago!), and trying out more enchantments that grant bonus damage with downsides that have to be managed (like blazing).

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-enchants.webp){: .align-center .rounded-large}

- **Venomous** is a returning common enchantment that now applies stronger stacking poison, but on a new three turn delay. The delay encourages 'hit and run' style tactics.
- **Vorpal** is a returning uncommon enchantment that now has a chance to replace **all** damage with non-stackable bleeding. This is more overall damage, but with a delay like venemous.
- **Eldtrich** is a returning uncommon enchantment that now applies fear to enemies nearby that **aren't** your primary target. This helps manage multiple enemies at once.
- **Crystal** is a new rare enchantment that gives a big damage boost, but at the cost of your weapon having durability. Crystal weapons self-repair over time, but permanently break if you lean on them too much at once.
- **Pressurized** is a new curse that has a chance to create a geyser of water, pushing away both you and the enemy. The geyser's push direction is random if using a thrown weapon.
- **Wondrous** is a new curse that lets weapons tap into the same random cursed effects as wands. That's 32 different effects in total, and yes this will work with wondrous resin!

## New Pixel Art!!!

New enchantments are exciting of course, but there's another addition coming in v4.0 that lots of you have waited for.

**v4.0 will include the first wave of new art that I've been teasing since 2024!**

Since the start of 2026 I've managed to get the pixel art improvement project started back up thanks to the help of two artists.

Firstly, an artist who previously worked on new item and character sprite art has returned! <u><b>PumpkinVolt</b></u> has done almost all of the item sprite improvements you've seen in blog posts from [2026](http://shatteredpixel.com/blog/shattered-pixel-dungeon-in-2026.html#what-about-new-pixel-art) and [2024](https://shatteredpixel.com/blog/ten-years-of-shattered-pixel-dungeon.html#new-pixel-art), and is returning now to continue that work! I'm planning to release this new item art in waves, with v4.0 focusing on standard consumable items:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-items.png){: .align-center .rounded-large}

Compared to [last time](http://shatteredpixel.com/blog/shattered-pixel-dungeon-in-2026.html#what-about-new-pixel-art), there have already been various improvements to coloration and tweaks to outlines, but we do plan to make a few more adjustments to this art based on feedback before release. The symbols on the new scrolls were a common point of criticism, and so here's a WIP of a tweaked scroll design that better preserves the original symbols:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-scrolls.png){: .align-center .rounded-large}

Next, [**Aleksandar Komitov**](https://www.alekskomitov.com/), the game's splash artist, is now also working on new pixel art and in-game art direction! Currently Alek's primary focus is on environment art, with an emphasis on expanding the environmental art assets without changing the style. Just like with items, I intend to release this art in waves, here's what we're hoping to have ready for v4.0:

We're not going too hard on universal art changes just yet, but one specific effect being added is a light shadowing where wall meets floor that enhances the depth of the game's 2.5D visuals. This subtle darkening is easy to apply to the whole dungeon once implemented:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/occlusion.webp){: .align-center .rounded-large}

As v4.0 is adding a new quest in the dwarven halls, there's also work being directed at quest areas (old on top, new on bottom):

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-quest-rooms.png){: .align-center .rounded-large}

...and the dwarven halls themselves! In particular we're experimenting with a new alt floor tiled visual, and then eventually migrating carpets to be something that can appear in every region with different colorations.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-tiles-and-carpet.png){: .align-center .rounded-large}

There's also a whole bunch of blueprinting work done on the various special and secret rooms of the dungeon. A lot of this will take time to implement though, and so they probably aren't coming in v4.0. Here are a few highlights:

<center>{% include gallery id="gallery" caption="You can select each image to zoom, old on top, new on bottom." %}</center>

I'm very excited to get this project back going and finally make good on the almost 2 year old promise of new in-game art! Hopefully v4.0 is the first of several updates that will include new and refreshed art in the game.

<u>Feedback is a crucial part of the process as always, so please don't be afraid to let me know what you think!</u>

## Anything Else?

As always, there are lots of little things being fixed and tweaked too.

One notable QoL tweak I'm making is a change to health bars. They will now visibly darken to show the total amount of incoming damage from damage over time effects. This is especially helpful for the returning venomous and vorpal enchantments.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dot-healthbar.webp){: .align-center .rounded-large}

There's also a significant change being made to the **swarm intelligence** challenge. Currently the rules for when swarm triggers are pretty inconsistent and experienced players have found a bunch of ways to avoid triggering the challenge entirely. I've decided to remove those inconsistencies, but also change up the challenge so that the alert range starts low (just 2 tiles, instead of 8) and grows the longer you stay in enemy line of sight. Even breaking sight for a moment resets the alert range. This way tricky strategy is still rewarded, but as a proper part of the challenge instead of an unintended quirk.

---

I do wish that v4.0 was ready sooner, but this is an exciting time for Shattered nonetheless. I expect when v4.0 does release it will have been worth the wait!

If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter) (recently migrated to a better provider!)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/47628599), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/658233956736600203)!