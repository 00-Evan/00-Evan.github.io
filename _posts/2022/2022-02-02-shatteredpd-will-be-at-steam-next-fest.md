---
title: "ShatteredPD will be at Steam Next Fest!"
excerpt: "Hey Dungeoneers, I've got some news to share on the Steam release! Development has been progressing well, and Shattered Pixel Dungeon will be participating in Steam Next Fest, running from Feburary 21st to 28th. During this time there will be a free demo of the game, letting people try the desktop version out before it fully releases with v1.2.0."

header:
  image: /assets/images/2022/2022-02-02/header.png
  teaser: /assets/images/2022/2022-02-02/header-small.jpg
  width: 1260px

gallery:
  - url: /assets/images/2022/2022-02-02/interface-1.png
    image_path: /assets/images/2022/2022-02-02/interface-1.png
    alt: "Regular Inventory View"
    title: "Regular Inventory View"
  - url: /assets/images/2022/2022-02-02/interface-2.png
    image_path: /assets/images/2022/2022-02-02/interface-2.png
    alt: "Selecting the Staff"
    title: "Selecting the Staff"
  - url: /assets/images/2022/2022-02-02/interface-3.png
    image_path: /assets/images/2022/2022-02-02/interface-3.png
    alt: "Choosing a Wand to Imbue"
    title: "Choosing a Wand to Imbue"

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: DISPLAY"]
---

Hey Dungeoneers, I've got some news to share on the Steam release!

Development has been progressing well, and Shattered Pixel Dungeon will be participating in [Steam Next Fest](https://store.steampowered.com/sale/nextfest), running from **Feburary 21st to 28th**. During this time there will be a free demo of the game, letting people try the desktop version out before it fully releases with v1.2.0.

## Demo Details

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/steam-demo.png){: .align-center .rounded-large }

The demo will feature all game content until the end of floor 10. Descending after floor 10 will redirect players to a screen congratulating them for completing the demo. Demo runs can still be continued from just before the moment the player descends and will carry over to the full game.

The demo will be available a bit before Next Fest on **February 9th at noon EST**, and will stay up until the game fully releases on Steam. It's worth noting that I would have preferred to make the game free for everyone on Steam for a limited time (like with the iOS release), but having a demo is required for participation in Next Fest.

In addition to the existing game content, the demo will also provide a first look at several of the Desktop enhancements I have planned!

## Desktop Enhancement Progress

As I mentioned [in October](/blog/shattered-pixel-dungeon-is-coming-to-steam.html#new-pc-features), there are a variety of features I want to implement before fully launching the game on Steam. I've had some time to work on those now, so let's see where we're at!

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/executables.png){: .align-left .rounded-large}
Firstly, I have fully implemented **Native Executables** for Windows, MacOS, and Linux/SteamOS. This means the game can now be downloaded and run through Steam without the user having to install Java. I'm also going to be working on implementing some platform-specific installers (.msi, .dmg, or .deb) for direct download users. The .jar build will still be available as well.
</div>

Getting the game to run via Steam is only the first step though, I'm also almost finished implementing **An Interface for Larger Displays**. I shared a concept of this in October, which has now been fully implemented plus some refinements. The inventory panel has a more streamlined appearance, and some windows and other game interaction are now centered on it as well. Take a look (click or tap to enlarge each image):


<center>{% include gallery caption="The new full interface at 1080p, 4x zoom. These images show the player selecting their staff, and then selecting to imbue a wand in it. Everything happens in one place on the main UI!" %}</center>

---

While these additions are enough to show the game off as a demo, there are some other things I'd like to try and get done before or during Next Fest as well: (note that these pictures are mockups and subject to change)

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/quickslots.png){: .align-left }
There's some obvious space to add **more quickslots** in this larger UI. Players have been asking for more slots for a while, and while I'm still unsure about adding a whole bunch, it would not be hard to bring the slot number up to 6 or so, assuming I can make them fit on mobile as well.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/right-click.png){: .align-left }
Another major thing I'd like to add is **better mouse functionality**, such as hover tooltips and right-click menus. In particular I think this could work extremely well with the new on-screen inventory. The player would be able to right click and select an action for their items, rather than having to open the full item window. This would also make game environment actions like examining much easier to do.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/enemy-info.png){: .align-left }
There's also a nice empty corner at the top-left of the screen where I might add some **more enemy info**. This info would essentially be a summary of the details normally shown when examining an enemy, including a health bar and active buffs/debuffs. Each enemy in view would have its own little info pane. This would replace the little enemy indicator at the top right, and possibly also the boss health bar.
</div>

I would like to work on some steamworks integration (cloud sync, achievements, etc) for the game as well, but that will likely happen after Next Fest. I also haven't forgotten about improvements like better keyboard and controller support, but I think it's more likely those improvements will be worked on after the game initially releases on Steam.

## After Next Fest

Once I wrap up all the changes I want to do for Next Fest I'm going to start working on the actual game content additions I have planned for v1.2.0. As a quick reminder, v1.2.0 is going to include a variety of smaller content changes and additions:
* Balance adjustments to alchemy recipies following the changes in v1.1.0
* A redesign to the Master Thieves' Armband to make it useful outside of shops
* Various levelgen improvements, mostly focused around special rooms
* New music for Yog-Dzewa, and probably music for each other boss as well
* Various smaller tweaks, fixes, and improvements as usual

I'll make another blog post with more details on these closer to the release of v1.2.0.

I'd like to tentatively put the release of v1.2.0, and of Shattered on Steam, in the **first half of March**. The Steam version will cost $10 (though I might do a launch sale), and will include all the features of the mobile version plus the enhancements I've been working on. It will also include some supporter benefits, just like the iOS version. Moving forward the Steam version will get free updates in lockstep with the Android and iOS releases.

If you haven't already, please consider [wishlisting the game on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), and give the demo a try when it releases next week, or during Next Fest!

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, and recently started getting access to early playtests of content updates!

You can discuss this blog post on the [Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/sj1tqf/), or on the [Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3185736218666470824/)!