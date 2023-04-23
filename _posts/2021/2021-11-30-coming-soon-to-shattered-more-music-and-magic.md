---
title: "Coming Soon to Shattered: More Music and Magic!"
excerpt: "Hey Dungeoneers, v1.1.0 is finally ready for beta! Now that v1.1.0 is content complete, I'm going to share some more details about the game content changes coming in it. This includes more reworked and new alchemy items, more details about how energy works, and info on some new music!"

header:
  image: /assets/images/2021/2021-11-30/header.png
  teaser: /assets/images/2021/2021-11-30/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#261 = Toolkit item sprite in v0.9.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 245"]
---

Hey Dungeoneers, v1.1.0 is finally ready for beta!

Now that v1.1.0 is content complete, I'm going to share some more details about the game content changes coming in it. This includes more reworked and new alchemy items, more details about how energy works, and info on some new music!

<div markdown="1"  style="display: inline-block; margin-bottom: 1.3em;">
[![](/assets/images/icons/SHPD.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) The beta for v1.1.0 is live right now! You can get it on Google Play by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon), on Apple devices by signing up on [TestFlight](https://testflight.apple.com/join/4PWFyask), or directly download the game for Android and Desktop via [Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases/). Note that the TestFlight release is currently awaiting approval from Apple, but it should be available soon.
</div>

Also, apologies for the continued delays on this update. At the moment I'm juggling a lot of extra responsibilities (both Shattered and real-life), and so have had less time to work on v1.1.0 than I would like over the last two months. Things are starting to clear up now though, but I don't think I'll be back up to full speed until the new year.

## Regional Music!

Before getting into more content changes though, there's new music! In v1.1.0 Shattered gains a track for each of its five regions, with the existing in-game track being used for the sewers. I'll let the music itself do most of the talking, feel free to let this run while you read the rest of the blog: 

{% include video id="GJk21Yrdxmk" provider="youtube" %}

As before, these tracks were composed by [Kristjan Thomas Haaristo](https://www.youtube.com/channel/UCL1e7SgzSWbD_DQxB_5YcLA), and feature some dynamic playback functionality in the game to reduce repetitiveness. With this addition Shattered now actually has a proper soundtrack, but hopefully there'll still be a more music to come!

## Energy and the Toolkit

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/alchemy-ui.png){: .align-right .rounded-large} I talked quite a bit about energy in the [previous blog](/blog/coming-soon-to-shattered-better-alchemical-energy.html), so I've got more of a quick update here. As mentioned in that blog, energy is becoming a more important part of the alchemy system that the player generates by scrapping consumable items.

I've done more iterations on how this changes the **alchemy interface**, and have decided to keep things more similar to the way they are currently. Based on feedback from the last blog I also decided to have a dedicated 'add energy' button at the bottom, instead of having energy creation be another recipe.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/inventory-ui.png){: .align-left} One big change from the last blog is that I've decided that **energy will become a resource like gold**. This means that the player will carry around all the energy they find/generate, just like how they carry around gold. This should make energy production and use much more flexible.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/toolkit.png){: .align-left } 
Finally, all of this serves as an indirect rework to the **Alchemist's Toolkit**. While the toolkit's core function hasn't changed, energy is much more valuable now. I've also taken the opportunity to improve the toolkit's flexibility a little too. It can now be used near enemies, warms up faster at higher levels, and can be levelled up anywhere.
</div>

## New Spells!

While the focus of v1.1.0 is mainly on improving existing alchemy content, there was room for me to add a few new spells as well:

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/alchemize.png){: .align-left } 
Firstly, while **Alchemize** is a spell that already exists, its functionality is getting a complete rework due to the other alchemy changes. The spell now lets the player convert an item into energy or gold anywhere in the dungeon. My hope is that this can substantially help with inventory management. A few uses of alchemize will also be sold in shops, replacing the merchant's beacon.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/summon.png){: .align-left } 
**Summon Elemental** is a new spell that gives an alternate use to elemental embers from the wandmaker's quest. It's made from elemental embers, an arcane catalyst, and a larger amount of alchemical energy. The spell can be used to summon a friendly elemental to fight with you, and can also be powered up by using items elementals normally drop.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tele.png){: .align-left } 
**Telekinetic Grab** is a new spell that I hope will improve the flexibility of thrown weapons. It's made from liquid metal, an arcane catalyst, and a smaller amount of alchemical energy. Players can use this spell to remotely grab items from the ground, or remotely reclaim thrown weapons that are stuck to enemies!
</div>

## More Exotic Changes

Finally, there are a few more reworks to exotic potions and scrolls that I didn't cover in the last blog:

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/divine.png){: .align-left} **Holy Furor** is turning into **Divine Inspiration**. This potion ties into the talent aspect of levelling up, by giving you two bonus talent points! These points can be spent on any tier, allowing you to invest in more talents than normally possible.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mastery.png){: .align-left}
**Adrenaline Surge** is being reworked into **Mastery**. This new potion doesn't give you any strength, but instead reduces the strength requirement if any item by 2! This is still limited like adrenaline surge was, but should be much less temporary.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/siren.png){: .align-left}
**Affection** is being reworked into **Siren's Song**. This scroll has a more powerful single target effect, permanently turning one enemy into an ally! The scroll will also still briefly charm other enemies.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/metamorph.png){: .align-left}
**Polymorph** is being reworked into **Metamorphosis**. Rather than transmuting items or enemies, this one works on the hero themselves! You can select any class-based talent and swap it with an equivalent talent from another class!
</div>

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, and recently started getting access to early playtests of content updates!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/r5y82z/)