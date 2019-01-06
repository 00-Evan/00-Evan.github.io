---
title: 'Coming Soon to Shattered: New Ranged Weapons!'
---
Hey Folks, I hope 2018 is going for well for you all so far. It’s finally time for me to share some progress on 0.6.3! Sadly, I’ve been very busy the last two months, so despite the longer wait 0.6.3 isn’t an especially massive update. It is aimed at solving one of Shattered’s longest standing issues though: the state of ranged weapons.

## How to Rework Ranged Weapons?:

Ranged weapons have always been a difficult thing for me to consider reworking, and I’ve pretty much ignored them over the last three years as a result. They have really badly needed changes all this time though. With a few exceptions, ranged weapons are considered to just not be worth the bother. Although in many cases they are quite literally free damage, their power and quantity has just been too low for them to be very impactful. Most players will collect them to sell and nothing more.

The most immediate solution is to simply directly buff ranged weapons: They could do more damage, and be found in a higher quantity. I initially tested doing this very a long time ago, but decided against it. While doing this would make ranged weapons impactful, it began to hit into a fundamental problem in their design. Distance-based damage is very limited in PD, so any damage ranged weapons can do is basically a ‘bonus’ ontop of mainline weapon damage. This means that by buffing ranged weapons, I give the player a large stack of mostly free damage that they could call on at any time. In order for the ranged weapons themselves to be impactful and fun to use, they would need to be powerful enough to let the player consistently kill enemies from a distance until they ran out of ammo. I decide that was too powerful, and let ranged weapons be.

However, now that I’ve thoroughly reworked and improved pretty much every other category of item, ranged weapons have become impossible to ignore. Ultimately, ranged weapons need to be limited in some way, but not so much that they aren’t impactful and fun. After thinking on their limitations somewhat, I came up with a list of three elements: poor direct impact, single use, restrictive ammo. A few ranged weapons (mostly tipped darts and tomahawks) avoid the first element somewhat, but other than that these limitations are shared by all standard ranged weapons. My initial attempt at reworking them removed the first and third limitation, but perhaps it is the second limitation which is worthwhile to look at changing.

## New Mechanics:

The solution I’ve decided on is letting the player reclaim none-broken thrown weapons from an enemy after defeating them, and giving most ranged weapons several uses before breaking. This solves the problem of hoarding ranged weapons, but still gives the player many more uses than they would have had previously. Infact, I can even give far fewer ranged weapons than before, while still having a large overall increase in number of uses. As a simple example, previously the game could drop 10 javelins, but now instead it might drop 3 of them which each last for 10 uses. This gives 3 times the number of overall uses, but at most 3 javelins can be thrown in any particular combat encounter. This is a somewhat similar restriction to wands, which work very well with their current recharge and upgrade mechanics. I’ve opted to let ranged weapons ‘pool’ their remaining uses, which means players don’t need to keep track of each item in particular, they’ll just be given a simple number of uses left before an item in that stack breaks.

Limiting the uses per combat lets me buff the direct impact of ranged weapons substantially. For example, javelins are going from 2-15 damage to 8-24, although their cripple effect is being moved to a different weapon. It also gives me greater control over variety, as some weapons can be balanced around having fewer or more uses before breaking. Tipped darts, for example, are going to retain a single use before breaking, but they will be more usable in the early stages of the game where they are most useful. 0.6.3 is going to feature over 10 different ranged weapons total, including some designed for direct damage, and others focusing on utility effects. It’s my hope that after 0.6.3 players will find ranged weapons to be a rewarding strategic option, but not so strong that they take over the game.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trident.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trident.png"/>
  <figcaption>
   A new high-tier ranged weapon, look at that damage!
  </figcaption>
 </a>
</figure>

Of course, if ranged weapons are getting changed up, what is happening to other parts of the game that depend on them?

## Huntress and Sharpshooting:

This change provides a nice opportunity to buff the huntress’s lategame power, which is lacking a bit compared to other classes. It’s not a full-scale rework, but should help tide her over until she gets one. Instead of being able to sometimes recycle a single ranged weapon per enemy, the huntress will now be able to use all ranged weapons for 50% longer before they break. Her boomerang has also been adjusted to do a bit more damage in the earlygame, however her knuckle dusters have been weakened slightly as a tradeoff. Her boomerang, naturally, will continue to have unlimited uses.

The ring of sharpshooting is getting a full overhaul, and will hopefully be much more useful. I’ve decided to position it as a sort of option for upgrading your ranged weapons. Each upgrade on the ring will boost ranged weapon damage by roughly as much as an upgrade would on a melee weapon, and extends their durability significantly. Ideally this will allow for some niche strategies that fully rely on ranged weapons, with a sufficiently upgraded ring of sharpshooting.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ranged-weapons.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/ranged-weapons.png"/>
  <figcaption>
   Some new ranged weapons, alongside some familiar ones
  </figcaption>
 </a>
</figure>

With ranged weapons finally improved in 0.6.3, I will have fully reworked every class of item except the consumables. Expect some exciting new things relating to them coming in 0.7.0…

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/)
