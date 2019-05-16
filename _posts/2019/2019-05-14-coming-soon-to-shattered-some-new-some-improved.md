---
title: "Coming Soon to Shattered: Some New, Some Improved!"
excerpt: Hey Folks! I'm unfortunately still tied up with other work, so 0.7.3 is also going to be a grab-bag of smaller content additions and improvements.
---

Hey Folks! I'm unfortunately still tied up with other work, so 0.7.3 is also going to be a grab-bag of smaller content additions and improvements. I am hoping to get more time to dedicate to shattered soon though, so 0.7.4 will be a properly themed update with some more significant content additions.

In 0.7.3 I'm putting some focus on improving things players have been critical of in the last few updates. Some of these are being addressed with design changes, and others with balance changes. Let's get into it!

## Enchantments

![](/assets/images/2019/2019-05-14/kinetic.png){: .align-left} In 0.7.2 I changed up a bunch of enchantments with the goal of pulling many enchants away from just being a source of extra damage. I do think 0.7.2 succeeded in that, but it's clear from feedback that I overdid things a bit. While the followup patch to 0.7.2 did help, In 0.7.3 I'm looking to go further by repositioning and replacing a few enchantments that aren't working well.

Firstly, I am removing **Precise** and **Swift**. Precise not only did nothing to encourage gameplay variety, but was also basically a direct damage enchantment while technically dealing no damage. Swift had a really cool theme but it unfortunately was just far too specific to work in practice, and did nothing for the weapon that actually had the enchantment.

**Lucky** and **Blooming** are both becoming uncommon enchantments, instead of rare and common respectively. Blooming is doing very well, but it works best with specific synergies and often does little for direct combat, which makes it better suited to being uncommon. Lucky was not performing well enough to justify being rare, and I don't want to buff it up to the point where it begins to push into the space of the ring of wealth.

Two new enchantments are being added: **Kinetic** and **Corrupting**! Kinetic is a new common enchant that I hope will work well with slower weapons. When an enemy is killed with a kinetic weapon, any excess damage is saved and applied to the next attack. Corrupting is a new rare enchantment that gives a chance to instantly corrupt an enemy when they are killed with the enchanted weapon.

## Warrior Adjustments

![](/assets/images/2019/2019-05-14/warrior.png){: .align-left} Now that all the heroes have been reworked, I'm excited to start working on something new, but there are still things that can be done for the existing heroes! The warrior is in sort of an odd state right now, as he has the best winrate but feels the weakest to many players. That difference between actual power and perceived power is often caused by too much strength being tied to passive effects which the player doesn't notice. In the case of the warrior that power is coming from his shield regeneration. If I nerf this shielding, I free up a load of power to spend on more noticeable things.

**The Warrior** is no longer going to get faster shield regen the more powerful his armor is, instead it will be a flat 1 shielding every 30 turns. The maximum amount of shielding the warrior can get is unchanged though, so having better armor will still let you store up more shield. 30 turns was deliberately chosen as it slightly buffs the shielding regen in the very early game, which means the warrior shouldn't really feel this nerf too much until he gets to his subclasses...

**The Berserker** is already in a decent spot gameplay-wise, so I'm mainly going to make his rage easier to maintain. Rage will now deplete more slowly over time, especially at high and medium hp. Keeping yourself injured or having very strong armor will still be very useful for maintaining rage, but it shouldn't be as necessary now. The berserker is meant to be a very simple subclass that lets players focus on other game mechanics, so my aim with this change is to make him more fun while keeping his mechanics simple.

**The Gladiator** is getting some big improvements to how flexible his combo mechanics are. I've decided to completely ditch item usage resetting combos, and am going to allow attacks with thrown weapons to increment the combo counter as well. I'm also looking to adjust the slam ability to better tie in with upgraded armor, so that the gladiator gets back some armor synergy that he would have otherwise lost due to the base class nerf. All of this should make his playstyle much less restrictive, as combos are now easier to maintain and can be weaved in between item use.

## Boss Alchemy

![](/assets/images/2019/2019-05-14/elixir.png){: .align-left} I'm not making any big changes to the alchemy system itself this update (unlike the previous one, where I added [catalysts](/blog/coming-soon-to-shattered-alchemy-streamlining.html)), but there are some adjustments to specific recipes coming. Probably there will be at least some changes to alchemy every update, but I don't expect it to be the main focus of any updates in the next while.

From feedback and gameplay data I'm realizing that on average recipes are not impactful enough. I want to avoid making the system too powerful, but clearly there is room to buff recipes and to make them more unique and interesting. For this update I'm going to focus on improvements to boss recipes. Note that this doesn't include bombs, they are doing just fine already.

I'm making the following adjustments to **Goo Blob** recipes:
- **Caustic brew** is getting an increased AOE range (7x7, up from 5x5), and has had a significant reduction in alchemical energy cost.
- **Elixir of Aquatic Restoration** is becoming much more forgiving in how it grants healing. The speed of healing now scales with max HP, and the effect pauses when out of water, instead of being wasted. The total amount of healing is being reduced a bit in compensation though.
- **Elixir of Arcane Armor** is a new recipe that acts as a counterpart to the potion of earthen armor. This elixir grants a long-lasting armor against magical damage which slowly fades over time.

I'm making the following adjustments to **Metal Shard** recipes:
- **Curse Infusion** is being adjusted to be a more legitimate item and less of a jokey one. In addition to inflicting a curse it will now also grant a single upgrade to a wand, weapon, or armor. This upgrade persists as long as the item remains fully cursed.
- **Reclaim Trap** is getting changed up to be more about trap effects than recharging. The spell will now let you store a trap and activate it at any location you want! Only one trap can be stored at a time however.
- **Wild Energy** is a new spell that's acting as a sort of replacement for the recharging effect reclaim trap had. The spell will give you multiple turns of recharging and mystical energy, but you will have to deal with a random cursed wand effect!

## Thrown Weapons

![](/assets/images/2019/2019-05-14/club.png){: .align-left} Since I [allowed them to be upgraded in 0.7.1](/blog/coming-soon-to-shattered-the-huntress-rework.html), thrown weapons have largely been in a good place, so it's time to add some variety! I don't think there should be as many thrown weapon types as melee weapons, but clearly there is room for a few more. In 0.7.3 I'm adding a new thrown weapon for each tier:

- **Throwing Clubs** are the new tier-2 thrown weapon. They are a nice simple equivalent to throwing hammers, they deal slightly less damage but have extra durability.
- **Kunai** are the new tier-3 thrown weapon. They deal bonus damage against unaware enemies, but have a reduced number of uses.
- **Heavy Boomerangs** are the new tier-4 thrown weapon. I threw the boomerang item away in 0.7.1 but, predictably, it has returned! Boomerangs will returns to the cell they were thrown from after a few turns. If the hero is still there they will catch the boomerang, if an an enemy is there they will be struck by it.
- **Force Cubes** are the new tier-5 thrown weapon. Force cubes are a very interesting thrown weapon that has a built-in AOE effect! They will hit anything adjacent to the location they are thrown to, leading to a lot of potential damage. They pay for this with a lack of durability, however.

**Tomahawks** are also being adjusted so that their bleed now starts at 60% of damage dealt, instead of 100%. This allows me to buff their damage scaling back up to what is normal for a tier-4 throwing weapon without making them too powerful. Tomahawks should still scale better than any other thrown weapon in terms of overall damage, but it won't be quite as extreme now.

I'm also adjusting **Tipped Darts**. I've decided to remove dart tipping it from the alchemy system entirely, in favor of letting people tip (and clean!) darts from their inventory. This should both make dart tipping more accessible and streamline alchemy a bit more.

---

0.7.3 will be releasing in a bit more than a week, so look forward to seeing these changes ingame soon!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/boybne/)
