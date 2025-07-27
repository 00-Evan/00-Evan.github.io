---
title: "Coming Soon to Shattered: Thrown Weapon Sets!"
excerpt: "v3.2 has just gone to beta, with an overhaul to thrown weapons and some other substantial balance and QoL changes! In this blog post I'm going to go over what's changing in v3.2 in more detail."

header:
  image: /assets/images/2025/2025-07-25/header.png
  teaser: /assets/images/2025/2025-07-25/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
# 151 = thrown spear sprite
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 151"]
---

Hey Dungeoneers!

v3.2 has just gone to beta, with an overhaul to thrown weapons and some other substantial balance and QoL changes!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v3.2.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

In this blog post I'm going to go over what's changing in v3.2 in more detail.

## Thrown Weapon Sets

Thrown weapons have been in an awkward spot for a while now. Prior to [v0.6.3](https://shatteredpixel.com/blog/coming-soon-to-shattered-new-ranged-weapons.html) they were single-use consumable items that you couldn't upgrade. Over time I've improved them with things like durability, upgrading, and dart tipping, but the upgrading experience is still far from ideal. Currently thrown weapons can only be upgraded individually, which the vast majority of players find way too restrictive.

I've finally decided to solve this problem by changing up how thrown weapons work a bit. Rather than having all thrown weapons of a kind stack together, they will now spawn in 'sets' of three, and sets will not mix. This makes quantities more consistent, so I can have upgrades apply to an entire set at once! In fact, this doesn't just stop at upgrades, thrown weapons can now be enhanced in almost every way that a melee weapon can, including enchantments, curses, augments, and naturally spawning upgrades!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-thrown.png){: .rounded-large .align-center}

Of course, thrown weapons are currently balanced around a base quantity of 2 and being upgraded one at a time. Massively increasing the uptime of thrown weapons like this without making adjustments anywhere else would make them absurdly overpowered. For now I have scaled back base durability a bit, heavily reduced the amount of durability an upgrade gives to each thrown weapon, and also reduced thrown weapon damage scaling a bit. There are also some targeted nerfs to some thrown weapons that will become more spammable due to this change.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/thrown-blazing.gif){: .rounded-large .align-center}

**Note that this is a pretty big changeup to an entire category of equipment. I expect there will be followup tweaks to thrown weapons and mechanics that tie into them during and after the beta.**

---

It's not quite enough to have its own section, but v3.2 also includes some pretty substantial subclass balance tweaks, mainly meant at better balancing options in a few cases. The Battlemage is getting some new on-hit effects to replace some phoned-in enchantment copies, the Gladiator is getting more combo flexibility, and the Priest is getting some improvements to spell synergy and the illuminated debuff. I hope that will put these subclasses onto a more even footing vs. the Warlock, Berserker, and Paladin respectively. Just like with thrown weapon sets I'll be keeping an eye on these changes.

## Hit & Miss Icons

While thrown weapon sets are the only major content change coming in v3.2, there is one pretty massive QoL change too! In v3.1 I added a little icon that appears when the newly-added Ferret Tuft was the reason an attack missed. I'm now expanding that system to apply to almost every source of accuracy and evasion in the game!

There are 11 miss icons in total, that will show up in any situation where an effect caused an attack to miss. They are, in order: -acc from weapons, +evasion from armor, bless (and bless-like effects), hex, daze, cursed accuracy ring, evasion ring, liquid agility, defensive stance, ferret tuft, and freerunning.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/miss-icons.png){:.align-center}

The system applies to hits from physical attack too! There are 12 new icons here, which all piggyback on the existing sword icon. They are, in order: +acc from weapons, -evasion from armor, bless (and bless-like effects), hex, daze, accuracy ring, cursed evasion ring, liquid agility, sword dance, surprise attacks, precise assault, and projectile momentum.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/hit-icons.png){:.align-center}

Here's a little GIF that shows these in action. The Cleric hits due to a surprise attack, the rat misses due to bless, then the Cleric hits again due to the +acc on their cudgel. Of course, these new icons won't show up as often in regular gameplay.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/hit-miss.gif){: .rounded-large .align-center}

## Saying Goodbye to Android 4.X

v3.2 also includes one pretty unfortunate change for ~1% of Shattered's Android playerbase: it will be the last version that Supports [Android 4.0 ICS](https://en.wikipedia.org/wiki/Android_Ice_Cream_Sandwich), [4.1-4.3 JellyBean](https://en.wikipedia.org/wiki/Android_Jelly_Bean), and [4.4 KitKat](https://en.wikipedia.org/wiki/Android_KitKat).

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/android-vers.png){: .rounded-large .align-center}

I'm quite proud that Shattered runs on some absolutely ancient Android phones. I can currently still play it on my old [Nexus S](https://www.gsmarena.com/samsung_google_nexus_s-3620.php), a phone released back in 2010! I have needed to increase the minimum Android version over the years though, first dropping [Android 2.2 in 2019](https://shatteredpixel.com/blog/saying-goodbye-to-android-2.2-froyo.html), and then [2.3 in 2021](https://shatteredpixel.com/blog/saying-goodbye-to-android-2.3-gingerbread.html). Now there's unfortunately a pretty big bump, as there were some major internal changes made to Android in 4.4 and 5.0.

I've actually been trying to hold onto support for these devices for a little while now, as since 2021 their % of Shattered users has only dropped to 1% from 2%, but it's sadly no longer feasible. Several code libraries that Shattered depends on now require Android 5.0+, and soon a [requirement by Google](https://developer.android.com/google/play/billing/deprecation-faq) will force me to update these libraries in order to keep releasing on Google Play. In terms of overall Android users, the number of people on 4.4- has dropped to 0.1% from 2% in 2021.

Coincidentally, with this change the oldest Android device that can still run Shattered will be my old [Nexus 4](https://www.gsmarena.com/lg_nexus_4_e960-5048.php), first released in November 2012, the same month as the release of the original Pixel Dungeon! I am sorry to those of you who won't be able to get future updates, but I have no plans to drop support for any more Android versions for the foreseeable future.

---

I expect the beta for v3.2 to last for about a week. If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/33469511), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/595155315671106141)!