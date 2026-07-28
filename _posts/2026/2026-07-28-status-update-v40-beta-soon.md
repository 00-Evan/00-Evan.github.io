---
title: "Status Update: v4.0 Beta Soon!"
excerpt: "v4.0 is extremely close to being beta-ready, but to ensure it's not rushed I'm going to move the beta ETA back a little bit to the first half of August."

header:
  image: /assets/images/update-header.png
  teaser: /assets/images/update-header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
#244 = hourglass item sprite in v0.9.3+
tags: ["SHPD_INGAME", "SHPD_ICON_v533: ITEM: 244"]

---

Hey Dungeoneers, time for a little update!

Just about [2 months ago](https://shatteredpixel.com/blog/coming-soon-to-shattered-new-enchants-and-pixel-art.html) I gave an ETA that v4.0 would be ready for beta in July, hopefully earlier in the month. We're now reaching the end of July, so how's that looking?

v4.0 is extremely close to being beta-ready, but to ensure that it's not rushed (and also for the sake of my stress levels) I'm going to be moving that beta ETA back a little bit to the <u><b>first half of August</b></u>.

It's also worth noting that unlike v3.0, the beta for v4.0 will launch content-complete (or very nearly complete), so it should hopefully not be too long of a beta, maybe 2 weeks.

## What's Coming, and What's Left to Do?

As I've mentioned before, the continued delays are mostly because v4.0 has ended up being a pretty massive update. I initially wanted it to focus exclusively on the new quest, but that ended up changing.

As a quick recap, here's all the stuff coming in v4.0:
- A new quest in the dwarven city, easily the biggest and most detailed one yet.
- New environment art by Aleks, mainly focused on the city and quest rooms.
- New item sprites by PumpkinVolt, mainly focused on consumables.
- A new enemy AI system for stealth gameplay, currently only used in the new quest.
- Four new weapon enchantments, two new weapon curses, and some tweaks to existing enchants.
- An overhaul to the swarm intelligence challenge, improving its interactivity.
- Improvements to the changes screen, including historically accurate icons and a complete history of the original Pixel Dungeon.
- 10+ misc changes (including visible DOT in health bars and persistent danger indicators) and 30+ bugfixes

Of all that content pretty much everything is implemented, but there's still some little gaps to fill in and refinements to make. Here's what I think still needs to be done:
- The quest overall needs a good amount of playtesting and tweaking. Things like ensuring it's not overly long and that there's always a good balance of loot and hazards.
- I need to do a pass on all quest dialogue (there's a lot going on so descriptions need to be clear), and a midpoint room in the quest needs filling in with some per-hero text.
- The boss of the quest is fully functional but not balanced at all currently. I need to spend some time refining it based on how much gear a player is likely to have.
- There's a little bit of Alek's quest environment art left to for me to implement, some of which may happen during the beta or in patches.
- There's also a little bit of refining to Pumpkin's spritework to try based on feedback, which will likely happen in the beta or in patches.
- Lastly, as always, I need to make sure that everything works correctly and is reasonably free of bugs.

The good news is that refining functionality I've added is a lot easier than implementing new functionality in the first place, so I'm starting to pick up the pace as I work through these final things.

---

It feels a bit boring to just list off everything in text though, so how about a few visual teasers! Keep in mind that most of these visuals are WIP.

Firstly we've got a new type of treasure room, a simple circular pattern that requires a bit of timing to avoid the sentry:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/sentry-circle.webp){: .align-center .rounded-large}

Next here's a very special room, the 'midpoint' I mentioned in the list. That door looks unusual, and what could that mirror be for I wonder? I'll talk a bit more about that next blog post when the beta releases:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mirror.webp){: .align-center .rounded-large}

Next here's an early peek at a formidable foe in the quest. I'll also be talking more about it next blog. This elemental is capable of summoning waves of flames, so you'll need to move toward the gap:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/fire-wave.webp){: .align-center .rounded-large}

And now that elemental is made of frost! It has more direct attacks too, such as this cone of cold that sweeps across the ground. It's quicker to dodge if you're up close:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/frost-cone.webp){: .align-center .rounded-large}

Lastly, here's another GIF of scanning sentries, but this time after they've been fully implemented! Individually they don't do much damage, but for this type of treasure room you REALLY don't want to just wander in:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/implement-scans.webp){: .align-center .rounded-large}

If you'd like to see more GIFs like this incrementally (usually once a week), you can:<br>- Subscribe to the [![](/assets/images/icons/avatar.png){: .rounded .text-inline}Shattered Pixel Newsletter](/newsletter)<br>- Follow me on [![](/assets/images/icons/mastodon.png){: .rounded .text-inline}Mastodon](https://mastodon.gamedev.place/@ShatteredPixel)<br>- Follow me on [![](/assets/images/icons/bluesky.png){: .rounded .text-inline}Bluesky](https://bsky.app/profile/shatteredpixel.com)<br>In fact, the first three GIFs above were previously shown off in a social post! We're getting close to v4.0's beta at this point though, so there will probably be just one or two more social posts about it before the beta goes live.

---

<div markdown="1" style="display: inline-block;">
[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, monthly content polls, physical loyalty rewards, and early alpha access to updates!
</div>

You can discuss this blog post on the [![](/assets/images/icons/lemmy.png){: .rounded .text-inline}Pixel Dungeon Lemmy Community](https://lemmy.world/post/50009076), or on the [![](/assets/images/icons/steam.png){: .rounded .text-inline}Steam Community Forums](https://steamcommunity.com/app/1769170/eventcomments/592937047299238139)!