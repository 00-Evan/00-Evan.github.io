---
title: "Coming Soon to Shattered: Tier Two Talents!"
excerpt: "After a bit longer in development than I thought, v0.9.1 and tier two talents are ready for beta testing! In this blog I'm going to go over the major changes I'm making to the first talent tier based on feedback, and then talk about most of the new talents coming in v0.9.1!"

header:
  image: /assets/images/2020/2020-12-01/header.png
  teaser: /assets/images/2020/2020-12-01/header.png
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: TALENT"]
---

Hey Dungeoneers,

After a bit longer in development than I thought (those levelgen changes took a while), v0.9.1 and tier two talents are ready for beta testing! In this blog I'm going to go over the major changes I'm making to the first talent tier based on feedback, and then talk about most of the new talents coming in v0.9.1!

## Changes to Tier One Talents

Before getting into tier two, there are some significant changes I have planned for tier one talents based on gameplay data and feedback. I'm looking to adjust or reposition the T1 talents that scale too well into the later stages of the game, and to improve some talents that players felt were underwhelming.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/warrior.png){: .align-left}
**The Warrior** is getting the smallest T1 changes of the bunch. I'm adjusting his two healing talents to address one of them being a bit too strong, and one of them being a bit unpopular:
</div>
- **Hearty Meal** is consistently outperforming the Warrior's other T1 talents, so I'm deepening the missing health requirement a little. It will now heal for a bit less at 50% health, and will heal for the current amount at 25% health.
- **Test Subject** is performing well balance-wise but is a bit unpopular, probably because of how restrictive it is. I'm going to change the trigger to identifying any item, but am also reducing the heal to compensate. That should hopefully make the talent more popular while keeping the power level and general gameplay the same.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/mage.png){: .align-left}
**The Mage** is, by contrast, getting the most T1 changes. I'm making changes aimed at both removing some power scaling from his T1 talents, and addressing the common point of feedback that his talents felt like the weakest of the bunch:
</div>
- **Energizing Meal** is being moved to T2 and I'm giving the Mage a more short-term T1 food talent instead. This new talent is named **Empowering Meal**, and it will give the Mage bonus damage on his next few wand zaps after eating food.
- **Tested Hypothesis** is also being adjusted to trigger on any identification, but in addition to that I'm changing up the effect. Shielding is a bit too short-term to be consistently useful when you ID an item, so instead I'm going to have this talent grant recharging!
- **Energizing Upgrade** is also being moved to T2 and in its place I'm adding in a talent that gives the Mage some more immediate defensive power. This talent is **Backup Barrier**, which grants the Mage a small amount of shielding when he spends the last charge in his staff.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/rogue.png){: .align-left}
**The Rogue** has two of the best scaling T1 talents, so I'm redesigning both of them to be a bit more short-term:
</div>
- **Rationed Meal** is being renamed to **Cached Rations**. Cached Rations will let the rogue find a set number of small ration caches in the earlier stages of the dungeon. This keeps the theme of extra food value, but makes the effect more noticeable and confines it to the earlier stages of the game.
- **Mending Shadows** is currently most used for converting cloak charges into healing, rather than giving the rogue some defensive power in combat. I'm renaming this talent to **Protective Shadows** and having it give shielding instead of health, to keep it to its original purpose.

<div markdown="1" style="display: inline-block;">
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/huntress.png){: .align-left}
**The Huntress** is getting a change to her food talent as well, but is otherwise in a good place:
</div>
- **Invigorating Meal** is being moved to T2, just like with the mage, and is being replaced with something a bit more short-term. The Huntress is getting a talent called **Nature's Bounty**, which will let her find small berries in grass in the earlier stages of the game. These berries provide less overall food value than the rogue's cached rations, but can also be eaten quickly and have a high chance to contain a seed!

## Tier Two Talents!

*Please keep in mind that balance and visuals here are still a WIP. Some of these talents may change before or shortly after full release.*

For tier two, I'm looking to make talents with a similar overall design to T1, except that I now have a much bigger power budget to play with. T2 talents are allowed to be useful all game rather than just in the earlier stages and so there are a lot more possible triggers and effects they can have! I've also tried to partially design these talents to work with certain subclasses and hero builds, which should open up more variance in talent choices compared to T1.

Firstly, just like in T1, each hero is getting a talent that relates to food. For the Mage and Huntress, these are simply their old T1 talents after being repositioned, but the Warrior and Rogue are each getting something new.  The Rogue is getting an artifact-charging counterpart to the Mage's food talent, which should be helpful in keeping his cloak and other artifacts topped up. The Warrior is getting a more defensive talent that grants him momentary massive damage resistance while he eats, perfect for well-timed blocks. I'm also letting every T2 talent improve eating speed, not just invigorating meal for the Huntress.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/food-talents.png){: .align-center}

The Warrior and Mage had some of their innate powers moved into talents in v0.9.0, and now it's time for the Rogue and Huntress to get a similar treatment. The Huntress is getting her thrown weapon and enemy detection bonuses turned into talents pretty directly, but for the Rogue it's a bit more subtle.

Previously the Rogue would get an average of 3 more secret rooms over the course of a playthough. This was thematically interesting but hard to notice, and also meant levels would have slightly different layouts for the Rogue. So, in v0.9.1 I'm giving every hero slightly more secret rooms and I'm giving the Rogue a T2 talent that gives him some help in finding them.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/innate-talents.png){: .align-center}

I'm also adding a talent to each hero that ties into using common items. For the Mage this is just like his old T1 talent, although with the effect tweaked to be a little more permissive. The Rogue is also getting an upgrade-based talent that gives bonus charging to his cloak. I think each of these offer an interesting tradeoff compared to each hero's T2 food talent. You can choose between a weaker more general effect that's easy to trigger, or a stronger more focused effect with a less common trigger.

The Warrior and Huntress are both getting effects that trigger when drinking potions of healing. For the Warrior the effect is a simple recharging of his shield, which nicely complements the healing he already wants when drinking a health potion. The Huntress is getting an effect that's a bit more complex but also more potentially powerful. Rooting adjacent enemies give her an opportunity to retreat when she wants distance, and spawning grass around her helps to block line of sight from ranged enemies.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/item-talents.png){: .align-center}

Finally, there are some talents with more varied effects as well. Here are four talents that all mix up gameplay interaction in some way:

- The Warrior gets **Improvised Projectiles**, which allows him to briefly blind an enemy by throwing anything that isn't a throwing weapon at them. This gives the warrior a bit of help against ranged enemies and fits his more 'brute force' character theme.

- The Mage gets **Shield Battery**, which lets him target himself with any wand or his staff to drain its current charges into a shield. This naturally synergies with the Mage's various recharging options, and gives him more to do with the variety of wands he tends to end up with.

- The Rogue gets **Silent Steps**, which ensures he will never wake up a sleeping enemy unless he's quite close to them. This opens up some neat strategic options for the rogue, as other classes have much less control over when sleeping enemies wake up.

- The Huntress gets **Rejuvenating Steps**, which causes her to grow tall grass on her position whenever she steps on short grass or embers. This opens up a little warden-like power for the Huntress regardless of her subclass choice, by giving her a little more control over where high grass is.

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/misc-talents.png){: .align-center}

In total, the second tier has 5 talents per hero and 6 talent points to spend from level 7 to 12. Tier three will come in v0.9.2 (which should hopefully come a little quicker), and will cover levels 13-20. There are some fun details that will separate tier 3 from 2 and 1, expect to read more about that in the near future!

[![](/assets/images/icons/SHPD.png){: .align-left .rounded}](https://github.com/00-Evan/shattered-pixel-dungeon/releases/) I'm planning to fully release v0.9.1 in about a week, but you can play it in beta right now! [If you're a Google Play user, you can opt into betas here](https://play.google.com/apps/testing/com.shatteredpixel.shatteredpixeldungeon). [You can also get the latest release of the game (including betas), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)

---

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy ShatteredPD and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, a monthly Q&A livestream, and also help determine content direction through community polls!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/k50r7w/)