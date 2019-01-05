---
title: Shattered Pixel Dungeon v0.1.1, now with fruit!
excerpt: Hey guys, what’s up? Welcome to my fork of Pixel Dungeon, V0.1.1!
---
Hey guys, what’s up? Welcome to my fork of Pixel Dungeon, V0.1.1! This version completely overhauls the scroll of lullaby, tweaks some of the content I changed last release, reworks the functionality of the Dew Vial and Ankh, and adds a new type of food!
  
V0.1.1 is backwards compatible with saves from V0.1.0 and does not conflict with any existing PD installation.   
  
You can discuss on reddit [HERE](http://www.reddit.com/r/PixelDungeon/comments/2dp1gp/shattered_pixel_dungeon_v011_now_with_fruit/)

## Full Changelist

This time, rather than just a boring list I’ll write each change and then briefly write my thoughts on it.

### Seed of Sungrass readjusted, healing ramp now scales with max HP

Removing the %HP from sungrass in V0.1.0 was a bad idea. Returning $healing while keeping the ramp means I preserve the original nerf while also ensuring the heal is balanced at any stage of the game.
 
### Scroll of Psionic blast rebalanced, self damage is now more consistent & slightly reduced, self stun/blind increased
 
I was a little overzealous in my initial rework of the scroll of psionic blast, it was almost never worth using. I’ve reconsidered how to punish the player for using it poorly and have more clearly defined it’s best use case. Also, just to clarify what the scroll does since V0.1.0, the scroll will instakill any monster in your field of view, but bosses are resistant to the effect, Yog Dzewa is immune.
 
### Scroll of Lullaby Buffed, now gives a drowsy debuff, followed by deep sleep
 
Lullaby is probably the least useful scroll, so it’s tiem for a buff! Now, instead of conking everyone in view out immediately, the scroll will instead afflict everyone (including you) with the drowsy debuff. After a few turns a drowsy creature enters deep sleep, which is like regular sleep but:

- Can only be awoken by taking damage (includes hunger)
- Player heals 1hp per turn

The player will awaken after they reach max HP, and can also resist drowsiness by fighting. There are a lot of neat strategies you can employ with lullaby now, and I encourage you to experiment!

### Dew Vial/Ankh reworked:

When the Dew Vial came out the Ankh became pretty useless by comparison, I wanted to fix that.

Firstly the Dew Vial has been nerfed:

- The vial stills heals 100% when full, but now heals significantly less at fewer drops filled.
- no longer autorevives at full.

And the Ankh has been buffed:

- Can now be blessed using a full dew vial: a blessed ankh autorevives the hero to full HP. The ankh is destroyed in the process.

These changes restore the Ankh to it’s former glory, keep the dew vial relevant, reduce the overall ease for revives, and make for a cool interaction between two items.

### New Fruit: (special thanks to reddit users /u/bart9h and /u/roastedlasagna for inspiration!)

Players who chance upon gardens or who get lucky while trampling grass may come across a new plant: the Blandfruit. As the name implies, the fruit from this plant is pretty unexceptional, and will barely do anything for you on its own. Perhaps there is some way to prepare the fruit with another ingredient, why don’t you see what you can find? The goal of BlandFruit was to add more food into the game with interesting gameplay interaction, let me know how the fruit works for you!

### Misc.:

- Corrected a serious bug involving wands, (also fixed in source 1.7.2)
- fixed a visual bug from the original source involving the dew vial and quickslots.
- Corrected a bug involving saving and the redesigned sungrass buff.
- fixed a typo in Icecap
- Recoloured the App Logo to differentiate from vanilla PD, this is a placeholder and a real new logo will be added later.
- Modified the game’s tolerance for exceptions when loading bones files, should reduce the number of ‘Something went wrong’ errors.
