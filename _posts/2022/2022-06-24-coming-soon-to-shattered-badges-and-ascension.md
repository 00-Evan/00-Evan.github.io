---
title: "Coming Soon to Shattered: Badges and Ascension!"
excerpt: "Greetings Dungeoneers! After some delays, v1.3.0 is finally ready to go to beta! In this post I'm going to detail some more of the new content coming to Shattered, with an emphasis on the challenging content additions coming in in v1.3.0!"

header:
  image: /assets/images/2022/2022-06-24/header.png
  teaser: /assets/images/2022/2022-06-24/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: BADGES"]
---

Greetings Dungeoneers! After some delays, v1.3.0 is finally ready to go to beta!

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
[![](/assets/images/SHPD-icon-2021.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) The beta for v1.3.0 is live right now! You can get it on Google Play by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon), on Apple devices by signing up on [TestFlight](https://testflight.apple.com/join/4PWFyask), on Steam by [selecting the Beta branch from the game's properties](steam://nav/games/details/1769170), or directly download the game for Android and Desktop via [Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases/).
</div>

In this post I'm going to detail some more of the new content coming to Shattered, with an emphasis on the challenging content additions coming in in v1.3.0!

## New Badges and High Scores

Firstly, v1.3.0 includes 15 new or totally reworked badges! A few are fairly straightforward, but several of them are focused on giving experneced players something to sink their teeth into!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-badges.png){: .align-center}

- The first row contains some new or heavily reworked 'cause of death' badges that are a little harder to get than the bronze ones. Most of them involve death by some special magical means, such as to your own item or to a grim trap!
- The second row are badges for earning a score of 5k, 25k, 100k, 250k, and a whopping 1 million in a single game. They run the gamut from easy to extremely hard, with 5k being achievable by Goo and 1 million probably being the new hardest badge in the game.
- The final row is a set of new boss challenge badges! They are all harder than fighting the boss normally, and keep ramping up as they progress. For the final one you'll need to win with all four demon spawners alive AND the badder bosses challenge enabled!

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/score.png){: .align-center}

I'm also adding a score breakdown page for players who want more incremental tracking of their performance in a particular game. This page shows how you did on each component of the run, and what multipliers were applied for winning or enabling challenges. For more details on what each score component means, take a look at [last month's blog post.](/blog/coming-soon-to-shattered-seeded-runs.html)

## Ascension

For a while now the game's ascension route has been pretty trivially easy. After getting out of the demon halls enemies start getting weak, and it becomes more of a test of patience than anything. I want to ramp up ascension difficulty, make it impossible to just run away back to floor 1, but also not make the player feel like they're just forced into fighting waves of enemies arbitrarily.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/amulet.png){: .align-center .rounded-large}

To accomplish this, I'm adding a few limitations to the game when the player starts their ascent. They won't be able to teleport back up a bunch of floors to quickly escape, and there will be a steadily increasing debuff that can only be lessened by defeating enemies. The debuff's effects range from subtly drawing enemies to you, to basically forcing you into combat.

The enemies themselves are also getting tougher. Each enemy will get a multiplier to their effective health, armor, accuracy, evasion, and damage. This multiplier is on a per-enemy basis, ranging from no changes for scorpios and eyes, to 2.25x for gnoll brutes, to a whopping 10x for rats! The goal in terms of enemy strength is to keep difficulty relatively consistent during the ascent, with it eventually falling off a bit as they player gets close to floor 1.

Ideally this will turn the ascent into a proper gauntlet that feels like it encourages the player to keep moving and picking their fights. It will only outright force combat if the player is very consistently trying to avoid enemies. As a reward, players who make it to the surface will find that they get a 2.5x score bonus, rather than the usual 2x for winning.

## Other Changes

v1.3.0 also has a bunch of other changes both big and small, it's probably ended up being the largest variety update I've ever done. In no particular order, here's a quick summary of a few other things coming that I haven't mentioned yet:

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dailies.png){: .align-left}
[Last blog post](/blog/coming-soon-to-shattered-seeded-runs.html) covered seeds extensively, and I've now fully implemented dailies as well! Every night at mightnight UTC another daily becomes available, and the game keeps a full history of all your daily scores. At some point in the future I might like to add online leaderboard functionality.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/changed-badges.png){: .align-left}
I'm also making several badge adjustments in addition to the new badges in v1.3! Unlocking the huntress is getting a bit easier, grandmaster treasure hunter and monster hunter are being made harder, several gold badges are being promoted to platinum tier, and the dungeoneer badges are becoming a bit less grindy.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/cleansing-dart.png){: .align-left}
v1.3 also has a higher than usual number of balance tweaks. Several curses are getting changes to make them less frustrating, including the complete removal of fragile and exhausting. Armor abilities are getting a variety of buffs and a few nerfs as well. Lastly, woolly bombs and some of the more helpful darts are getting new effects to make their usage less niche.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ui.png){: .align-left}
I'm also making some improvements to various interfaces in v1.3.0. The settings menu is getting expanded with some new options for keyboard and controller users and I've added a new 'quickslot swapper' for mobile users! I plan to implement a little more here before the beta is finished, including radial controller menus and more enemy info in the top left of the full UI.
</div>

---

With the little bit of remaining UI work, I expect this beta is going to last a bit longer than the usual timeframe of one week. Look forward to v1.3.0's full release in early July!

<div markdown="1" style="display: inline-block;">
[![](/assets/images/patreon-icon-2021.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/reddit-icon.png){: .rounded .text-inline} Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/vjvkbp/), or on the [![](/assets/images/steam-icon.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3415432674392137853)!