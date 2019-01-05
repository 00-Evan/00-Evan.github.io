---
title: 'Shattered Pixel Dungeon v0.6.0: New Levelgen!'
---
Hey everyone! Another 3 months have passed without an update, but this is a big one!

Before I get into descriptions though, I want to let you guys know that the next few updates are going to come faster and be more focused on traditional content. I know some players have been longing for some regular content updates for a while now. Those updates are coming soon, just a little more waiting!

In the meantime though 0.6.0 is definitely a content update, just of a different sort. 0.6.0 introduces a completely redesigned level generation system! Almost every aspect of levelgen has been completely reworked, and while things should still feel pretty familiar, there are a lot of possibilities now with this new system.

The update is rolling out right now through Google Play, and will be available to users on other platforms soon.

Here’s a full list of changes, plus change context:

```
New levelgen!
- Level creation algorithm completely overhauled!
- Sewers are now smaller, caves+ are now larger
- Some rooms can now be much larger than before
- Added 8 new standard room types, 
  and loads of new standard room layouts

Environment Balance Changes:
- Falling damage tweaked to be less random
- Reduced number of traps in later chapters
- Floor 2 entry doors only hidden for new players
- Visiting floor 21 before completing the imp quest
  no longer prevents his shop from spawning
- Light sources now grant significantly more vision
- Light from torches now lasts 20% longer
- Slightly increased visibility on floor 22+
- Floor 21 shop now sells 3 torches, up from 2

Item Balance Changes:
- Meat and small rations are 50% more filling
- Pasties and blandfruit are 12.5% more filling
- Greataxe base damage increased by ~22%
- Greatshield base damage increased by ~17%
- Vampiric enchant lifesteal reduced by 20%
- Lucky enchant rebalanced:
  now deals 2x/0x damage, instead of min/max
  base chance to deal 2x increased by ~10%
- Glyph of Viscosity rebalanced:
  proc chance reduced by ~25% 
  damage over time reverted from 15% to 10%
- Glyph of Entanglement root time reduced by 40%
- Glyph of Potential rebalanced:
  self-damage no longer scales with max hp
  grants more charge at higher levels
```

## New Levelgen!

I’ve already written two blog posts on this, so if you’re curious about how the system works you should look at [Part One,](/blog/whats-coming-in-shattered-pixel-dungeon-v060.html) and if you want to see some of the new content that’s been added, take a look at [Part Two.](/blog/whats-coming-in-shattered-pixel-dungeon-v060-2.html)

## Environment Balance Changes:

The falling damage changes are another attempt to make falling very damaging, without also having it instakill low HP players. Back in 0.4.1 I added a bleed component to help with this, but it was proving too random and would occasionally quickly kill high health heroes. Chasms now will deal mostly upfront damage if the hero is healthy, and will deal mostly bleed if the player was weak when they fell. This should preserve the initial goal of letting dieing heroes chug a health potion to survive, while also cutting down on the randomness for those who fell when healthy.

The changes to traps, entry doors, and light sources are reactionary to the levelgen changes. With more detailed level layouts, traps become more punishing (and they were already quite harsh anyway), reducing their number should help with that. The more freeform layouts make secrets harder to find, so it seemed unnecessary to keep adding secret doors on floor 2 for players who clearly already know how to search for them. Light changes were entirely to counterbalance the fact that rooms layouts are a bit larger now, which makes reduced visibility more punishing. I’m happy that darkness is harsher now, as previously visibility would need to be almost 0 before it became a serious drawback.

## Item Balance Changes:

Food changes are entirely due to new levelgen, which tends to make backtracking and being thorough take longer, especially after floor 10. Rather than just buffing food across the board though, I felt it was more interesting to make the less common food sources more worthwhile. Overpriced rations have also been renamed to small rations, to reflect the fact that after this buff (and their cost reduction in 0.4.1) they are clearly not a terrible buy from the shop anymore.

Weapon, glyph, and enchant changes were all made based on analytics data. The Greatshield and Greataxe weren’t quite carrying enough heft to justify their strength requirements; enemies should now feel their weight just as much as you do. Vampiric and Viscocity have been knocked down a peg or two due to their very high usage, they should still be very strong however. Lucky, Entanglement, and Potential have all had major changes to make their drawbacks less punishing. Lucky in particular has had a major mechanics change to allow it to better stack with other damage boosting effects. I look forward to seeing screenshots of people dealing 200+ damage with a lucky greataxe =P

[You can discuss this update on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/6fapo7/shattered_pixel_dungeon_v060_new_levelgen)

