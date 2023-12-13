---
title: "Coming Soon to Shattered: The Gnoll Caves Quest!"
excerpt: "The second variant of the new caves quest is now ready for beta! In this post I'm going to go over what this new quest area entails, and also share some other content coming in v2.3.0."

header:
  image: /assets/images/2023/2023-12-13/header.png
  teaser: /assets/images/2023/2023-12-13/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: sprites/brute.png, 0, 0, 12, 15", "SHPD_ICON_v756: sprites/gnoll_guard.png, 0, 0, 12, 16"]
---

Hey Dungeoneers!

The second variant of the new caves quest is now ready for beta! In this post I'm going to go over what this new quest area entails, and also share some other content coming in v2.3.0.

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>This beta for Shattered v2.3.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id156312110) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via their beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

## The Gnoll Mining Area

To quickly recap, the mining area is a special level that's only accessible during the new caves quest, where the player can dig through walls! Making your own terrain opens up interesting strategic opportunities, and lets the quest area have a much more free-form shape compared to regular floors. The existing quest variant, added in v2.2.0, tasks the player with tunneling through a cave filled with fragile crystals.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/crystal-area.png){: .align-center .rounded-large}

The new gnoll variant has different terrain which is quite a bit less fragile. These gnolls have been using some pretty chaotic earth-moving magic to get at the gold in the area, resulting in lots of boulders and cave-ins. Unlike the crystal quest, where rooms were mostly connected to each other, rooms in the gnoll caves quest will mostly be closed off from each-other. Not to worry though, there are plenty of environmental hints that can point you in the right direction.

(<b><u>Please note that the following pictures use unfinished visuals.</u></b> Obviously this new area isn't going to be as shiny as the crystal caves, but there are some visual improvements I'd like to make before full release.)

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gnoll-area.png){: .align-center .rounded-large}

The core ingredients of the quest area are otherwise the same: you'll need to collect 40 gold, there are one or two secret rooms, three larger rooms with tougher enemies, and one giant room with a boss!

## Gnoll Enemies

The gnoll caves quest has three unique enemies:

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gnoll-guard.png){: .align-left}
The first and most common enemy in this region is the **Gnoll Guard**. Guards are weaker than brutes overall, but have extra attack range thanks to their spears. They also deal heavy bonus damage if they can attack you at a distance. The best way to fight them is to try and force them into close-up combat, as they have trouble attacking around terrain like walls and boulders.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gnoll-sapper.png){: .align-left}
Next up are **Gnoll Sappers**, which have a variety of disruptive and supportive tools granted to them by the area's boss. They aren't especially proficient with them, but still pose a notable threat. Each sapper also comes with an accompanying guard, and you'll want to try and use the sapper's abilities to your advantage to get the upper hand.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/gnoll-geomancer.png){: .align-left}
Finally, the region boss is the **Gnoll Geomancer**. Unlike sappers, the geomancer is very proficient with rock-based magic, so expect to do a lot of fancy footwork or you'll be taking a boulder to the face. The fight plays out a bit like Tengu's fight, with the geomancer jumping away from you while hurling various rocky attacks. The geomancer will also conscript any living gnoll sappers to help it, so you probably want to clear the cave out before starting the geomancer fight.
</div>

## v2.3.0 Side Content

As always, v2.3.0 is going to include some side content as well! This time around I've tried to focus on little additions that were fairly easy to implement:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/remains-items.png){: .align-center}

- Firstly, hero's remains now contain an extra unique consumable that's themed after the hero who died. These items replace the old boring 50 or 10 gold remains drop, and will also appear in conjunction with regular remains loot if the game selected any. You can use these items for a small benefit, or hold onto them earn some new badges.
- Next, Shattered has had little holiday food items that temporarily replace cornish pasties ever since 2016, but only for Halloween and the Winter Holidays. I'm finally expanding that for 2024, so keep an eye out for something for Lunar New Year in early February, and for Easter in late March to early April. I'll be adding more of these throughout the year too.
- Lastly, I'm adding new icons to the various numbers that indicate damage, positive effects, and currency gain. These icons make these text popups much cleaner and make it more clear where damage or healing effects are coming from. I've also taken the opportunity to add a bunch of text popups for various healing and shielding effects.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/damage-text.gif){: .align-center .rounded-large}

---

I'm not too certain how long the beta for v2.3.0 will last, as there's still one more quest variant to implement before the caves quest as a whole is complete. I'm going to spend a bit of time working on that, and depending on how smoothly development of the final variant goes I'll either include it as a part of v2.3.0 or put it off until later in favor of getting v2.3.0 fully released sooner. If you'd like to keep up to date on that, you can subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter), or follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel).

<div markdown="1" class="img-text">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider supporting me on [![](/assets/images/icons/patreon.png){: .rounded .text-inline}Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/9526317), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/4035852164013984780)!