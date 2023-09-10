---
title: "Coming Soon to Shattered: A New Quest! ...Eventually"
excerpt: "I've got some news to share about v2.2.0. The new caves quest isn't ready to show off yet, so in the meantime I am releasing the other content in v2.2.0 as an early beta!"

header:
  image: /assets/images/2023/2023-09-10/header.png
  teaser: /assets/images/2023/2023-09-10/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#452 = pickaxe sprite in v0.9.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 452"]
---

Hey Dungeoneers!

I've got some news to share about v2.2.0. The new caves quest isn't ready to show off yet, so in the meantime I am releasing the other content in v2.2.0 as an early beta!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>This early beta for Shattered v2.2.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id156312110) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via their beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

## Caves Quest When?

So, as mentioned above, the new caves quest isn't currently in the beta. This is due to a mixture of development taking longer than expected, and honestly August just ending up being a very busy month for me for a variety of personal reasons. This has put development significantly behind the ETA I previously gave of 'beta sometime in late July or August'.

Although the new quest isn't playable yet, I have made a lot of incremental progress since the last blog post.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/levels.png){: .align-center .rounded-large}

Firstly, I've made some big improvements to the generation of the mining level since v2.1.3's tester area, as you can see above (old on left, new on right). Levels are now more random seeming, but are actually more consistent under the hood. As an example, while some rooms are still secret, they are now guaranteed to be adjacent to regular rooms. Gold is also now generated in more consistent patterns, creating larger chunks overall, and guaranteeing that the overall quantity of gold falls within a specific range.

There is still work to do though. Gold tends to cluster a bit too much currently, and I worry that these levels are currently a bit on the large side. They also seem pretty empty, mostly because of all the content that isn't quite done yet, including three different sets of hazards to place within these levels.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/quest-types.png){: .align-center .rounded-large}

While I'd like to keep the specifics a bit close to my chest for now, I've pretty solidly worked out three variants for the quest. Each variant will come with its own hazards, enemies, and boss encounter. You'll be tasked with mining though a cave filled with **ancient and fragile crystals**, **thick vegetation and aggressive fungi**, or **cave-ins and magic-wielding gnolls**.

I'll talk more about the new quest in another blog post, once it's closer to releasing. I'm afraid I'm not totally sure when that will be just yet.

## So What IS in the Beta?

The new quest is still going to come out with v2.2.0 when it fully releases, but v2.2.0 also includes a bunch of other smaller additions. I decided that it would be best to get a beta out now with all of the other content in v2.2.0, rather than just sitting on it while I finish v2.2.0's headline content.

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/music.png){: .align-left}
**Firstly, Shattered's soundtrack has doubled in size!** In total there is ~20 minutes of new music from Shattered's composer: [Kristjan Thomas Haaristo](https://www.youtube.com/channel/UCL1e7SgzSWbD_DQxB_5YcLA). This includes extensions to the game's regular region tracks, new 'intense' tracks that play during quests and ascension, and new 'finale' tracks that play towards the end of boss fights and the game overall.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/rot-room.png){: .align-left .rounded}
I've also taken some time to improve the game's two pre-caves quests. Prison quests now have a few new mechanics and overall have more consistent and engaging gameplay. Sewers quests are mostly unchanged, but I have made a few subtler tweaks to make both the ghost and quest bosses easier to find.
</div>

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ghost.gif){: .align-center .rounded-large}

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/challenges.png){: .align-left}
The Hostile Champions challenge is also getting some big changes to try and smooth out its difficulty spikes, which are a bit too extreme at the moment. Stronger champion types now have more counterplay options, and some of the weaker ones have received boosts as well.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/talents.png){: .align-left}
There have also been a few balance changes. Most notably, Dagger type weapons have a reworked ability that lets the Duelist blink to a location in addition to granting her brief invisibility. T2 potion and scroll talents now have slightly weaker effects, but trigger on any potion or any scroll instead of only on specific ones.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/misc.png){: .align-left}
And, of course, there are a bunch of smaller misc. changes and bugfixes. Most notably, shopkeepers will now warn you the first time they are attacked, the crystal path room has been redesigned to offer more choice, and sacrifice rooms should be less tedious in the earlygame.
</div>

## Social Media Changes

Firstly, I have decided to end my use of Twitter, Reddit, and Facebook as platforms to share news about Shattered Pixel Dungeon. This is both due to decisions these platforms have made recently, and also just being fed up with corporate, centralized, profit-driven social media in general.

I'll continue to post updates about my projects on [![](/assets/images/icons/patreon.png){: .rounded .text-inline}Patreon](https://www.patreon.com/ShatteredPixel), [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel), the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community](https://steamcommunity.com/app/1769170/allnews/), and will now also be posting on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon community over at Lemmy](https://lemmy.world/c/pixeldungeon)! I owe Shattered's early success to the Pixel Dungeon subreddit community, and so I really hope to see it continue to thrive over at Lemmy.

Lastly, I understand that not everyone wants to make another new account on another new website, so I'm also starting a [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)! You can subscribe to get emails about new blog posts, and optionally also get more frequent emails with smaller incremental updates.

---

I expect that I'll be fixing a few beta bugs over the next couple of days, and a little while after that I hope to finally get work finished on the caves quest. If you'd like smaller updates leading up to that, consider following me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel), or subscribing to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter). The beta itself should also get updated pretty quickly after the quest's content is ready.

<div markdown="1" class="img-text">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider supporting me on [![](/assets/images/icons/patreon.png){: .rounded .text-inline}Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/4803893), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3824174193423904768)!