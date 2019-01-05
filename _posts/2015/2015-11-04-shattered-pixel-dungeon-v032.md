---
title: 'Shattered Pixel Dungeon v0.3.2: The Prison Rework!'
excerpt: "This update brings the beta balance changes to live, and also adds a reworks a bunch of stuff about the prison. I'm making progress on that whole 'faster updates' thing, so expect 0.3.3 to be out before the end of the month."
---
Hey folks, finally time for another shattered update!

This update brings the beta balance changes to live, and also adds a reworks a bunch of stuff about the prison. I'm making progress on that whole 'faster updates' thing, so expect 0.3.3 to be out before the end of the month.

As always, you can get the update through google play (should be live right now!). Desktop, F-droid, and Amazon users should get this update closer to the weekend, once I've ironed out any major issues and got the source released.

As always, if you have any feedback to give or run into any issues, please email me.

Here is the full changes list, plus change context:

```
Prison Rework!:
- Tengu boss fight completely redone
- Corpse dust quest overhauled
- Rotberry quest overhauled
- NEW elemental embers quest
- NEW prison mob: insane prison guards!
- Thieves can escape with a stolen item
- Gnoll shaman attack speed increased
 
BIG BALANCE CHANGES: 
- Mastery Book is not attainable until floor 10, even when unlocked
- Many changes to compensate for Mastery Book changes (see below)
- Hunger damage now increases with hero level, but starts out lower 
 
Sewers rebalance: 
- Marsupial rat damage and evasion reduced
- Gnoll scout accuracy reduced
- Sewer crabs less likely to spawn on floor 3, grant more exp
- Fly swarms rebalanced, moved to the sewers
- Great Crab HP reduced 
- Goo fight rebalanced 
 
Base Class Changes: 
- Mage's staff base damage increased 
- Huntress now starts with 20 hp 
- Huntress no longer heals more from dew 
- Rogue's cloak of shadows now drains less while invisible
 
Subclass Changes: 
- Berserker now starts raging at 50% hp (up from 40%) 
- Warden now heals 2 extra HP from dew 
- Warlock completely overhauled
 
Misc. changes:
- Fixed 'white line' graphical artifacts
- Floor locking now pauses all passive effects, not just hunger
- Cursed chains now cripple, do not root
- warping trap is now more likely to put you at a deeper floor
- various other bugfixes
```

## Mastery Book & Sewer Balance

No doubt the biggest change balance wise, there are two major reasons I'm making this tweak. 

Firstly, I want the earlygame experience to be consistent for all players, it makes no sense that new players who hadn't unlocked the book had a harder time in the earlygame. Now that difficulty has been rebalanced to be about at the 'post mastery' level for everyone, new players should actually have a less harsh time at the beginning of the game. I certainly don't want to make the whole game easier, but early on it makes sense for the game to be kinder so that people don't feel like they hit a wall the second they get to floor 4/5. 

Secondly, I want more design space for subclasses. Having them available at floor 1 seriously limits how I can design subclasses in the future. We even see this being prevalent with only 2 options, where the best generalist subclass is the one that's picked far more often right now. I want to make interesting subclasses that fit in strategic niches, but its much more feasible to expect the player to pick those options after they hit floor 10, as they might have found some of the tools that would make a niche subclass work.

## Prison Rework

The prison finally gets some new stuff! These changes include new quests, a new tengu fight, and some tweaks to prison mobs. 

Skeletons were already in a good place so there was no need to change them. Shaman got a bit more threatening if you blindly run at them (their magic hits more frequently now). You're going to have to be very careful with your positioning around thieves now, as letting them get away is a bad idea. Lastly, prison guards drop some nice loot, but you might find it hard to keep a distance from them. 

The quests have all been reworked around a theme of a specific location. Whether you need to find an overgrown garden, a ritual marker, or a mass grave, each quest will send you looking for a spot, and then doing something interesting there. Careful though, these quests are a fair bit tougher than the sewer ones, make sure to listen to the wandmaker's advice. Part of these quests being in a certain spot means you can engage them on your own terms, so don't be afraid of putting them off if you need better gear.

Finally, tengu is still the same tricky assassin as always, but he has some nasty new tricks. Lookk out for harsher traps, a new arena with cover, and a labrynth you'll need to navigate in order to take him down.

## Changes to Level Locking

As people had time to play with the level lock effect it became pretty obvious it was easy to exploit. With the new tengu fight, which has quiet moments, this would be even worse, so here's a change. Rather than just affecting hunger, time will now not help or hurt you while fighting a boss. You can take your time and drag out a fight, but you won't passively recharge items, regen health, or get hungry. Note that all active effects (e.g. scroll of recharging) aren't affected by this.

## Warlock

I think I described this one best when I made a post regarding my planned changes on the pixel dungeon subreddit:

> To make a long story short, I've been experimenting with the balance of the warlock given the current beta hunger changes, and he just isn't fun, regardless of his balance state. I feel the warlock straddled the line of being unfun before (he probably needed to be changed regardless), but the hunger changes make him completely unsatisfying to play. 
>
>So I'm going back to the drawing board, My ideas for his new class benefits are as follows:
>
>- When the warlock uses magic (wands) on a character, he has a chance to 'mark' their soul
>- The chance increases with wand level and charges used in a zap
>- The warlock restores health and hunger when a marked target takes physical damage.
>
>These would completely replace the old benefits, so food would once against restore hunger.
>
>This lets people focus more on working on the benefits, rather than constantly mitigating downsides. It also clearly defines the warlock's role in relation to the battlemage, as wands need to be accompanied by a weapon for the warlock to be most effective. This is also neat as it means the warlock will specifically synergize with many wands that aren't as commonly used on the battlemage, such as corruption, fireblast, frost, lightning, and maybe even regrowth.
