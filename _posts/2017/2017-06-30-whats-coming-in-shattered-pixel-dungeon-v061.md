---
title: What’s coming in Shattered Pixel Dungeon v0.6.1 pt.1
---
Hey everyone, I’m hard at work on 0.6.1 and thought I’d start sharing a bit of what’s coming. Unlike 0.6.0 I’m not planning on making any huge overhauls to core game systems. Instead 0.6.1 is focusing on improvements to rings and artifacts, a few general balance/design changes, and improvements to the new player experience. In this first part, I’m going to focus on three items that I’m changing in 0.6.1 and explain the thinking behind those changes.

A couple things to note regarding why I change items before we get started though. My goal isn’t to have all items be perfectly equal in power, but rather I want to ensure all items are reasonably balanced and fun to use. Shattered is at its best when you have a variety of interesting item choices available to you. If certain items aren’t fun, are too weak to justify using, or are so strong they overshadow other items, that’s when I want to make changes.

## Ring of Might:

### Current Stats:

- plus 1 strength per ring level
- plus 5 max HP per ring level

The Ring of Might was originally added back in 0.2.0, and back then it was fairly underpowered. However, since 0.4.0’s changes to strength requirements, the ring has become much stronger. At the later stages of the game it is just barely ahead of other top tier rings, but at earlier stages like the prison it is massively better than any other ring. The ring clearly needs a nerf.

The most obvious solution is to reduce the strength benefit, but I really want to avoid doing that. The major appeal of the ring is that it lets the player somewhat cheat the current strength system, and I would rather remove the ring entirely than nerf that away. There is another balance knob to tweak however: the health. A flat +5 max HP is most valuable in the earlygame, just like the strength, so altering it provides a nice opportunity to only hit the ring where it is most powerful.

### Changes:

- Max HP boost changed from a flat +5 per level, to +3.5% per level

By changing to a percent health boost, the bonus HP because much weaker in the earlygame, which should help pull back the Ring of Might’s dominance there. After around level 24 though the percent health catches up with the original flat boost, meaning the ring’s stats are largely unaffected when used in the endgame.

## Unstable SpellBook:

### Current Stats:

- Upgrades by being fed one of two specific scrolls, to a max of +10, no duplicate scrolls
- Scales from 3 to 8 max charges, charges much faster when upgraded
- When activated, instantly triggers a random scroll effect

The Unstable Spellbook is fairly well balanced in terms of winrate, but it’s failing in one very specific way: Nobody upgrades it. The book scales from being top-tier early on to being a bit below middle of the pack later on, but it is consistently upgraded the least out of all artifacts. Most players don’t see the extra charges as being worthwhile for the effort of upgrading it. Even if upgrading the book was worthwhile, it’s just not that interesting at the moment, as all the gameplay it offers is basically just a duplication of existing scroll effects.

An ideal balance change, then, would be one which takes power away from the books recharging and puts it into something new and interesting:

### Changes:

- Charges now scales from 2 to 6, and charge speed scales less with upgrades
- If a scroll has been fed to the book, its effect will be enhanced when it is triggered by the book

This change puts a lot more power into the effects themselves, gives the book a bunch of new unique mechanics, and better lets me balance the effects within the context of the book. Specifically, it lets me reduce the risk of using the book in combat by removing many of the downsides scroll effects normally have. The Unstable Spellbook will now be the only way to access several new powerful effects relating to scrolls, and should make a scroll-heavy playstyle much more interesting and viable.

Some effect examples:

- Remove curse will reveal all curses in your inventory before you choose which item to uncurse.
- Rage will no longer attract enemies from across the map.
- Recharging will grant 10 turns of 2x recharge, in addition to the usual 30 turns of normal recharging.
- Psionic blast will no longer damage, stun, or blind the player.

## Dried Rose:

### Current Stats:

- Upgrades by being fed rose petals, which are semi-randomly dropped after the rose is found
- When fully charged, can be activated to spawn an ally ghost hero
- Ghost hero’s accuracy/evasion is determined by hero level
- Ghost hero’s damage/health/defence is determined by the rose level
- Ghost hero cannot travel between floors, and will slowly die over time

The dried rose is currently the only item in the game that grants you a consistent ally. Helper characters are an extremely cool concept, and while I would never want to bog down Shattered with a full party system, there is lots of potential for ally mechanics. Unfortunately, at the moment the rose does a poor job of realizing that potential. The ghost ally is underpowered and offers little tactical opportunity, usually ending up as just a bit of bonus damage. Even worse, they end up being fairly temporary thanks to their health loss over time and inability to move between floors. One of the biggest reasons for the ghost’s weakness is that the rose costs almost nothing to invest in. Petals are quite easy to come by which ultimately means the only cost the rose has is that it takes an equip slot something else could occupy.

Giving more ways for the player to spend resources on the rose would give me lots more room to make it powerful and interesting. I also wanted to work on the rose from a technical perspective, both by improving the ghost’s AI and allowing them to follow you between floors. Finally, I know that in the future I want to add more items with ally-spawning mechanics, so giving the ghost something unique that other future allies would not have is also important.

### Changes:

- Rose no longer recharges while Ghost ally is alive
- Ghost ally no longer takes damage over time, and may now follow you between floors
- Ghost ally’s damage/defence are no longer determined by rose level
- Ghost now has a strength level, which increases with the rose level
- Ghost ally can hold a weapon and armor, and uses them just like the player would

While the core idea of the rose is the same, the gameplay relationship the player has with the Ghost Hero is now very different. The player now needs to consider what they want out of the ghost, and then equip it accordingly. This also means that the Dried Rose now takes advantage of all the gameplay possibilities already present in weapons and armor, which expands what the ghost can do massively.

This does mean that it will be more difficult to get value out of the rose though, as putting petals into the rose will no longer grant the ghost as much power. Petals will still be important though, as without adequate strength the ghost won’t be able to use very strong equipment. Thankfully, a well-outfitted ghost will be a lot more permanent thanks to the removal of the health loss and the ability to travel between floors.

I imagine most players will put whatever second-best items they can find on the ghost and leave it at that, but I’m very interested to see what kind of niche strategies players will come up with given all the new possibilities here.

---

Look out for part 2 in the next week or two, where I’m going to be detailing some of the new stuff coming in 0.6.1!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/6kiv8j/)

