---
layout: single
title: 'Shattered Pixel Dungeon v0.2.4: 1.7.5 source and some extras!'
---
Hey guys, one final maintenance update before we FINALLY move on to 0.3.0 and the wand rework. A mixture of source releases and the donation system has meant that I have been adding very little content for the past couple months, this isn’t something I think anyone is happy about. Now that this is all done with, I’m looking forward to getting back to big updates which overhaul content!

As usual, you can find the most recent version from Google Play. Amazon and the desktop version are both getting updates soon. Amazon has to wait as I position my internal code organization so I can make simultaneous donation and none-donation releases. I have a couple unique tweaks and improvements planned for the desktop version, so those users will need to wait a bit as I get those finished.

Changing the formatting up a bit, I’m going to list changes just as they appear ingame (using the new shiny scrollable changes pane), and then afterward explain some of the more important changes.

## Here is a list of changes

> ### v1.7.5 Source Implemented, with exceptions:
> 
> - Degredation not implemented.
> - Badge syncing not implemented.
> - Scroll of Weapon Upgrade renamed to Magical Infusion, works on armor.
> - Scroll of Enchantment not implemented, Arcane stylus has not been removed.
> - Honey pots now shatter in a new item: shattered honeypot. A bee will defend its shattered pot to the death against anything that gets near.
> - Bombs have been reworked/nerfed: they explode after a delay, no longer stun, deal more damage at the center of the blast, affect the world (destroy items, blow up other bombs).
> 
> ### In addition, this update features the following changes:
> 
> - The huntress has been buffed: starts with Potion of Mind Vision identified, now benefits from strength on melee attacks, and has a chance to reclaim a single used ranged weapon from each defeated enemy.
> - A new container: The Potion Bandolier! Potions can now shatter from frost, but the bandolier can protect them.
> - Shops now stock a much greater variety of items, some item prices have been rebalanced.
> - Going down stairs no longer increases hunger, going up still does.
> 
> ### Many, many bugfixes:
> 
> - Some UI improvements.
> - ingame audio quality improved.
> - Unstable spellbook buffed.
> - Psionic blasts deal less self-damage.
> - Potions of liquid flame affect a 3x3 grid.

# Change Context:

> ## Degredation
> As was already mentioned in my previous Reddit post, I am not implementing degradation. I completely agree with the intention, but simply too many players found it unfun. The code is all there in the source though, so it is entirely possible for me to add it as a challenge. I also want to implement my own solution for the problems degredation attempted to fix, more on that as we get closer to the weapon/armor rework (think 0.5.0 or so).
> 
> ## Badge Syncing
> This one was removed from the source by Watabou. As a side benefit, this means Shattered can continue supporting android 2.2 for the foreseeable future.
> 
> ## Bombs, bees, scrolls of enchant
> These were all introduced to help counterbalance degradation somewhat. As degradation isn’t here, I’ve attempted to nerf bees and bombs as to not make the game too easy, and decided against including scrolls of enchant entirely. Reworking Scroll of Weapon Upgrade was something that happened to be on my to-do list anyway.
> 
> ## Huntress
> As she was made even weaker in 0.2.3 from the invisibility thrown weapon nerf, and since her rework was so far away, I decided to give the huntress some help in the meantime. The changes should hopefully increase her relative power, without her losing her unique playstyle. It has never been mentioned anywhere that the huntress doesn’t get a strength bonus for melee weapons, yet on investigation it is clearly there in the code, I’m treating that one both as a buff and a bugfix.
> 
> ## Shops
> As I reworked how shops work internally in the last update, the limit for items stocked has gone up from roughly 15 to 39. With all that extra space, I decided to put some more stuff on offer. Players should be less encourage to sell many items, and more encouraged to pick choices strategically with the money they have. Global gold has been increased a little bit to compensate for this. Additionally all shops except the first one (which stocks both) will now stock a weightstone OR an ankh.
> 
> ## Stair Hunger
> the biggest sticking point for new players seems to be the hunger system. While I’m not eager to make it much easier directly, I do want to make it more clear to players how hunger should be managed, and what affects hunger. Hunger from stair movement was never explained anywhere in the game, so removing not only improved clarity, but does give newbies a little bit of extra breathing room.
> 
> ## Music
> Just a small extra note on what exactly I changed: title screen music has been tweaked to not be as loud to start, ingame music has been recompressed from Cube Code’s original track, and should be notably clearer with the same file size. The music which plays on the surface has been completely changed to an unused part of the original title music by Cube Code, should sound a bit more ‘epic’.

