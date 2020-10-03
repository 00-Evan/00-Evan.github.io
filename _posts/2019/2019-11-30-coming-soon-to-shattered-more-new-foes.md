---
title: "Coming Soon to Shattered: More New Foes!"
excerpt: "0.8.0 is a continuation of 0.7.5, and contains major changes to enemies and general balance in the later stages of the game."

header:
  image: /assets/images/2019/2019-11-30/header.png
  teaser: /assets/images/2019/2019-11-30/header.png
  width: 1260px

#This field is parsed by Shattered Pixel Dungeon to display an ingame icon in its news feed
tags: ["sprites/ripper.png, 15, 0, 15, 14", "SHPD_INGAME"]
---

Hey Dungeoneers, the next Shattered update, v0.8.0, is currently well into development, here's some of what's coming!

0.8.0 is a continuation of 0.7.5, and contains major changes to enemies and general balance in the later stages of the game. In this blog I'm going to talk about changes to enemies, but look forward to a second part coming later, where I'll talk about the improvements planned for bosses.

The major goal with these changes and additions is to make the lategame more interesting, better balance its difficulty (it's too spiky right now), and to encourage a greater variety of player strategy. There's a lot to get though, so I'm going to be a bit brief for each individual enemy, let's go!

## Caves

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/shamans.png){: .align-center}

**Bats** and **Gnoll Brutes** are both getting relatively minor changes. I'm tweaking bats to deal slightly less damage, and to heal for less than their raw damage dealt. This should hopefully make them a bit less oppressive against undergeared runs, especially runs with weaker damage. Brutes will now rage when at 0 health instead of 1/4, and will gain shielding equal to half their health when they start to rage. Just like with the Berserker, this shield fades over time, and they will die when it hits 0. My hope is that this will make their rage a gameplay factor more often, instead of just giving the hero an extra attack to finish them off.

**Gnoll Shamans** are getting some significant changes, and are becoming a caves-exclusive enemy! In the prison they are being replaced by **DM-100s**, which function basically the same as shamans do currently. The new caves shamans have better stats and a new earthen-themed magical attack! Each shaman you encounter can be wearing one of a few different mask types, and the debuff they inflict with their magic will vary based on the mask.

**Cave Spinners** are being slightly reworked into what I like to call a 'pseudo-ranged' enemy. Pseudo-ranged enemies are capable of attacking at a distance, but have some major drawback to their ranged attack such as a cooldown, charge-up, or debuffing instead of dealing direct damage. Spinners are getting the ability to spit webs around the hero, but can't directly web their position. This means spinners can use their webs strategically to cut off escape or chase routes. The webs also now block projectiles, but will break apart when doing so.

**DM-200s** are a new very bulky caves enemy that's too big to move into tunnels! This gives the player a lot of control over how to engage them, but DM-200s make up for it with impressive stats and a couple abilities to help them against dodgy players.

## Dwarven Metropolis

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/elementals.png){: .align-center}

**Ghouls** are a new basic enemy that will appear in the early stages of the dwarven metropolis. Their direct stats aren't very high, but they make up for this by always traveling in pairs! They'll be much more threatening if you let them gang up on you, so make sure to use those hallways!

**Elementals** are getting some fairly significant changes to make them more varied and mechanically interesting. With ghouls taking the spot of basic metropolis enemy, I'm moving elementals to be a pseudo-ranged enemy! There are also now multiple elemental types, so fire isn't the only thing you'll need to look out for. Each elemental has a different ranged attack that they can use every few turns, but these attacks will be focused around debuffing instead of dealing raw damage. Each elemental type has the same base stats, but different resistances/weaknesses and different debuffs they can inflict when attacking.

**Monks** are getting a complete change to their ability, with the goal of being less annoying and also more effective at countering enemy damage. Rather than disarming the hero, monks now build focus to parry an attack. When they are prepared, the next physical attack against a monk will be 'parried' by them, and is guaranteed to miss as a result. Monks start a fight with full focus, but need time to rebuild it, so big attacks are still effective, but need to be performed after a weaker opener.

**Warlocks** are being moved to appear slightly later in the metropolis and are getting a melee damage reduction, but are also getting a really nasty new debuff! This debuff, named degraded, will temporarily weaken heavily upgraded gear! At moderately high upgrade levels such as +5 this debuff won't be too severe, but at higher levels the effective upgrade level can be halved! I'm not out to totally invalidate upgrade dumps with this change, but I do hope to give those builds something to worry about!

**Golems** are getting a similar treatment to DM-200s, and won't be able to move into tunnels. To offset this change, golems are getting a stat bump and brand new abilities. While DM-200's are mostly able to do simple mechanical things in response to the hero, golems have access to dwarven magic, and will have some pretty potent powers to offset their lack of mobility.

## Demon Halls

![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/halls-enemies.png){: .align-center}

**Ripper Demons** are a new fairly basic enemy that appears throughout the halls. They attack and move quickly, but are very frail compared to other enemies. With strong armor or good damage they should be dispatched without too much trouble, but you might notice that there's a seemingly endlessly supply of them...

**Demonic Spawners** are the second new demon halls enemy, and are meant to go along with ripper demons. Unlike all other standard enemies, spawners have their own special room and are created with levelgen. Spawners are big and tanky, but can't move or attack on their own, all they can do is spawn a limitless supply of ripper demons! Hunting down and killing the spawners will stop ripper demon from respawning on that floor, and will also give the player a big chunk of exp and a guaranteed health potion drop! 

In contrast to the caves and metropolis, I'm actually already pretty happy with the existing enemies in the demon halls, and so I'm only making minor changes, mainly focused around making their drops more rewarding:
- **Succubi** work well as a sort of chaser enemy that often forces the player to position well or use other types of damage than directly attacking. In order to make fighting them more rewarding, I'm adjusting them to commonly drop any scroll type except identify, instead of only rarely dropping lullaby. 
- **Evil Eyes** were basically already reworked way back in 0.4.1, and I'm still pretty happy with those mechanics. I'm tweaking them to drop twice as much dew on average, and they now have a chance to drop a seed or runestone.
- **Scorpios** already function well as a purely ranged-enemy that's more evasive than usual, so I'm just tweaking their drops as well. They will now commonly drop any potion except healing (spawners drop that now). Note though that I did significantly change **acidic scorpios**. Rather than having a chance to rebound huge amounts of damage, they will now inflict ooze instead, which I think plays nicely into their evasive nature.

I'm also making a few balance adjustments to weapon and armor drops, mainly focused around the lategame. Tier 2 items will no longer drop in the caves or later, tier 3 will no longer drop in the demon halls, and tiers 4 and 5 are a bit more common at appropriate stages of the game. This should remove those annoying situations where the player finds a comically under-tiered item as loot in later stages of the game.

Several tweaks are also being made to rarer lategame traps. Similarly to the trap adjustments from 0.6.2, the focus here is to remove cases where traps just screw the player over without any real ability for them to react. I'm also adjusting trap spawning frequency to make traps less plentiful in the lategame. Here are the most significant changes to specific traps:
- Explosive traps no longer spawn as a regular random trap, but you can still encounter them in special trap rooms.
- Cursing traps now always curse a single item, and won't curse rings or artifacts (which are much nastier when cursed compared to weapons/armor).
- Disarming traps now have a distance range they can teleport your weapon away to, preventing extreme cases where it could go to the other end of the level.
- Pitfall traps now affect a small AOE, but also give the player a single turn to react before they're yeeted down to the next depth. This means players can use the traps against enemies, and can also quickly swig a healing or levitation potion to save themselves.
- Distortion traps have been reworked, and now act as a sort of more chaotic summoning trap. I do think removing their current effect is a bit unfortunate, but it was just too prone to errors, especially when combined with the reclaim trap spell.

My hope with all these changes is to keep the demon halls dangerous while also making them more worthwhile to explore.

---

I'm going to be keeping a keen eye on how all of these changes perform over the beta, and making adjustments as needed. I'm expecting the beta for 0.8.0 will last for a little bit, so expect to see the blog detailing boss changes sometime in the next few weeks.

A few of you might have read that previous paragraph and wondered what I meant when I said beta. Shattered has had open betas for updates for a long time, but I've often been fairly quiet about them, but I'm changing my policy on that! [You can find the latest release of the game (including a beta, if one is running), on the game's Github page here.](https://github.com/00-Evan/shattered-pixel-dungeon/releases/)

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/e45im5/)

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) Lastly, if you're as excited about these changes as I am, please consider making a purchase in the Google Play version of the game, or [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) While I don't ever plan to paywall game content, patrons do get early info about what I'm working on, which will include a first look at new bosses before I release the next blog!