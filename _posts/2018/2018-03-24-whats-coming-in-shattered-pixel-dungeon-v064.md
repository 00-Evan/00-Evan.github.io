---
title: What’s Coming in Shattered Pixel Dungeon v0.6.4
---
0.6.4 is coming along nicely, so I thought I’d share some of the things in development! Initially I had planned to go straight to 0.7.0, but one thing I really want to focus on this year is releasing updates more consistently. In order to achieve that, I’m going to start releasing more smaller updates in between large ones, rather than releasing nothing for up to 3 or 4 months. With that in mind, 0.6.4 is focused on adding a bit of new content, and making a few fixes and improvements to some existing things which need it.

One small thing I hope to improve in 0.6.4 is inventory management. Previously, I wanted to ensure inventory space had some serious limitations, with the intention that people would want to manage what they take with them. This ignored the reality that people can just drop items on the floor and come back for them later though, which means limited inventory is more annoying than anything else. Because of this, I’ve decided to ditch my previous stance and adjust some elements of how bags work. The wand holster is now a more generic holster which can hold wands and missile weapons, and every hero will now start the game with a bag. This should help alleviate the annoyance of inventory congestion, but still allow me to limit items that don’t fit into bags, if I ever need to.

A more significant feature that very few players use is the challenge system. This makes sense, challenges are mostly focused around removing aspects of gameplay in order to enhance difficulty, which isn’t terribly interesting. Even worse, beating the game with all challenges enabled is basically impossible, which doesn’t inspire people to really try. Eventually I’d like to dedicate an entire update to overhauling challenges, but in the meantime I can make some big improvements simply by adjusting some mechanics around.

Every challenge has received changes, some large and some small. The primary goal is to better balance challenge difficulty and scale back on challenges just removing gameplay as much as possible. For example, faith is my armor will now allow you to keep and use your starting cloth, which means several armor-based strategies are still possible, albeit with massively reduced defense. I’ve also tweaked the balance of the various challenges which remove sources of healing, so that winning with all-challenges isn’t about getting lucky with a vampiric weapon. This isn’t all about making challenges easier though, I’ve adjusted some challenges to try and weight things a bit more towards lategame difficulty, so that getting a run started is easier, but finishing will be very challenging indeed. Here’s a quick summary of the challenge changes:

 - On diet now provides small rations, rather than removing all food
 - Cloth armor is now allowed on faith is my armor
 - Pharmacophobia is unchanged
 - Barren land now allows seeds to drop, but they cannot be planted
 - Swarm intelligence now draws nearby enemies, not all enemies
 - Into darkness now limits light more harshly, but provides torches
 - Forbidden runes now removes 50% of upgrade scrolls, and no other scrolls

One other thing coming in 0.6.4, which is a feature that many people have asked for, is a ranged weapon! Not another thrown weapon, but rather an weapon which shoots projectiles as ammo.

Ranged weapons are an extremely common type of equipment to have in fantasy games, usually in the form of bows or guns. I have been opposed to including them in shattered for some time though, due to design issues that I thought were unavoidable. Firstly, Pixel Dungeon’s interface is already extremely cluttered, and a weapon which uses ammo would only add to that by increasing the complexity of how weapons can work (loading with ammo), and by possibly eating up more quickslots. Such a weapon would also affect inventory space, as you would need to hold onto both the weapon and its ammo. Ranged weapons also have to be balanced extremely carefully to avoid weapon juggling. Weapon juggling would just add more complexity and annoyance to the game’s interface. If a ranged weapon wasn’t usable in melee range it would get juggled, but if it was usable in melee then it wouldn’t be different enough from a reach weapon to be worth all this extra interface complexity.

Despite all these problems, it doesn’t change the fact that ranged weapons are an extremely popular concept, and I have frequently considered how I might implement them. Keep in mind that the implementation I discussed above, with ammo being loaded into the weapon, isn’t necessarily the only way to fulfill the theme of a ranged weapon. As I was working on thrown weapons for 0.6.3, I settled on the idea of darts lasting forever but doing so little damage that they were only useful when tipped. It quickly occurred to me that these new darts would work very well as ammunition. This led me to start thinking about a ranged weapon that worked ontop of the existing thrown weapon system, rather than handling ammo in some new way.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/crossbow.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/crossbow.png"/>
  <figcaption>
   I give you, the crossbow!
  </figcaption>
 </a>
</figure>

The crossbow is a tier 4 melee weapon with lowered damage, but a fairly unique effect. While it is equipped any darts you throw will deal substantially more damage, scaling with the level of the crossbow. This design not only has a bunch of cool strategic possibilities, but also solves many of the design problems inherent to ranged weapons! Firstly, the crossbow works with tipped darts, and provides its enchantment to all darts used. This gives all sorts of cool effects, and lets classes other than the huntress use enchantments with ranged weaponry. It also avoids UI issues entirely by piggybacking on the existing thrown weapon system. Shooting a dart from the crossbow is as simple as throwing them with the crossbow equipped. Lastly, the crossbow is strong enough in melee to not be worth juggling, and while it is similar to a reach weapon in core function, this isn’t as much of an issue now because there isn’t a big usability tradeoff for it existing.

While I don’t ever think ranged weapons like bows and guns will feature as prominently in Shattered as melee weapons, I’m very happy that I’ve been able to squeeze them in. By using darts as ammo ranged weapons can fit into their own little niche in the game, without having any impact on the game’s structure or interface at all. Infact, if the crossbow does well, I could easily add a lower-tier equivalent, perhaps a blowpipe?

0.6.4 will be releasing in about a week, so look out for these, and other new things soon!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/86trlz/whats_coming_in_shattered_pixel_dungeon_v064/)
