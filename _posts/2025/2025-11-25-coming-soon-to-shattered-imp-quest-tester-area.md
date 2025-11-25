---
title: "Coming Soon to Shattered: Imp Quest Tester Area!"
excerpt: "Hey Dungeoneers, it's been a couple of months since the last patch for v3.2, so it's time to an update! Previously my plan was to release the new city quest in a single large update, almost certainly in 2026, but I've decided to change my tactic on that in favor of a more incremental release. That does mean that v3.3 is going to be a much smaller update, but also means that it's ready for beta right now!"

header:
  image: /assets/images/2025/2025-11-25/header.png
  teaser: /assets/images/2025/2025-11-25/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
# 58  = skeleton key sprite in v3.2.5-
# 264 = skeleton key spritei n v3.3.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 58", "SHPD_ICON_v878: ITEM: 264"]
---

Hey Dungeoneers, it's been a couple of months since the last patch for v3.2, so it's time for an update!

Previously my plan was to release the new city quest in a single large update, almost certainly in 2026, but I've decided to change my tactic on that in favor of a more incremental release. That does mean that v3.3 is going to be a much smaller update, but also means that it's ready for beta right now!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v3.3.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

In this blog post I'm going to go over the reasoning for this change, and what's coming in the now-smaller v3.3 update.

## Why Shrink v3.3?

There are three major reasons why I've decided to break the new quest into multiple updates:

Firstly, a particularly nasty bug in v3.2.5 surfaced shortly after I moved onto development for v3.3.0. The bug only affects certain users, and causes the game to hard-freeze if characters die while a projectile is attached to them. This flew under the radar initially, but for a small % of users it happens every time and is pretty game-ruining. I would really rather not leave this unfixed for even more time.

Secondly, and this won't come as a surprise to long-time readers, I have regretted trying to release huge updates all at once literally every time I have done it. Releasing updates in a more incremental fashion (when it's possible to do so) has always been the correct choice previously and this time is no exception. It doesn't substantially reduce my development speed, gives me time to course-correct based on feedback, and is honestly just a lot less stressful.

Lastly, a lot of the work on the new quest has been concepting that hasn't turned into actual game content yet. While doing this concepting I have also been doing my usual rounds of smaller content tweaks and additions to the game, and it seems a waste to keep them locked behind finishing the city quest when they have nothing to do with it.

## City Quest Beginnings

Okay, so then if the full quest isn't coming, what quest content **is** coming in v3.3?

v3.3 will contain a sort of 'tester area' for the upcoming new quest, just like with the [caves quest had back in v2.1](https://shatteredpixel.com/blog/coming-soon-to-shattered-subfloors-and-digging.html). This includes a new dedicated room for the Imp to appear in, where the new quest will start:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/vault-entrance.webp){: .align-center .rounded-large}

The Imp is standing aside the forcibly-opened entrance to a massive dwarven vault. eventually he'll have you go down there for the quest, but for the moment he'll give you the same quest as in v3.2 and before. In addition to completing that quest as normal, you can walk onto the vault door to be teleported down into the new tester area below...

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tester-area.png){: .align-center .rounded-large}

Eventually this area will be filled with all the hazards and loot you might expect from a quest, but for the moment things are pretty barren and it's mostly just a demonstration of how I'm planning for these levels to be structured. You'll note that this quest uses a very grid-like level structure, with all rooms of a set size. It would get a bit repetitive if regular dungeon floors did this all the time, but it works perfectly for one floor for a quest. Players are free to walk around and explore this empty space as much as they like, before returning to the previous floor.

Part of this tester area is also an implementation of storing and retrieving the player's inventory. You'll have an entire separate inventory in the quest area, which is scrapped and swapped back to your old inventory (fully intact of course) once you choose to leave. Feel free to play around with the items in the tester area, but you can't take them back out ;).

## Other Stuff

As I mentioned further up, v3.3 is also releasing now as I've got a decent bit of side content finished. Here are the highlights:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-misc.png){: .align-center .rounded-large}

v3.3.0 is releasing with Shattered's first new artifact in over a decade! The **Skeleton Key** grants the player new ways to control the dungeon environment. It can be used to open almost any lock in the dungeon, lock doors that weren't previously locked, and create temporary magical walls! There are a lot of cretive ways to make use of this, and it opens up entirely new interactions with all the dungeon's various doorways.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/skeleton-key.webp){: .align-center .rounded-large}

There's also a new trinket coming in v3.3.0. The **Cracked Spyglass** is sort of a milder version of the Mimic's Tooth. It generates extra items in the dungeon, but those items are very hard to see, so keep your eyes peeled! The GIF below has three different environments with 2 hidden items in each, can you see them all? (the sewer one is especially tricky)

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/hidden-items.webp){: .align-center .rounded-large}

Shattered now has options for picking random progression options as well! You can select a random hero, challenges (optionally), talents, subclass, and armor ability. I expect this to both help people who've got a bit of analysis paralysis, and offer a new gameplay option for experienced players who want to mix things up. There's even a new badge for winning a purely random run!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/random-badge.png){: .align-center .rounded-large}

Lastly, as always, this update includes a bunch of smaller fixes and improvements. This time around there's an emphasis on adjusting various little points of annoyance that have been reported over time. This includes things like secrets in the caves being a bit too hard in some cases, the Chalice having an upgrade mechanic that almost demands the player look up numbers, and difficulty spikes on early floors caused by albino rats or hostile champions.

---

v3.3.0 is already content-complete so I expect this beta to be very short, v3.3.0 should release fully in very early December!

If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/39301954), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/680735027732993411)!