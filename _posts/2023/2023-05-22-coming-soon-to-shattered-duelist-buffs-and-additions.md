---
title: "Coming Soon to Shattered: Duelist Buffs and Additions!"
excerpt: "Hey Dungeoneers, it's time for another beta release! In this blog post I'm going to go over the bulk of the changes coming in v2.1.0, including a bit of new content and a bunch of Duelist balance! I expect the beta for v2.1.0 to last slightly longer than a week."

header:
  image: /assets/images/2023/2023-05-22/header.png
  teaser: /assets/images/2023/2023-05-22/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#123 = runic blade sprite in v0.9.0+
#99 = rapier sprite in v2.0.0+
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ITEM: 123", "SHPD_ICON_v684: ITEM: 99"]
---

Hey Dungeoneers, it's time for another beta release!

<div markdown="1" class="img-text">
![](/assets/images/icons/SHPD.png){: .align-left .rounded} <b><u>The beta for Shattered v2.1.0 is live right now!</u></b> You can get it:<br>- On [![](/assets/images/icons/gplay.png){: .rounded .text-inline}Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon) by [opting-in to betas](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon)<br>- On the [![](/assets/images/icons/appstore.png){: .rounded .text-inline}App Store](https://apps.apple.com/us/app/shattered-pixel-dungeon/id1563121109) via [TestFlight](https://testflight.apple.com/join/4PWFyask)<br>- On [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam](https://store.steampowered.com/app/1769170/Shattered_Pixel_Dungeon/), [![](/assets/images/icons/gog.png){: .rounded .text-inline}GOG.com](https://www.gog.com/game/shattered_pixel_dungeon), or [![](/assets/images/icons/itch.png){: .rounded .text-inline}Itch.io](https://shattered-pixel.itch.io/shattered-pixel-dungeon), via beta branches<br>- On [![](/assets/images/icons/github.png){: .rounded .text-inline}Github](https://github.com/00-Evan/shattered-pixel-dungeon/releases) for Android or Desktop.
</div>

In this blog post I'm going to go over the bulk of the changes coming in v2.1.0, including a bit of new content and a bunch of Duelist balance!

## Duelist Changes

When I look at balance data, I usually only include players who already have a win. A few weeks ago, after enough time had passed, I ran some numbers for the Duelist, and got some pretty interesting results:

- The Duelist is played 33.7% of the time, quite a lot higher than the average of 20%. This makes sense of course, she is a new character.
- Her overall winrate is almost exactly 50% lower than the average. This seems to indicate that she is extremely weak!

Right away this felt wrong to me. If the Duelist was truly half as strong as other classes you guys would be letting me know quite loudly. I decided to expand my numbers to include everyone who has at least beaten Goo to see what might change:

- The overall number of runs studied increases by about 5x, there are lots of people who haven't gotten their first win yet!
- The Duelist becomes played 21.1% of the time, only slightly more than average.
- Her relative winrate shoots up to just 12% below the average. Still a little weak, but much better!

To me this very clearly shows that experienced players are still experimenting with the Duelist and building their mastery of her, which causes her to appear quite weak. If I include a wider range of players though, who haven't mastered any of the heroes yet, the Duelist shows as just a bit below average.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/weapons.png){: .align-center}

For v2.1.0 I'm focused on a whole bunch of targeted buffs to specific Duelist abilities. These will come together to be a buff to her overall, but it's more about making more of her gameplay options effective than flatly boosting everything. In particular it seems quite clear that I still need to make many of her more awkward or risky weapon abilities stronger, as the 'plain but no downside' cleave ability is still doing quite well compared to other weapon abilities.

Pretty much every weapon ability (except cleave) is getting a buff, with most either focused on milder power boosts, or more substantial changes to reduce ability downsides. As probably the most significant example, heavy blow is getting its accuracy penalty replaced with a guaranteed hit, but now costs 2 charges when not surprise attacking. This should still preserve the goal of the ability synergizing with surprise attacks, but also makes it less useless in cases where surprise attacks aren't an option (such as against bosses).

## Other Additions

While the changes to the Duelist are the biggest overall adjustment in v2.1.0, it wouldn't be an update without some new things as well!

### New Weapons

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/katana.png){: .align-left}
The **Katana** is a new T4 weapon with 4-20 base damage and 0-3 blocking. It's been made in direct response to the feedback I heard from players about loving the rapier’s lunge ability and wishing it was more useful in later stages of the game. Just like with the rapier, the Duelist can **lunge** at enemies with the katana, dealing +50% damage.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sickle-scythe.png){: .align-left}
The **War Scythe** and **Sickle** are T5 and T2 weapons that trade in some accuracy for more base damage: 6-40 and 3-20 respectively. The accuracy penalty can be awkward, but can be worked around with things like surprise attacks. The Duelist can **harvest** with these weapons, dealing a large amount of bleeding instead of direct damage, but using 2 charges.
</div>

### Exotic Enemies

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tormented-spirit.png){: .align-left}
**Tormented spirits** are otherwise good ghosts that have been twisted by evil magic. They deal more damage than wraiths, but will grant you a reward if you can free them using a scroll of remove curse. Of course, you could also decide to just kill them, you monster. Tormented spirits replace 1 in every 100 wraiths, but will not show up in cases where wraiths can spawn repeatedly.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/phantom-piranha.png){: .align-left}
**Phantom piranhas** are a special piranha that can teleport when attacked. This normally moves them to a random place in the dungeon, but if you're next to water they'll teleport right to you and attack! Phantom piranhas replace 1 in every 50 piranhas and drop the exotic phantom meat, which fully restores satiety and grants all the effects of frozen carpaccio at once!
</div>

### Smaller Changes

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/shopkeeper.png){: .align-left}
Shopkeepers are getting a new interface when interacted with, which offers a little dialogue and shop buyback! I eventually want to make more extensive thematic changes to shops, but a little bit more interaction and new dialogue is a great starting point.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ascent.png){: .align-left}
I'm making some pretty notable changes to the ascension challenge. Enemies now get more max HP instead of damage resistance, and you'll also be able to keep earning exp while ascending all the way to level 30. I hope this makes ascension more fun and a little more rewarding.
</div>

<div markdown="1" class="img-text">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/misc.png){: .align-left}
As usual, there's also a slew of smaller changes and fixes. I'm getting more little issue reports than ever, so the game has never been more stable, even though the list of small fixes keeps growing each update.
</div>

---

I expect the beta for v2.1.0 to last slightly longer than a week, perhaps until next Wednesday. If you'd like some incremental updates on that leading up to release, consider following me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline} Mastodon](https://mastodon.gamedev.place/@ShatteredPixel) or [![](/assets/images/icons/twitter.png){: .rounded .text-inline} Twitter](https://www.twitter.com/ShatteredPixel)!

<div markdown="1" class="img-text">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider supporting me on [![](/assets/images/icons/patreon.png){: .rounded .text-inline} Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly Q&As and Content Polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/reddit.png){: .rounded .text-inline} Pixel Dungeon Subreddit](https://www.reddit.com/r/PixelDungeon/comments/13oxrcw/coming_soon_to_shattered_duelist_buffs_and/), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline} Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/3827542174236594353)!