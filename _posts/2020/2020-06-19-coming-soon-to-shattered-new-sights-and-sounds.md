---
title: "Coming Soon to Shattered: New Sights and Sounds"
excerpt: "v0.8.1 is filled with followups to v0.8.0, and a bunch of medium-large sized features that I've been wanting to get into the game for quite a while. There are some big visual improvements coming in this update!"

header:
  image: /assets/images/2020/2020-06-19/header.jpg
  teaser: /assets/images/2020/2020-06-19/header.jpg
  width: 1260px

gallery:
  - url: /assets/images/2020/2020-06-19/warrior.jpg
    image_path: /assets/images/2020/2020-06-19/warrior.jpg
    alt: "Warrior"
    title: "Warrior"
  - url: /assets/images/2020/2020-06-19/mage.jpg
    image_path: /assets/images/2020/2020-06-19/mage.jpg
    alt: "Mage"
    title: "Mage"
  - url: /assets/images/2020/2020-06-19/rogue.jpg
    image_path: /assets/images/2020/2020-06-19/rogue.jpg
    alt: "Rogue"
    title: "Rogue"
  - url: /assets/images/2020/2020-06-19/huntress.jpg
    image_path: /assets/images/2020/2020-06-19/huntress.jpg
    alt: "Huntress"
    title: "Huntress"

#This field is parsed by Shattered Pixel Dungeon to display an ingame icon in its news feed
tag: "ICON: DISPLAY"
---

Hey Dungeoneers, the next Shattered update is nearing completion, so let me share what's coming!

v0.8.1 is filled with followups to v0.8.0, and a bunch of medium-large sized features that I've been wanting to get into the game for quite a while. As you can probably tell from the header image, there are some big visual improvements coming in this update! I'm going to start with those big headline changes (new visuals and SFX!) and then cover some of the more specific changes to design and balance.

---

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, please consider making a supporter purchase on [Google Play](https://play.google.com/store/apps/details?id=com.shatteredpixel.shatteredpixeldungeon), or supporting me on [Patreon!](https://www.patreon.com/ShatteredPixel) Google Play Supporters get access to fun cosmetic in-game benefits. Patrons get access to weekly mini-blogs, monthly content polls, and a patron discord!

## New Hero Select!

I've talked about a redesigned hero select in both the [2019](/blog/shattered-pixel-dungeon-in-2020.html#audio-and-art-improvements) and [2020](/blog/shattered-pixel-dungeon-in-2019.html#hero-splash-art) plans blog posts, and finally it's happening! This new interface features a minimal UI and **fullscreen hero splash arts by [Aleksandar Komitov](https://www.alekskomitov.com/)!** Take a look:

{% include video id="Hr_cm35Gs8Q" provider="youtube" %}

Each splash is scaled to fill your screen, and has a crisp pixellated look to match the game's art style. Each splash does also have an HD version (you can a bit of the one for the huntress in this blog's header), and I will likely be doing something with those as well in the future.

Youtube's video compression doesn't quite do the splashes justice, so you can see some less compressed versions below. Note that the pixelization of the splashes isn't finalized just yet. Some specific details (especially around the face) may be tweaked before full release. You can click/tap the images to zoom in.

{% include gallery layout="half" %}

Giving a fully detailed view of the heroes is a big first step in making the overall story of the game a bit more character-driven. I'm not looking to abandon the game's setting of course (heck I just did a huge update expanding on it), but I think it's equally important for the player characters to be detailed and compelling.

I also still have [two new heroes planned](/blog/shattered-pixel-dungeon-in-2020.html#two-new-classes), and both of them will be getting the same full splash treatment. One notable thing I hope to improve on with additional characters (both heroes and NPCs) is the diversity of the game's cast. I didn't feel it was appropriate to make such changes to characters that have existed for over half a decade, but I do plan to make improvements on this front when new characters are being added.

## New Sound Effects

Shattered is also getting some new sound effects made by [Charlie (a.k.a s9menine)](https://s9menine.itch.io)! There are a total of 16 new sounds effects being added for a variety of situations. Just as with the splashes, it's probably best for the video to do most of the talking, though you can also see a list of the new sounds with timestamps below:

<!-- TODO this should probably be a global CSS property if I use it again -->
<style>
.double-yt-container {
    display:inherit;
}
.double-yt-vid{
    width: 100%;
}
@media (min-width: 37.5em) {
    .double-yt-container {
        display:flex;
    }
    .double-yt-vid{
      width: 50%;
    }
}
</style>
<div class="double-yt-container">
<div class="double-yt-vid">{% include video id="on-gzKyx1QI" provider="youtube" %}</div>
<div class="double-yt-vid">{% include video id="gE_VluCqCU8" provider="youtube" %}</div>
</div>

First Video:
- <u>0:00-0:10</u> Sturdy floors now have a correspondingly sturdy sound when stepped on.
- <u>0:10-0:30</u> Grass now gives a satisfying crunch, extra loud when it's tall grass!

Second Video:
- <u>0:00-0:10</u> The default hitsound has been remastered!
- <u>0:10-0:40</u> There are now new sound effects for slashing, stabbing, and crushing weapons. <u>0:40</u> and an extra impact sound plays when you make a surprise attack!
- <u>0:45-0:55</u> A new blocking sound plays when a hero takes no damage thanks to a shield.
- <u>1:10-1:30</u> Wands and the game's two bows have new sound effects too!
- <u>1:30-1:45</u> A few miscellaneous sound effects have also been added!

Many of these sounds show up in other places too! Weapons also make use of varying base pitches, so the 'crush' sound from a warhammer will be notably deeper than one from a mace.

## v0.8.0 Followup

I always try to evaluate how the game is performing after an update and adjust accordingly, but this is especially important following an update as big as v0.8.0. v0.8.1 includes some comprehensive balance and design evaluations to many parts of the game. Probably the most significant of these changes is being made to bosses:

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/tengu.png){: .align-left} I originally gave **Tengu** a second phase because I felt it was important to balance out the pacing of the fight. Players have responded really positively to the more intense boss fights I added in 0.8.0 though, and Tengu's second phase has had a generally negative reception. Based on that, I'm removing Tengu's second phase entirely, while making phase 1 a little trickier to compensate.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/dm-300.png){: .align-left} **DM-300** is performing well in terms of raw difficulty, but a lot of players are having trouble learning the fight. So, I'm tweaking the current mechanics, visuals, and text of the fight to try and make the correct method of fighting the boss a bit more obvious. Most significantly I'm changing when the fight actually starts, so that the player will have to explore the arena a bit and will know there are inactive pylons in the corners.

I'm also making a few targeted balance tweaks to Yog-Dzewa, and do plan to continue looking at overall boss balance to make sure they're all at the right level of lethality.

---

I've also looked at the balance of specific game elements to see what is over or under-performing. Probably the most notable change I've observed is a shift in the value of defense versus damage, especially burst damage. I'm happy to see this as a bit more emphasis on defense was my intention with several of the boss and enemy changes. Glass cannon builds are definitely still viable, but it's less valuable to have high burst and more valuable to be able to tough a fight out. Most game aspects have taken this change just fine, but wands and offense-focused subclasses are getting some buffs. Conversely defense-granting weapons and sources of magic defense are getting scaled back a little.

---

Finally, I set aside time while working on v0.8.1 to take a look at some items that are in need of more substantial design changes. None of these items are in a bad place due to v0.8.0 in particular, but this is an excellent time to make changes to them regardless:

- The **Talisman of Foresight** is getting a redesigned active ability that's more interative and powerful. It now scans forward in a cone, and reveals everything in the area it scans. The max range and reveal duration increase based on level.
- The **Wand of Regrowth** is being redesigned to be more useful in combat, rather than for pure farming. It still spawns plants and grass as usual, but now consumes less charges, roots more consistently, and has a new unique plant that boosts the longevity of other plants and tipped darts.
- The **Wand of Magic Missile** is getting a new power to make it more potent in conjunction with other wands. When upgraded, it can now briefly empower other wands, letting them act as if they were at magic missile's level. I'm being careful about the balancing of this, I want magic missile to have more use, but not so much that it becomes a dominant choice for the mage.

## Inventory Management

One more major change coming in v0.8.1 is targeted at inventory management. For a long time now, but especially after v0.7.0, It's been far too common for players to have substantially more items than their inventory can store. This is unfortunate as clogged inventories were supposed to be a problem v0.7.0 helped with! I'd still look to improve alchemy, but for now I'm focusing on the quantity of items coming into your inventory.

For **Consumables**, I'm slightly reducing their overall drop frequency, in exchange for making their variety more consistent. I'm accomplishing this by changing consumables to use a drop system that ensures items are dropped in proportion to their rarity over the course of a run. This should increase the chance of getting the specific consumables you want over the course of a run, while also slightly lessening their inventory burden.

**Equipment** is getting a similar treatment, except instead of variety I'm increasing quality. For the game in general, I'm reducing the frequency of low-value random equipment spawns, but leaving high-value drops from special rooms untouched. For enemies, I'm increasing the value of their equipment drops (they can now spawn upgraded!), but also making these drops gradually more rare as you get them. This both prevents farming and ensures players will get some equips of a higher quality, without being overwhelmed by too many.

Lastly, **Bags** are also getting a change. Currently they do an excellent job of removing inventory burden for certain items, but also slightly reduce the size of your main inventory. So I'm tweaking bags to appear inside of themselves and have 19 spaces free, rather than appearing in the inventory and containing 20 spaces. This should slightly alleviate general inventory burden for those items that can't go into a bag the player has.

---

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/hc4y05/)

[![](/assets/images/SHPD-icon.png){: .align-left}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) Currently I'm hoping to release v0.8.1 around the middle of next week. All of the changes are finished and I'm working on final bugfixes, mechanical polish, and spritework. If you can't wait though, there is a beta available right now! [You can find the latest release of the game (including a beta, if one is running), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)