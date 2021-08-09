---
title: "Coming Soon to Shattered: Music, Metal, & More!"
excerpt: "v0.9.4 contains a bunch of smaller content additions and changes, but some of them are still pretty significant. There's remastered music, some new alchemy recipies, an improved tutorial, and a bunch of smaller tweaks and addition!"

header:
  image: /assets/images/2021/2021-08-09/header.png
  teaser: /assets/images/2021/2021-08-09/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: MUSIC"]
---

Hey Dungeoneers, apologies for the slight delay, but v0.9.4 is now ready for beta!

v0.9.4 contains a bunch of smaller content additions and changes, but some of them are still pretty significant. There's remastered music, some new alchemy recipies, an improved tutorial, and a bunch of smaller tweaks and addition!

While they're not about game content, you can also take a look at these two posts for some more info on v0.9.4:
- [Shattered Pixel Dungeon is coming to iOS!](/blog/shattered-pixel-dungeon-is-coming-to-ios.html)
- [Saying Goodbye to Android 2.3 Gingerbread](/blog/saying-goodbye-to-android-2.3-gingerbread.html)

## Remastered Music

As the most significant game change this update, Shattered is getting some remastered music!

{% include video id="FdwfFsQ3VqY" provider="youtube" %}

These remasters were both made by [Kristjan Thomas Haaristo](https://www.youtube.com/channel/UCL1e7SgzSWbD_DQxB_5YcLA), and I'm already working with him on a track for each region as well! For the title theme we went with a more instrumental feel compared to the original, and blended instrumental and synthetic sounds for the new sewers track. The result is a little different than the original tracks, but I'd say it's quite a large improvement! Expect to hear more new music in future updates!

There's also some interesting stuff going on at a technical level, the sewers track is actually split into two parts! The game plays the shorter lead-in part once, and then the longer main part either one or two times before looping back. The idea here is to reduce the repetitiveness of the game's tracks while still keeping the runtime small enough to fit on older phones.

## Liquid Metal and Arcane Resin

While I'm not making big design changes to alchemy just yet, there are two new important recipes being added! Both of these recipes are focused on giving the player ways to recycle excess thrown weapons and wands, instead of them feeling forced to use or sell them. This ties into continuing to improve inventory management, and also is an attempt to help reduce quickslot demand a little. Theyre also both alchemy recipes that help recycle items you don't want into ones that you do, which is something I want the system to focus on more.

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/liquid-metal.png){: .align-left}
The first new alchemy item is **Liquid Metal**, which is created using thrown weapons. Liquid metal is then used to repair other thrown weapons! Each weapon generates enough metal to fully repair another weapon of the same tier and level. Of course you can use low tier weapons to repair high tier weapons too, but you'll need more of them to get a full repair.
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/arcane-resin.png){: .align-left}
The second alchemy item is **Arcane Resin**, which is created from a wand. Wands are pretty valuable, so resin is more potent than liquid metal, it gives upgrades! One wand creates enough resin to upgrade two wands of the same level. However, resin upgrades don't stack with scrolls of upgrade and only work up to +3, so they are mainly useful for sidearm wands.
</div>

## Smaller Additions

v0.9.4 also includes a variety of other smaller content additions and changes:

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tome.png){: .align-left}
To go along with the release on iOS, I'm making some changes to the game's tutorial. The basic structure is the same, but the tutorial should be a lot more punctual with its advice now, as some pages are highlighted right when the player needs their advice. The guidebook is also now called the "Tome of Dungeon Mastery", as a nod to the recently removed tome of mastery.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trap.png){: .align-left}
I've also added two new traps, which both have bigger opportunities to be useful to the player. **Geyser traps** create a great plume of water when activated, knocking back anything nearby and turning the surrounding terrain to water. **Gateway Traps** act like teleportation traps, but never expire and always teleport to the same location.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/wraith.png){: .align-left}
There's also a new rare enemy: **Spectral Necromancers!** These necromancers don't create a single skeleton, and instead prefer to make a bunch of disposable wraiths. Killing them quickly is important to avoid getting overwhelmed, but as a reward you'll get a guaranteed scroll of remove curse!
</div>

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) Both the new traps and spectral necromancers are happening thanks to some content polls on Patreon! If you'd like to vote in polls that help shape future content, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons also get access to weekly mini-blogs and an exclusive Discord server.

## Balance Changes

Lastly, there are some pretty significant balance changes coming in v0.9.4 too:

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ankh.png){: .align-left}
Way back in v0.1.1 I added the blessing mechanic to make ankhs more worthwhile, and now I'm finally giving some love to unblessed ankhs as well. They will now give you a chance to reclaim your entire inventory, if you can fight your way back to it Dark Souls style! Blessed ankhs have received a smaller buff as well, to ensure they're still clearly worth using.
</div>

<div markdown="1" style="display: inline-block; margin-bottom: 1.3em;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/runestones.png){: .align-left}
As a precursor to larger alchemy changes, I've changed scrolls to always produce 2 runestones, and handed out compensation buffs to the stones that used to be made in quantities of 3. This ranges from intuition stones giving a second guess if your first was correct, to stones of flock getting a bigger AOE, to a couple stones getting entirely new mechanics!
</div>

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/crown.png){: .align-left}
Finally, I've done a balancing pass on the new talents and abilities added in v0.9.3. These are mostly numbers adjustments, focused on making some talents and abilities more worthwhile versus others. There have been a few nerfs though, as a couple of abilities were doing a little better than I wanted.
</div>

---

[![](/assets/images/SHPD-icon-2021.png){: .align-left}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) The beta for v0.9.4 is live right now on [Google Play](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon) and [Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases/), and it should release on [iOS TestFlight](https://testflight.apple.com/join/4PWFyask) very soon. I expect to fully release v0.9.4 on **Tuesday August 17th**. A pre-order page should appear for Shattered the iOS App Store soon, follow me on [Twitter](https://twitter.com/ShatteredPixel) if you'd like to know when that pops up.

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/p1d1rc/)