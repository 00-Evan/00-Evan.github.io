---
title: 'Coming Soon to Shattered: The Rogue Rework!'
excerpt: "0.6.2 is the first update with new content focused on taking advantage of the levelgen overhaul from 0.6.0. All the hidden secrets in the dungeon are getting an overhaul, along with the Rogue class and a few other tidbits. This blog is going to be focused on improvements I’m making to the Rogue, but look out for a second blog in the coming weeks which will detail how dungeon secrets are changing."
---
Hey folks! Work on the next Shattered PD update (0.6.2) is well underway, so it’s about time I started sharing some of what’s coming.

0.6.2 is the first update with new content focused on taking advantage of the levelgen overhaul from 0.6.0. All the hidden secrets in the dungeon are getting an overhaul, along with the Rogue class and a few other tidbits. This blog is going to be focused on improvements I’m making to the Rogue, but look out for a second blog in the coming weeks which will detail how dungeon secrets are changing.

## The Rogue Base Class:

The Rogue was actually the first class to get an overhaul way back in 0.2.0. Back then my goals for Shattered and what I considered a class overhaul were very different. I gave the Rogue a fancy new cloak and called it a day. While the cloak is definitely an improvement, I don’t think it’s enough. As unintuitive as it may be, the Rogue has a much deeper issue in that he has too many abilities!

For reference, here are the Rogue’s abilities right now:

- Starts with a unique Cloak of Shadows which grants invisibility
- Already knows which scroll is the scroll of magical mapping
- Has a significantly increased chance to automatically detect secrets
- Automatically identifies the type of ring when wearing one
- Takes slightly more time to build hunger
- Gains bonus evasion per excess strength on armor

The major issue here is that while he has lots of powers, the only one which is really significant is the Cloak of Shadows. All the others are some mixture of weak, hard to notice, and difficult or impossible to interact with through gameplay. This creates a class that has no clear strengths and isn’t as fun as it could be. The Rogue seriously pays for this lack of clear strengths in the earlygame, where having a lot of small benefits isn’t very helpful.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/survival-rates.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/survival-rates.png"/>
  <figcaption>
   Here you can see each class’s survival rate by a given floor, represented as a percentage difference from the average. This data is taken from the latest version(0.6.1b), and only includes players who have beaten the game at least once. Some amount of survival variance is fine, but by Goo the Rogue has a whole 30% lower survival rate than any other class, yikes!
  </figcaption>
 </a>
</figure>

My plan for the Rogue is to focus him more clearly around two strengths: stealth and discovering secrets. I also want his powers to be more noticeable, and affect the way people play with him more strongly.

With that in mind his new powers are:

- Starts with an improved Cloak of Shadows
- Already knows which scroll is the scroll of magical mapping
- Searches in a larger radius than other heroes
- Is able to find more secrets in the dungeon than other heroes

I’m going to cover what exactly ‘secrets’ are in the next blog post (don’t worry, it isn’t more traps), but the intention with these changes is to allow the Rogue to more easily explore the dungeon, and for him to get more rewards out of said exploring.

The biggest direct buff to the Rogue here is coming from improvements to the Cloak of Shadows. The cloak is getting a significantly faster recharge speed, and the cloak’s cooldown mechanic is being removed entirely. This should significantly buff the rogue’s ability to escape danger and deal damage in the early stages of the game. The removal of the cloak’s cooldown means the Rogue finally has a tool to deal with strong enemies, as he can spend multiple charges for consecutive surprise attacks.

## SubClasses:

The Rogue’s subclasses also have issues, but they’re almost the opposite of the issues with his base class. Despite losing lots of ground to other classes, the Rogue’s winrate climbs to be just about 5% below the average. This is because the Rogue gains a ton of power once he gets access to better items and his subclasses. A big component of the power of both of his subclasses comes from them requiring the player to do very little to fully benefit from them. I want to make his subclasses slightly weaker than they are currently, and require more interaction. This should nudge down the rogue’s lategame power, and also make his later game abilities more fun to use.

### The Freerunner:

Currently, the Freerunner gains a boost to movement speed whenever he isn’t starving or encumbered. I’m changing this up by giving him a new system where he needs to earn his movement speed more directly. As he moves the Freerunner will build momentum, fully charging at 10 moves. Momentum grants the Freerunner bonus movement speed and evasion, depending on the charge. The extra evasion also scales with excess strength on armor, effectively transitioning that base class benefit to the Freerunner! The Freerunner rapidly loses momentum whenever he isn’t running, but if he’s quick at weaving into and out of movement he’ll be able to maintain a high amount of charge.

This focuses the Freerunner on speed and evasion, and gives him some clear goals both in terms of gameplay and item choice. Unlike with the Rogue, the extra evasion the Freerunner can gain is quite significant, so I’m really excited to see what item builds this subclass makes possible.

### The Assassin:

Currently, the Assassin gets a 25% bonus to damage whenever he surprise attacks. I’m changing that to a system where he gets bonus damage from turns spent in stealth prior to a surprise attack. This removes his ability to get bonuses from regular surprise attacks, but lets him instead gain a much bigger bonus from extended time invisible. In its simplest form this lets him spend multiple cloak charges for extra power, but there are other ways of becoming invisible. Extended time invisible will let the Assassin blink to enemies before attacking, do more damage to injured enemies, and even instantly kill regular foes!

Just like the Freerunner, this makes the Assassin need to do more work to get a cooler effect. He loses a lot of baseline damage consistency, but can call upon much stronger attacks when he really needs it. This also cements the Assassin as the subclass which combines well with the Cloak of Shadows.

---

It’s looking like 0.6.2 will be going live late this month or early October. After 0.6.2 the only class left without a proper rework will be the Huntress, hopefully I’ll get to her sooner than later…

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/7049yb)

