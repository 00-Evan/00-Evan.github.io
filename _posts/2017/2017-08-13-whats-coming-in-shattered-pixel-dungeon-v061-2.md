---
title: What's Coming in Shattered Pixel Dungeon v0.6.1 pt.2
---
Hey Everyone! 0.6.1 is nearing release and it’s been unfortunately difficult to write this post until now. 0.6.1 was originally meant to be a sort of variety update, with several new items. The longer I spent concepting these items though, the more I realized that they, and the systems they tie into, really deserve their own individual updates, rather than all being rolled into one. This has made it a bit tricky to write this post until now, as I didn’t want to talk about something that wouldn’t end up actually coming out in 0.6.1.

0.6.1 certainly won’t be devoid of new content though! There are still some new items, new rooms, many improvements, and a completely overhauled journal system. That new journal is what I’m going to be covering in this blog post. The journal update features expansions to the two existing journal functions (the item catalog and list of dungeon landmarks), as well as a completely new one.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/notes-and-items.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/notes-and-items.png"/>
 </a>
</figure>

The notes and items tabs (previously the journal and catalog tabs) are essentially expanded versions of their former selves. Notes now has nice headers to better separate keys and landmarks, plus some changes under the hood to allow for more expansion later. The items tab has a bit more changed: it now contains every identifiable item in the game! This not only serves as a comprehensive item info hub but also gives some permanent progression. When an item is first identified it will appear in the journal items tab, and its entry will persist between all runs. There are even some new badges for filling out entire categories in the items list. (It’s worth noting that you won’t be able to use this to determine potion colors or scroll glyphs before finding them in each run. The name and info for these items will show up, but their appearance will be hidden.)

While those two improvements are nice, the biggest addition to the journal is the new guide tab:

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/guidebook.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/guidebook.png"/>
 </a>
</figure>

The Adventurer’s Guide is a complete overhaul to the new player experience, replacing the existing signpost tutorial system. Players will be able to find pages of “The Adventurer’s Guide to Dungeoneering” semi-randomly scattered around the early floors of the dungeon. Collected pages persist between runs and can be referenced anytime. Each page covers a topic and aims to point players in the right direction without just directly telling them what to do.

Prior to this update, the main way the game directly informed players about mechanics was by having a signpost at the beginning of each floor. Originally the tips these signposts gave were very barebones, but as I started to expand them many updates ago I began to realize that the rigidity of the signpost system was going to be an issue. Signposts didn’t give me much control over how information was paced out, there was one sign per floor and that’s it, that means only 5 signposts before the first boss! Signposts also could only be read at their location, meaning the player had to read them through right away or lost the opportunity. These limitations weren’t so much of a problem back when signposts were meant to just contain one sentence tips, but I wanted to be able to provide the player with more guidance than that.

Tutorials are an extremely important part of the design of any game, and are especially important for complex discovery based games like roguelikes. Many roguelikes try to teach everything though gameplay and as a result become extremely difficult to approach for players new to the genre. This is especially bad when you consider many roguelikes have mechanics that would just not be noticed if they weren’t explained to the player. This gives rise to external guides and tutorials, and while I have nothing against them, if most players feel compelled to seek external help then I see that as a game design problem that needs to be fixed.

It’s my hope that this new tutorial will help players get past the “what the heck and I supposed to be doing” phase of the game so they can get to the more fun parts. This requires a careful balance though, as every bit of revealed information is a lost opportunity for the player to discover things themselves. It’s also very important to not turn the early stages of the game into a wall of text, as that is just as likely to turn players off as not knowing what to do. I’ve specifically designed the guidebook with these principals in mind. The guidebook is written as a reference and can be checked anytime, so it doesn’t need to be read through right away. The pacing of the guidebook can be controlled very precisely, so players aren’t overwhelmed with pages. The guidebook is also indirect in its advice as much as possible, preferring to guide players toward discovery rather than just discovering things for them.

Another benefit of this new tutorial is that I haven’t implemented it directly as a guidebook, but instead as a general ‘documents’ system. For now the only document you can find is a guidebook page, but the system is specifically designed with future expansion in mind. I want this system to house all kinds of texts that players can find in the dungeon. This gives me a lot of opportunity to expand the lore of the game while keeping it optional. This will let me do things like remove those obtrusive story popups at the beginning of each chapter and instead move and expand that information by putting it in region-specific documents.

0.6.1 is going to release very early this coming week, so be sure to let me know what you think of the new journal!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/6tgmjc/whats_coming_in_shattered_pixel_dungeon_v061_pt2)

