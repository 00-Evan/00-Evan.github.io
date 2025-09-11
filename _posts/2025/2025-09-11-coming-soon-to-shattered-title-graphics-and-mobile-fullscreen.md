---
title: "Coming Soon to Shattered: Title Graphics and Mobile Fullscreen!"
excerpt: "Hey Dungeoneers, I'm still releasing patches for v3.2, and as a rare surprise, this one's big enough to get a little blog post! In this blog post I'm going to go over what I've been doing in v3.2's patches, and what's coming in v3.2.4 in particular!"

header:
  image: /assets/images/2025/2025-09-11/header.jpg
  teaser: /assets/images/2025/2025-09-11/header-small.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#TODO warrior seal sprite?
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: DISPLAY_LAND"]
---

Hey Dungeoneers, I'm still releasing patches for v3.2, and as a rare surprise, this one's big enough to get a little blog post!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v3.2.4 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/) or [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon) via their beta branches<br>(This beta will be quick, it will release everywhere soon)
</div>

In this blog post I'm going to go over what I've been doing in v3.2's patches, and what's coming in v3.2.4 in particular!

## New Title Background Art!

Shattered has gotten some new title graphics recently, but that isn't the only thing Aleks and I have been working on. v3.2.4 will include a new background for the title screen as well!

{% include video id="sZ8QorSRAyo" provider="youtube" %}

The new title screen makes use of several layers of fully rendered chunks of dungeon, floating in front of a classic arch layer (also now fully rendered). It's meant to both extend the classis archs, and tie the title screens more directly to the region splash arts. This first release has objects that relate mostly to the sewers, but we have plans for new object sets for each of the other regions too!

This new title background will go everywhere the current archs go, and should react well to various screen sizes, from mobile portrait to ultrawide desktop displays. It has a lot of moving parts (both literally and in terms of code), and so I expect I'll be making little tweaks and refinements to it after launch. Let me know what you think!

## Mobile Layout Improvements

I'm modernizing various aspects of Shattered on mobile phones (now that I've dropped support for Android 4.0-4.4), and so I've been changing up how Shattered handles display cutouts (notches, hole punches, etc.) to let users play the game in true fullscreen! Currently the game just sticks black bars at the top, and the in-game UI looks like this: 

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/existing.png){: .align-center}

For most of the game's interfaces this is fairly easy, just keep the title lower and extend the background to the top. The in-game UI doesn't really have a background though. If I let the UI render up into display cutouts, it sorta works in some cases, but falls apart with larger cutouts like the iphone dynamic island:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/existing-island.png){: .align-center}

There isn't room to make this work on displays with larger notches (they'll still have a black bar, sorry!), but most modern hole punches leave a decent bit of room above and around, which has led me to this changed up UI for mobile users:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new.png){: .align-center}

A few elements have been moved around here:

- The XP bar has been moved to under the hero portrait, which both gives it a bit more screen space and lets the entire UI move a couple of pixels up.
- The version info has been moved to the top and the menu buttons brought down a bit, this prevents them from being cut off on rounded display corners.
- The boss HP bar and hero level have moved out of the way a bit, which gives the buff bar enough space to exist on two rows. It now dynamically skips spots that are obscured behind display cutouts.

This now lets Shattered render the UI all the way to the top on the majority of mobile devices! Here's how that looks with cutouts of varying size: (Galaxy S24, Pixel 9, and iPhone 16)

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-combined-vert.png){: .align-center}

This leads to a nice big fullscreen display for the majority of mobile phones! In lots of cases, with a black backdrop, the hole punch is hardly noticeable, even big ones like the dynamic island. Here's a typical earlygame scene on an iPhone 16 Plus:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/new-iphone-full.png){: .align-center}

I expect this change will take some getting used to, given that the majority of users have been used to a black bar for years. There are also literally hundreds of different phones with slightly varying cutout sizes, so I'm sure there will be a few hiccups here for some users as well. If you run into issues or otherwise have feedback on this change then please let me know!

---

There is no new text to be translated in v3.2.4 and the changes are pretty specific, so I expect the beta is going to be short, probably just a day or two. I do expect to do one or two more patches after v3.2.4 to fix any minor issues that crop up. Once all that's done I'll finally start moving on to v3.3 and a new city quest!

If you'd like more frequent incremental updates on Shattered's development (such as announcements for every patch release), you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/35775284), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/598537454201510456)!