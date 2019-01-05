---
title: 'Shattered Pixel Dungeon v0.3.3: Google Play Games!'
---
A smaller update this time around, focusing on an often-requested feature: Google Play Games Integration! It’s now possible to sync your badge process, and unlock Google Play achievements by connecting to the Google Play Games service.

The update should already be available through google play, desktop, F-droid, and Amazon users should get this update in the next few days, assuming there are no major hiccups. Unfortunately as Google Play games is the main focus of this update, those other platforms aren’t getting too much this time around.

If you have any feedback or issues to report, please email me.

Here is the full list of changes, plus change context:

```
Support for Google Play Games:
- Badges can now sync across devices
- Five Google Play Achievements added
- Rankings sync will come in future

Shattered remains a 100% offline game if Google Play Games is not enabled

Gameplay Changes:
- Tengu's maze is now different each time
- Items no longer auto-pickup when enemies are near

Fixes:
- Fixed several bugs with prison enemies
- Fixed some landscape window size issues
- Fixed other minor bugs

Misc:
- Added support for reverse landscape
```

## Google Play Games Data use and Tracking

I know a lot of people play Shattered because it uses very few permissions, so I want to make it really clear exactly what's happening with the new google play games features.

To start with, all of this new stuff is optional, if you don't want the game to connect to the internet, simply never enable google play games. If you do enable it, here is exactly what happens:

- The game will sync your badge info to the cloud, storing it in a small partition of your google storage. This info can then be grabbed by other devices that you've connected, meaning that unlocking a badge once means unlocking it everywhere, even if you lose your initial device.
- The game now supports achievements, which are unlocked as part of the badge sync process. Currently there is just one for each boss, but I hope to add more in the future as part of a badge rework.
- The game will collect anonymous demographics and gameplay data. This lets me see things like which age and interest groups shattered is most popular with, how often people die on certain floors with certain classes, and how often players upgrade certain gear. None of this info is personally identifiable, it's all about broad statistics, not specific identification. I plan to use this data to help improve game balance, and better understand which parts of the game are more popular.

If you have any questions about this new functionality, feel free to talk to me about it. From my testing all of this stuff uses up less than 50kb of data per hour of gameplay.

## Mazes

Something I wanted to get done with 0.3.2, The game can now generate random mazes! This is done on Tengu's fight to start, but can easily be used elsewhere. Let me know what you think, hopefully the maze should be less boring now, but not too tricky to navigate.

## Reverse Landscape

Another thing I wanted to include in a previous update (this time I just forgot, oops), it is now possible to use reverse-landscape mode by flipping your phone over while in landscape. The same goes for portrait, for those rooted users who have 180 degree rotation enabled.
