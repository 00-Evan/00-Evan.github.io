---
title: "Shattered Pixel Dungeon is Coming to Steam!"
excerpt: "Hey Dungeoneers, I've got some more exciting news, Shattered Pixel Dungeon is coming to Steam in early 2022! I'm moving so quickly on this due to a mix of the game's success on the iOS App Store, and a promotion from Roguelike celebration 2021!"

header:
  image: /assets/images/2021/2021-10-15/header.png
  teaser: /assets/images/2021/2021-10-15/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#63/#61 = Amulet of Yendor item sprite in v0.9.0/v0.9.3
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 63", "SHPD_ICON_v533: ITEM: 61"]
---

Hey Dungeoneers, I've got some more exciting news, **Shattered Pixel Dungeon is coming to Steam in early 2022!** I'm moving so quickly on this due to a mix of the game's success on the iOS App Store, and a promotion from [![](/assets/images/roguelike-celebration.png){: .rounded .text-inline} Roguelike celebration 2021!](https://roguelike.club/)

<div markdown="1" style="display: inline-block;">
[![](/assets/images/roguelike-celebration.png){: .align-left .rounded}](https://roguelike.club/) As I mentioned in the last blog, I'll be giving a presentation at Roguelike Celebration 2021 tomorrow, titled "Community-Driven Roguelike Development", you can find more details about it [Here](https://roguelike.club/speakers2021.html#evan-debenham). Roguelike Celebration will also be running an [event on Steam this week](https://store.steampowered.com/sale/roguelikecelebration2021), which Shattered is a part of!
</div>

<div markdown="1" style="display: inline-block; width: 100%">
<p style="margin: 0px"><a href="https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/"><img src="/assets/images/2021/2021-10-15/steam-small.png" alt="" class="align-right rounded-large"></a></p>

While the game won't release for another few months, it already has a [page on Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/)! If you have any interest in the Steam version of the game at all, please considering adding it to your Steam wishlist. The game will be paid on Steam just like on the App Store, costing $10 US when it releases.

Just like with iOS, I want to give PC users a first-class experience. This requires some more direct changes than iOS though, as user-interaction is fundamentally different on PCs. I want the game to play just as well on big desktop screens as it does on tiny phone ones, and that means I can't just scale up the game's current mobile UI. Because of this, I have a bunch of plans for improvements to make before release. I hope to get most of all of them done in time for a release in early 2022.
</div>

## New PC Features

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/executables.png){: .align-left}
Firstly, the most fundamental change is **Native Executables** for Windows, MacOS, and Linux. Currently the game requires the user to install Java on their computer, but there are ways for me to bundle Java with the game which allow it to be run/installed like a normal program. This is pretty crucial, so I plan to have this implemented with the release of v1.1.0.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/main-ui.png){: .align-left}
After v1.1.0, I'm going to start working on several **Core Interface Improvements**, which take advantage of the extra real-estate of full-size computer displays. In addition to shifting some elements around, the most important thing I think will be to **move the inventory into the main UI.** This will allow the player to do all inventory-based interaction right from the main interface, instead of having to constantly open a window.

<figure>
  <a href="/assets/images/2021/2021-10-15/PC-UI.png" title="" class="align-center text-center">
    <img src="/assets/images/2021/2021-10-15/PC-UI.png" alt="" class="align-center rounded-large">
    <figcaption>
      Here's an early draft of what this UI might look like at a standard 1080p resolution (press on the image to zoom in).<br>The mobile UI will remain as an option, for those who prefer a minimal interface.
    </figcaption>
  </a>
</figure>

I have plans for other UI improvements as well. The extra space means that **quickslots could be replaced with a hotbar**. This would mean that an entire keyboard row (number keys) could be dedicated to game and item actions. The hotbar would at least work for items, but it's possible I could extend its functionality to game actions as well.

Additionally, there is empty space at the top-left which could be used for **more detailed enemy info**. This info would essentially be a summary of the details normally shown when examining an enemy, including a health bar and active buffs/debuffs. Each enemy in view would have its own little info pane.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mouse.png){: .align-left}
I also want to look into providing **Better Mouse Functionality**, such as hover text and right-click menus. Hover functionality could let the game display helpful contextual tooltips, and right-click menus could be used to quickly select all sorts of game actions, such as examining something or dropping/throwing/using an item.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/controller.png){: .align-left}
And lastly I'd like to look into **Better Keyboard and Controller Support**. The game currently has some keyboard support and basically no controller support, many interfaces cannot be used without a mouse. I would start with partial controller support, like binding game actions to buttons, but eventually I'd like the game to be fully playable without a mouse or touchscreen.
</div>

## Other Plans

<div markdown="1" style="display: inline-block; width: 100%">
[![](/assets/images/SHPD-icon-2021.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases) As a reminder, if you'd like to play the PC version as it is currently (a straight mobile port + keyboard bindings), it's available right now on [Github!](https://github.com/00-Evan/shattered-pixel-dungeon/releases) I also plan to be releasing the game on Itch.io soon under a 'pay what you want' model, with $10 as the suggested amount. These versions of the game will also get the improvements I've mentioned above.
</div>

Once Roguelike Celebration is over I'm going to be getting back to work on v1.1.0, including those alchemy changes I mentioned [last time](/blog/coming-soon-to-shattered-better-alchemical-energy.html). You can expect another full post about v1.1.0 sometime in November, but until then you can follow me on [![](/assets/images/twitter-icon.png){: .rounded .text-inline} Twitter](https://www.twitter.com/ShatteredPixel) for smaller updates and some animated gifs.

My plans for updates after v1.1.0 are still not locked in, but there are some exciting things coming, especially once I've gotten PC porting work out of the way. We're getting closer to 2022 so expect a big blog on it then, just like the yearly posts I've made in [2021](/blog/shattered-pixel-dungeon-in-2021.html), [2020](/blog/shattered-pixel-dungeon-in-2020.html), and [2019](/blog/shattered-pixel-dungeon-in-2019.html). It looks like we're going to get through about half of the items listed in the 2021 post by 2022.

---

[![](/assets/images/patreon-icon-2021.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, and recently started getting access to early playtests of content updates!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/q8twh1/)