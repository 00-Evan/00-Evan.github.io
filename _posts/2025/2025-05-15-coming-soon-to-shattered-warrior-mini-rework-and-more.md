---
title: "Coming Soon to Shattered: Warrior Mini Rework and More!"
excerpt: "Hey Dungeoneers, v3.1 is ready for beta, just in time to meet the estimate I gave (for once)! In this blog post I'm going to go over what's coming in v3.1! This update has a a mini Warrior rework, some new rooms in the dungeon, a new trinket, and an assortment of other changes and additions."

header:
  image: /assets/images/2025/2025-05-15/header.png
  teaser: /assets/images/2025/2025-05-15/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
# 66 warrior seal sprite
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 50"]
---

Hey Dungeoneers, v3.1 is ready for beta, just in time to meet the estimate I gave (for once)!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v3.1.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via their beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop
</div>

In this blog post I'm going to go over what's coming in v3.1! This update has a a mini Warrior rework, some new rooms in the dungeon, a new trinket, and an assortment of other changes and additions.

## A New Warrior Ability

As a quick recap, the Warrior currently has an ability that gives him one passive shielding every 30 turns, which is effectively +33% health regen that works even when hungry. This power is hard to notice and impossible to interact with, but also easy to use and very impactful over the course of a run. This results in the Warrior feeling a lot weaker than he actually is, and I'd like to make the seal's power easier to notice and interact with without making it outright stronger or harder for new players to use.

Here's how that's happening: When the Warrior is about to take damage that would reduce him to 50% health or lower, he will now instantly gain a shield that scales with his armor's tier, with a cooldown of 100 turns. This up-front shield boost is way easier to notice compared to a passive shield that just takes 1 or 2 off most attacks. To start out you'll get 5 shield, and this can go as high as 15 with T5 armor and the iron will talent. Here's how that looks in action:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/warrior-shield.gif){: .rounded-large .align-center}

This means that in theory the Warrior is going from 30 turns per shield to 20 at the start, going as low as 6. That's a huge buff on paper, but it also assumes that the player is constantly fighting at 50% HP or lower. This creates a nice little point of interaction for experienced players, who'll want to try and maximize shield uptime. Newer players don't have to do anything in particular to just use the ability though, as it still triggers automatically whenever the Warrior needs it.

Other Warrior mechanics are getting smaller changes to compensate for this. Several talents are getting shuffled around a bit, and the Berserkser subclass is getting its own separate shield buff instead of piggybacking on the seal's shielding buff. The Berserker's shield still scales with armor level as well, so players who want to dump their upgrades into armor will still have a mechanic that scales with that.

## New Terrain and Rooms

<b><u>(Note that the new visuals shown here are placeholders and will be improved)</u></b>

v3.1 is going to include a new terrain type in each region and some standard room changes to make use of them! I ended up getting a little carried away with this, and in the end each region is getting a new room type, changes/expansions to some existing rooms, and two new entrance/exit variants!

Firstly, here are some of the entirely new rooms that take advantage of the new terrain:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levelgen-1.png){: .rounded-large .align-center}

Next, here are some existing rooms that have been changed around a bit to include new terrain types:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levelgen-2.png){: .rounded-large .align-center}

Finally, here are some of the new entrance/exit variants. Some are similar to old ones, but I’ve added a few new ones focused on enclosed starting spaces.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levelgen-3.png){: .rounded-large .align-center}

Overall I ended up taking longer making these changes than I initially expected (at first it was just going to be the new terrain), but I'm pretty happy with the result. In particular, with these additions the typical empty rooms that were near universal a few years ago are now entirely gone!

## Other Changes and Additions

The Warrior changes and levelgen expansion are the biggest parts of v3.1, but there's a nice assortment of smaller things too:

v3.1 includes one new item: the **Ferret Tuft!** The tuft is a simpler evasion-boosting trinket with more of a cute aesthetic. It boosts evasion for you and for enemies, but there are lots of ways to counter enemy evasion, so use wands or go for those surprise attacks! The tuft is a little reference to a favorite ferret.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ferret-tuft.png){: .align-center}

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/badges.png){: .align-left}
There are also **Four New Badges**, that range in difficulty from gold-tier to diamond-tier. They're all focused on specific accomplishments, and I expect the two hardest badges to be quite tricky to earn.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/exile.png){: .align-left}
There are **Two New Rare Enemies**, both of which can spawn in the sewers. Gnoll exiles have extra loot, are very tough, and also non-aggressive. Hermit Crabs have substantially boosted defense but reduced movement speed.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/cleric.png){: .align-left}
I'm also making some **Cleric Balance Changes** based on gameplay data from v3.1. The Cleric is a bit on the weaker side currently, but not nearly as much as I thought they might be, so I mostly did targeted buffs to various abilities.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/score.png){: .align-left}
I've also made some adjustments to how score is calculated. Rather than exploration score being all or nothing for each floor, it's now instead reduced to 50%/20%/0% if 1/2/3+ rooms are left uncleared. To compensate, quest score is getting a little harder, with ways to lose points just like when fighting bosses.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/misc.png){: .align-left}
Lastly, there's the usual assortment of **Miscellaneous Changes and Bug Fixes** too. In total v3.1 has over 40 of them, including some small improvements for colorblind users, better custom note functionality for items, and hints for unseen items on the catalog.
</div>

---

I expect this beta to last for about one to one and a half weeks. If you'd like more frequent incremental updates on Shattered's development, you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/29719394), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/games/1769170/announcements/detail/542231678008951217)!