---
title: "Coming Soon to Shattered: Better Bosses!"
excerpt: "Hey Dungeoneers, long time no see! Over the last four months I’ve been steadily working on the beta for 0.8.0. There haven't been any life events that caused this delay, it's simply because 0.8.0 ended up becoming a much larger update that I originally planned."

header:
  image: /assets/images/2020/2020-04-08/header.png
  teaser: /assets/images/2020/2020-04-08/header.png
  width: 1260px
---

Hey Dungeoneers, long time no see!

Over the last four months I've been steadily working on the beta for 0.8.0 and making posts for those who've signed up on [Patreon](https://www.patreon.com/ShatteredPixel), but for a lot of you I've been basically silent on dev work since the [last post](/blog/shattered-pixel-dungeon-in-2020.html) in mid January. There haven't been any life events that caused this delay, it's simply because 0.8.0 ended up becoming a much larger update that I originally planned. But now I'm happy to finally be at the end of developing it, which means I can share more info!

---

Before we get started though, I want to send my well wishes to everyone currently feeling the effects of the novel coronavirus. Regardless of whether the virus has affected your health, mental wellbeing, or financial stability, I want to wish you the best as we all do what we can to fight it.

We live in an unprecedented era of human communication and coordination, which has allowed many of the world's societies to protect themselves from the virus before any direct treatment for it has been developed. While it's easy to focus on cases where the virus has spread uninhibited, every case where it has not is a victory for humanity in this battle, and we're racking up quite a few of them. I think this recent XKCD comic highlights it best: [We're not trapped in here with the coronavirus. The coronavirus is trapped in here with us.](https://xkcd.com/2287/)

## Why the Wait?

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/pylons.png){: .align-center}

0.8.0 was already shaping up to be a fairly big update when I [last talked about it](/blog/coming-soon-to-shattered-more-new-foes.html), but since then the scope has increased further. In fact, originally 0.8.0 was going to be named 0.7.6, and was intended to be only a bit bigger than 0.7.5.

The original plan was for 0.7.6 to be primarily specific enemy and boss tweaks that were easy to implement. However, as I kept looking at enemies and general balance in the mid to late game, I kept increasing the amount of elaborate changes I was making. Slowly my plan transformed from *"specific tweaks to enemies and bosses"* to *"overhaul enemies, but just tweak bosses"*, and then eventually to *"totally overhaul both enemies and bosses"*.

Because of that change in trajectory, 0.8.0 is now looking to continue the trend of every 0.X.0 update being bigger than the last one. Here's a quick list of all the major stuff coming in 0.8.0:
- Complete redesigns to standard enemies in caves/city/halls
- Total redesigns to DM-300, Dwarf King, and Yog
- Rework to Mimics
- Five new rare enemy variants
- Substantial design changes to the demon halls
- Significant design changes to some lategame traps
- Major balance changes to class armor abilities
- Full support for desktop platforms (no wider release just yet though)
- New ingame update notifier for all platforms
- Loads of smaller improvements and bugfixes

## Big Changes to Bosses

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dwarves.png){: .align-center}

0.8.0 now includes total redesigns to the game's three later bosses, which before now have been basically unchanged since the original Pixel Dungeon! For each of these bosses, I wanted to evaluate what their primary issues are and how those could be addressed with new mechanics and design. I've tried to keep the theme of each boss pretty much the same, but their specific abilities have been almost totally changed.

---

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dm300.png){: .align-left}
Currently **DM-300** is the least interesting of the game's bosses. After the player realizes they cannot kite DM-300 over trap tiles, the fight revolves around stepping back out of toxic gas, hoping you don't get unlucky with falling rocks, and otherwise just treating DM as a regular enemy with very high stats. Despite this, DM-300 being a powerful in-your-face boss is really cool thematically, it just can't be bad to be next to it all the time.

I'm trying to adjust DM-300's fight to put a bigger emphasis on environmental interaction, while still preserving the original theme. To start with, DM-300 retains its rock dropping and gas spewing abilities, but these can now be evaded with smart positioning. DM-300 now has multiple phases, some of which require the player to fight, and others require the player to flee. A core part of this is that DM-300 is now a 'large' enemy, and can't move into tunnels as a result. This gives the player a big positioning advantage against DM-300 when they need to run, but DM has some abilities to help it level the field, quite literally.

---

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/king.png){: .align-left}
Currently **Dwarf King** has a very neat premise as a minion-master boss, but the difficulty of the fight largely hinges on how well you can manipulate his mechanics. Because DK needs to walk onto pedestals to summon his minions, it's extremely easy to manipulate him into a state where he is constantly running around trying to summon while taking damage from your attacks. AOE items such as liquid flame and toxic gas are especially good at this. On the flip-side, not messing with him will often result in the player being stunlocked by skeletons while DK kills them. I think the biggest improvement DK needs is a better balance of power between himself and his summoning mechanics.

The crux of DK's changes are that his summons are now stronger, slower, and do not require any action on his part. This means that the threat of summons is much more consistent, rather than wildly variable depending on your actions. Rather than bearded skeletons, the player will now fight the same dwarves that are encountered earlier in the metropolis: ghouls, reworked monks, and reworked warlocks. This allows these enemies to add their own mechanics to the fight, further enhancing the variety and danger. Initially the player is encouraged to divide focus between DK and his minions, but then there is a wave-based phase that is all about minion fighting, and finally a tense finale where the player needs to rush down DK's remaining HP.

---

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/yog.png){: .align-left}
Currently **Yog-Dzewa** has a great theme as a multi-character boss, but suffers from problems with pacing. The fight starts out with two powerful fists and a passive eye, and is largely decided by whether the player gets ganged up on by the fists or not. Smart players who use items like invisibility potions can engage the fists on their terms, and almost totally disarm (or perhaps dis-fist) yog right after the fight starts. Less prepared players will often fight both fists at once and get overwhelmed. Neither of these results are very fun; ideally a boss should ramp up the intensity as the fight progresses, not spend it all right at the start.

While I think all the individual parts of Yog's fight work well, I've decided to restructure the pacing of the fight entirely. Yog now summons fists steadily as the eye takes damage, rather than all at once at the start of the fight. Yog has a total of 6 fists, and will summon 3 randomly selected ones over the course of a given fight. This is my first significant foray into [alternate boss behaviours.](/blog/shattered-pixel-dungeon-in-2020.html#alternate-boss-behaviors) The eye is also no longer passive: it will summon larva on a cooldown, and can shoot artillery laser blasts at the player regardless of their location. As the fight progresses, Yog's abilities will become faster and it will fire multiple lasers at once, which gives a really great difficulty progression regardless of the order the fists are spawned in.

One extra thing to note with Yog is that it will be the only boss whose difficulty is directly affected by player action on the floors above. It's no secret that the best way to deal with the demon halls is currently to run past them, as they're often seen as more trouble than they're worth. In order to thwart that, I've significantly ramped up the loot enemies drop in the halls and also added new enemies. Each demon halls floor has a demon spawner, and leaving them alive is a risky proposition...

---

These new bosses have been in beta for a little bit now and so far I'm extremely happy with how they've performed. Player feedback has been almost unanimously positive, and after a few tweaks the overall difficulty of these bosses is just about where I want it. It's important to note though that while I do want the bosses to be harder to cheese with specific strategies, I don't want the game to be much harder overall. All of the new mechanics I've described above come along with raw stat nerfs, and as always I plan to keep evaluating difficulty to ensure these bosses are fun and challenging, but not cruel.

My only significant gripe with this update is the amount of time it's taken to complete...

## Changes to Development Philosophy

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/fists.png){: .align-center}

Years ago, Shattered updates could be made of relatively quick and simple changes to the game, but as I've gained experience and expectations that's no longer the case. It's now reaching a point where it's actually difficult for me to keep the size of updates in check. My plans are almost always growing in size as I develop an update and discover more things that I could do. This is a good thing for the game of course, but because I haven't acknowledged this and planned for it the game's release cadence has suffered.

Just to illustrate my point, here is a brief summary of every 0.X.0 update so far:
- **v0.1.0** was made over a few days. It included significant balance changes to various consumables. I make larger changes in some balance patches these days.
- **v0.2.0** took 31 days. It included significant ring redesigns and added artifacts. It's worth noting that artifacts have had substantial changes and additions since 0.2.0.
- **v0.3.0** took 92 days. It included a redesign to the mage class and most wands. Unlike 0.2.0 the changes here mostly stuck and only some things received big changes in later updates.
- **v0.4.0** took 50 days. It included major additions and rebalances to weapons, enchantments, and glyphs. It came out a bit quicker as I did the warrior rework in a separate update. 
- **v0.5.0** took 115 days. It included a total overhaul to the game's visual style, moving the graphics to 2.5D from 2D.
- **v0.6.0** took 116 days. It included a completely new levelgen algorithm, which allowed for better level layouts, and paved the way for other content in the future.
- **v0.7.0** took 168 days. It included a completely new game system by reworking alchemy.
- **v0.8.0** is taking a bit more than 190 days. This blog and the [last one](/blog/coming-soon-to-shattered-more-new-foes.html) cover what's coming.

Shattered's updates have gotten much bigger and better, which is great, but taking half a year on an update should only be done if absolutely necessary. Doing things in one big update was a bit unavoidable with 0.5.0 and 0.6.0, but 0.7.0 and 0.8.0 could easily have been split into multiple smaller updates. Splitting updates into smaller parts is a way for me to keep release times in check while still letting my plans be flexible.

You may remember that in the plans for 2020 blog post, I talked about a [new gameplay system.](/blog/shattered-pixel-dungeon-in-2020.html#new-gameplay-system) Originally the plan was to do a relatively small 0.8.1 update, and then implement this new system in 0.9.0. This would make 0.9.0 into another big monolithic update that could easily take another half-year to complete. Instead I'm going to try something different and will release this new gameplay system incrementally over multiple updates. I've yet to decide if these will be named 0.8.2, 0.8.3, etc. or 0.9.0, 0.9.1, etc. but the result is the same: **this will prevent Shattered from going another half a year without a public update.**

In addition, regardless of how long I take on updates, I should be communicating better to the average player. The vast majority of players don't visit this website or patreon, and so have no way of knowing what I'm doing until they get an update. This means for many users the last 6 or so months have looked like I just stopped working on the game! I don't yet have solid plans for this, but I'm toying with the idea of extending the game's main menu to feature a news feed section, which would allow blog posts on this website to reach many more players.

---

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/fxfs2j/)

Currently I'm hoping to release 0.8.0 in the next few days. All of the changes are finished and I'm working on final bugfixes, mechanical polish, and spritework. If you can't wait though, there is a beta available right now! [You can find the latest release of the game (including a beta, if one is running), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) Lastly, if you like to support what I do, [please take a look at my Patreon!](https://www.patreon.com/ShatteredPixel) I've recently added a new community discord exclusively for patrons, and our next milestone goal is patron-exclusive livestreams! If you want to support me outside of ingame donations on Google Play, Patreon is the best way.
