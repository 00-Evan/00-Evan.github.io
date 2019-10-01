---
title: 'Coming Soon to Shattered: Better Traps'
excerpt: "In this blog I’m going to be talking all about traps in ShatteredPD! You may recall that in the last blog I mentioned I would be talking about secrets, however I got a bit sidetracked, and thought it would be fun to reflect that here as well. The secrets blog is still coming though, just a little bit later."
---
Hey folks, work on 0.6.2 is starting to come to a close, so expect that update fairly soon. In the meantime, here’s another blog!

In this blog I’m going to be talking all about traps in ShatteredPD! You may recall that in the last blog I mentioned I would be talking about secrets, however I got a bit sidetracked, and thought it would be fun to reflect that here as well. The secrets blog is still coming though, just a little bit later.

## How was I sidetracked?

I already took one pass at improving traps back in 0.3.1, and while I do think that update did its job, I’m still not happy with the state traps are in. 0.3.1 was focused around providing a great variety of traps, and while it did accomplish that it also introduced several problematic ones. I was very concerned with adding as many traps as possible, and not as concerned with trap quality as I should have been. In 0.6.2 I intended to take a quick look at traps and adjust some of the most problematic ones, but that ended up changing.

Having well laid plans is important, but they have to be flexible. A rigid plan is just asking to be broken by a shift in priorities or circumstance, and both of those happen very often in game development. My plan was for traps to be a minor point of 0.6.2, but the more I looked into them the more ways I found that they could be improved. The time I allocated to trap changes ended up ballooning from around a day to about a week, but the result is that instead of a few tweaks, I have essentially done a second trap overhaul! This does delay 0.6.2 slightly, but I think it makes it a much better update, and fixes one of Shattered’s more problematic updates from the past.

## So what am I actually doing to improve traps?

Traps are a tricky thing to design. They are all about forcing the player to adapt to a sudden change in circumstance, but players tend to really hate when something happens to them that’s out of their control. A good design for traps needs to keep several things in mind to ensure they’re fun despite the seemingly unfun core mechanic. These were my priorities when looking at traps, roughly in order of most to least important:

1. **Every trap should allow the player to react to their effect in some way.** If the player is able to do something about a trap’s negative effect, then that effect moves more toward creating varied gameplay rather than frustrating gameplay. This is the most important design element by far, if a trap breaks this it had better be for a good reason.
2. **Most traps should provide opportunities for the player to manipulate the effect to their benefit.** This lets the player turn something that could be frustrating into a satisfying tool in the right circumstances. It shouldn’t always be possible to do this, and it shouldn’t be easy (traps are meant to be harmful, after all), but allowing this makes traps much more engaging.
3. **Traps should offer a variety of themes, interaction choices, and negative effects.** Having 30+ traps is pointless if they all work the same way, so it’s very important to ensure that traps look and feel unique from eachother. This mostly manifests in interaction choices, where ‘throw a thing on the trap’ is far too common of a solution when it comes to diffusing traps.
4. **Despite point 3, most trap effects should fit into a clear group.** With a great variety of traps there’s a risk of too much complexity, so it’s also important to manage that variety appropriately. By creating groups of traps which all share a common element, it becomes much easier for the player to keep track of what all the traps do.

With those principals in mind, here a few highlights among what I’ve changed:

- Warping has been reworked to be a more disorienting teleportation trap.
- Worn dart, poison dart, and disintegration traps now all work similarly to grim: they target at a distance, but are always visible.
- Rockfall traps are now always visible, but cause rocks to fall in a very large area.
- Spear traps have been removed, but gripping and flashing traps now have infinite uses. Gripping also no longer roots.
- Lightning and Paralytic gas traps have been merged into a new trap: shocking.
- Fire, frost, and shocking traps now all create a lasting 3x3 AOE effect. They each have a stronger variant that has a 5x5 effect.  
The way scrolls and potions are destroyed by burning/freezing has also been made much less random.
- Pitfall, explosive, and disarming traps are unchanged, ~~because I love to see you suffer~~ because their unique effects justify the frustration they cause.
  
<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trap-examples.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/trap-examples.png"/>
  <figcaption>
   Examples of new elemental traps, new rockfall trap, and new disintegration trap
  </figcaption>
 </a>
</figure>

It’s my hope that after this update people will finally find traps more engaging than frustrating. They have a lot of potential to be a worthwhile and fun mechanic in the game, but only if they are handled **very** carefully. Look out for the last 0.6.2 blog, and the release of 0.6.2 next week!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/75hcrb)

