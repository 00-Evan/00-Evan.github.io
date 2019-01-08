---
title: Shattered Pixel Dungeon in 2019

header:
  image: /assets/images/2019/2019-01-08/header.png
  teaser: /assets/images/2019/2019-01-08/header.png
  width: 1260px
---

Hey folks, it's a new year, and a new website! I have moved on from Tumblr, and brought all of the previous blog posts with me. Things may shift around here a bit as I settle on some aspects of the website design and content, but I'm very happy to no longer be dependent on an external blog provider.

I have been developing Shattered Pixel Dungeon for over four years now and a huge amount of ground has been covered since Shattered's humble beginnings in late 2014. I originally started ShatteredPD as a rebalance mod and while balance improvements are still an emphasis Shattered shifted to offering brand new content and completely reworking or replacing gameplay systems from the original Pixel Dungeon. We're now at the point where gameplay-wise Shattered is more of its own game than it is a fork of the original Pixel Dungeon.

After working on a project for so long, it's important to step back and take a look at where we are now and what there is left to do. Even with Shattered being massively expanded from its original goals, there will still come a time when I will be ready to call it complete. Infact, now that I have finished so much, I think it's possible to put most of what's left onto a list!

So, for the start of 2019, I present the first ever 'longer term goals' blog post, where I'm going to illustrate some of the things I'd like to add to Shattered in the future! Not all of these will be in 2019 of course, but hopefully a good number of them will be.

**Please note that this is not a specific plan or roadmap.** I'm happy to try sharing some of my broader goals with you guys, but I really try to avoid locking something down until I'm actually developing it directly. Everything I'm about to discuss is speculative and may change. These also aren't necessarily the only things I will be doing moving forward, but rather most of the major things I'm considering. Finally, not all of these things are guaranteed to happen, especially as we get further down the list.

## Higher Priority
These are things I am giving more immediate priority to, due to a mixture of importance and ease of design/implementation. Some of these might happen quite soon, but not all of them.

### Alchemy Improvements
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/alchemy.png){: .align-left}
One of the alchemy system's greatest strengths is its ability to let people recycle consumables they don't want. Most of the alchemy system works toward that goal, but the higher-tier recipes which require alchemical energy are more rigid than they probably should be. While some recipes have to be specific, I am experimenting with adjusting several recipes to work with new 'catalyst' items, which are made from any potion or any scroll. This should make higher-tier recipes more flexible and better emphasize alchemy as a tool for recycling items you don't want.

### Enemy and Boss Improvements
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/enemies.png){: .align-left}
Most of my focus in the last while has been on items and heroes, which leaves the dungeon itself quite lacking. Shattered has lots of potential for cool new enemies, especially with all the new abilities I've given to the player. In particular I'd like to see some enemies which counter common strategies, or encourage the player to engage them in different ways. Bosses are also a big issue, they are very bland and extremely easy to beat with the right strategy. This turns most bosses into 'noob traps', where the difficulty is in knowing their gimmick and not much else. I want bosses to be more engaging, probably a bit longer, and more balanced in difficulty.

### Better Allies
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/allies.png){: .align-left}
Allies are extremely cool thematically, but have always been problematic when it comes to balance and gameplay. The current sad ghost is the best example of a powerful ally, but falls flat in lots of cases when it does something you don't want it to. I have a few ideas for more ally items, which will allow for new allies which are powerful, like the ghost. I also want to spend some time looking into ally AI so that the player can give allies basic directions, or at least allies will make decisions more intelligently.

### Environment and Quest Improvements
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/quests.png){: .align-left}
Just as with enemies/bosses, this factors into the dungeon itself not being expanded as much compared to items and heroes. I started this job with the release of 0.6.0, but that new levelgen system still hasn't flexed its full muscle, leaving lots of possibilities for new rooms and layouts. Currently all floors are using a fairly basic 'loop' layout, and I'd really like to make things more variable in the future. Quests also need to be addressed. I'd like to continue making quests more unique and involved, and perhaps even add a new one to the 5th chapter.

### New Gameplay System
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/unknown.png){: .align-left}
Forgive me for being a bit vague on this one, but I don't want to spoil the surprise ;). I have plans to implement another new gameplay system, roughly on the same scale as the alchemy system introduced in 0.7.0. I expect this system to have more gameplay significance than the alchemy overhaul, but it should also be less complex and easier to implement. This system should significantly amp up player choice when it comes to heroes, allowing people to better tune their character towards a particular playstyle.

### Lore System
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/lore.png){: .align-left}
The system that the adventurer's guidebook uses was always designed to be flexible and usable for more than just tutorial text. I want to expand on the lore of the game, and I think collectible documents is the best way to do that. This creates a reward that persists between runs, and is also not in the face of people who don't want to do a bunch of reading. There are lots of possibilities here, ranging from character backstories, to flavor text, to world-building. Likely I'll start out with 1 or 2 document types per region. These would show up in a similar manner to guidebook pages, but less frequently.

### LibGDX Conversion
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/engine.png){: .align-left}
More of a behind-the-scenes adjustment, but definitely still important. Shattered Pixel Dungeon is currently coded directly for Android, without a game engine or library. Moving to a game library enables me to make lots of new technical improvements, and currently I think LibGDX is the best option. The biggest of these improvements would be getting ShatteredPD working on new platforms! Note this this is just one piece of the puzzle for eventually making shattered widely available outside of Android, but it is a big piece.

### Monetization Improvements
![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/donations.png){: .align-left}
While this may not be as fun as working on new gameplay, the donation system is now nearing 4 years without any significant changes, and could do with being spruced up. I don't know specifically what I will do with the system yet, but adding new features and expanding donation options seems quite likely. Of course, my primary motivation for working on this system is the possibility of increased income. I want this because continuing to dedicate time to working on shattered into the future requires having it be more sustainable. There are a number of approaches to monetization, but I think the first steps I take should be expanding what's already in place. While I may increase the feature set and emphasis of the donation system, I have no plans to lock gameplay or power behind donations. I also do not have any plans to implement monetization which would damage the game experience, such as advertisements or gaudy cosmetics.

### Hero Splash Art
[![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/splash.jpg){: .align-left}](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/splash-large.jpg)
Going along with better lore, I also want to give players a better visual impression of the heroes they play as. The game's art style makes it infeasible to have ingame art that's more detailed, but Shattered is hardly the first game with that limitation. I plan to work around this with visual improvements to hero select, which will feature some really nicely detailed splash arts for each hero! I'm working with [Aleksandar Komitov](https://www.artstation.com/akomitov) to make this happen, and he's already made some progress, as you can see! You can click the image to see a larger version, and even pinch to zoom on mobile!


## Longer Term
These are things I want to do, but they have less of a priority. They may depend on other things being finished first, I may not have a complete idea of how they may work, or I may not have yet decided if they're worth the time commitment. No pictures for these ones I'm afraid!

### Two New Classes
Now that all the existing classes have finally been reworked, I can start thinking about adding something new! I think there's room for 6 classes total, and I have rough ideas of how the two additional classes could work. Similarly to the existing classes, they would each focus on a general gameplay archetype, with more specific strategies evolving from items and subclasses. The high-concepts for these classes are a magic user who focuses on divine magic (as opposed to the mage, who's all about the arcane), and another melee hero who's focused around weapons.

### Challenge Overhaul
This is a perfect example of something that must wait because of its dependency on other parts of the game being more final. When the time does come to overhaul challenges, I will probably remove the existing stacking system because I think that will allow individual challenges to be more interesting. I definitely do want to preserve graduating difficulty though, so if challenges no longer stack some will definitely be harder than others.

### Badges Overhaul
Similarly to challenges, I can't really do this until other parts of the game are more concrete. The overall badge system is in a decent place, but there needs to be more content and variety to it. In particular, it's sorely lacking in specific challenging badges, and more 'progression' based badges which give newer players things to reach towards. I also want to improve the badges screen to make it easier to see what badges you're missing.

### Alternate Boss Behaviors
Bosses need to be improved directly first, but after that there is still the problem of variety. Other roguelikes and roguelites solve boss variety by having a pool of potential bosses and picking one each time. I don't think multiple bosses is a good fit for shattered though, but that doesn't mean boss fights need to be the same every time. I'd like to look into implementing variable boss mechanics, so that while you may fight the same character each time, there would be several different versions of the fight from a gameplay perspective.

### Better Shops
Shops in Shattered sell some new items at different prices, but are otherwise basically unchanged from vanilla Pixel Dungeon. While the big general stores after each boss are a nice breather, I'd like to experiment with adding in new shops which may randomly appear in the dungeon. These would have more limited and exotic items in stock. This also leads to lots of lore possibilities regarding shopkeepers. The ambitious imp is a good start, imagine if every shopkeeper was a unique character!

### Improved Tutorial
The game's tutorial was improved by the guidebook, but could still be more visual and ideally also more punctual. A better tutorial might occasionally pop up with helpful advice the first time a specific gameplay situation occurs, and a collection of these tips could be referenced from a specific menu. Many games already take this approach and are quite successfully with it. Thinking up the right situations for messages will require a lot of design consideration though, so it might make more sense to just start with improving the text and visuals of the current tutorial.

### Better Audio
More music is something I want to do, but there are technical and creative hurdles. On the technical side, there's the issue of the game's install size, as audio assets tend to be very large. Shattered is already very lightweight though, about 5mb, so expanding it with new audio wouldn't be the end of the world, but it is something I have to keep in mind. More significantly, there's the problem of actually getting new audio. There are lots of routes here, ranging from free music, commissioned music, or self-made music (assuming I don't suck at it, of course). It's a major thing to tackle, but I hope to tackle it eventually.

### New Platforms
When shattered is closer to being finished, I want to start looking into bringing it to new platforms! LibGDX is part of the equation for this, but it's also dependent on a lot of things which I cannot commit to myself, such as agreements with Watabou (dev of Pixel Dungeon) and possibly the platform owners. Initial talks with Watabou have been positive, but I need to ensure that if Shattered releases more widely it won't end up harming him by stealing sales from Pixel Dungeon. How that will happen specifically isn't decided yet, but I can say at the very least that Shattered will be paid on any platform that Pixel Dungeon is paid on, so as to avoid undercutting it. I know more availability is something that lots of people want (especially iPhone users), but I'm afraid I can't commit more to this yet.


## Stretch Goals
These are neat ideas I have which I currently do not have a place for, either due to not having a working design in my head, or because of the significant effort required. They may be extras I could work on after finishing most other tasks, assuming I'm still developing Shattered at that point.

### New Item Type
Artifacts were the first substantial update shattered ever received and were a huge success. I think there's room for one more equipped item type, a sort of 'modifier' item which is more about tweaking gameplay variables than giving direct power or utility. They would probably go into a new equip slot. The specifics of this could take a lot of forms though, so the design is quite vague for now.

### More Subclasses
With 4 (perhaps eventually 6!) class options, the 2 subclasses per-class begin to seem a little lackluster. Expanding this is a nice thought, but it requires a LOT of good ideas, I don't want to risk making a large number of boring subclasses. Additionally, adding new classes absolutely has to happen first.

### Alternate Paths
This is definitely a stretch goal, something I probably won't do unless shattered gets lots of support after v1.0.0. After beating the game for the first time, a new path through the dungeon could unlock. This path would be a sort of 'hard mode', offering new environments and enemies which tax the skills of experienced players. This is a great way to fullfill the desire of 'content after the final boss' that I frequently get, without actually increasing the length of a winning run too much. Of course, actually implementing this would take a LOT of time.

---

Well that ended up being longer than I expected! There's still definitely a fair bit left to do, but this is a far cry from previous years, where I didn't feel like there was any end in sight for Shattered. We're definitely not done yet though, so get ready for a year of Shattered updates!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/adyfxc/)