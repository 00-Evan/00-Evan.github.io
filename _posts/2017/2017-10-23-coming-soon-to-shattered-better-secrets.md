---
title: 'Coming Soon to Shattered: Better Secrets!'
excerpt: "In this blog I’ll be covering how existing secret mechanics are changing, and what totally new stuff is coming."
---
Hey everyone, the release of 0.6.2 is imminent! But first, one more blog!

In this blog I’ll be covering how existing secret mechanics are changing, and what totally new stuff is coming.

## Existing Secrets

Currently there are two types of secrets that exist in the game: hidden doors and traps. Traps are semi-randomly spread through a floor of the dungeon, with the frequency and danger of traps increasing as the game progresses. I’ve already talked a bunch about traps so if you’re interest in them read more [Here.](/blog/coming-soon-to-shattered-better-traps.html) Regular doors are also randomly hidden, again with chances increasing as the game progresses. With one or two exceptions, doors are never specifically hidden, it’s always random.

You might be thinking that I’ve forgotten a 3rd type of secret: hidden rooms. This isn’t the case though, because as far as the game’s logic is concerned hidden rooms don’t exist. The rooms which you may think of as being hidden are just regular rooms that, through chance, had all their doors set to hidden. That might seem nit-picky, but this is a very important distinction from a game design perspective.

## Hidden Doors

Hidden doors in their current state can completely hide key progression items, quest characters, and sometimes even large sections of a level. These are things that weren’t designed around being totally hidden, and really shouldn’t be. While hiding some doors can be a really nice way to increase layout variety, hiding entire rooms just ends up being annoying more often than interesting.

In 0.6.2 I’m changing this so that any door can still be randomly hidden, but there is an added condition to the randomness. Every standard room must have an uninterrupted visible path to the level entrance. If hiding a particular door would break that path then the door is not hidden. This makes randomly hidden doors less of an obstacle, and more of an element of floor layout variety.

## What’s New?

Of course, it would hardly be worth an entire blog post if that was all that I changed. If randomly hidden doors are a bit problematic, what would happen if they were specifically hidden instead? This leads into the real interesting change here: secret rooms. Like special rooms, they are specifically chosen and placed into a level, but unlike special rooms they are always totally hidden. This opens up so many design possibilities, as now these rooms can be made with the intention of being completely hidden.

Most significantly, this means I can ensure these rooms focus on rewarding the player in ways that are appropriate for a secret. You’ll rarely if ever find amazing gear, but you will find more of the game’s rarer consumables, and perhaps a few new things as well. This is important as it helps reinforce that secret rooms are optional. They should feel great to find and explore, but shouldn’t feel necessary. This is in direct contrast to things like upgrade items and weapons/armor, which are necessary and shouldn’t be hidden very often as a result.

There will be 12 secret room types to start out. Some of them are basically secret versions of regular special rooms, but others are entirely new with some interesting puzzles built into them. Just as with new levelgen, there’s a lot of room for expansion here. I’ve already got a few ideas for how the secret room system could be expanded further.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/secret-rooms.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/secret-rooms.png"/>
  <figcaption>
   Some examples of new secret rooms coming in 0.6.2
  </figcaption>
 </a>
</figure>

In compensation for all this, hidden doors are going to become much harder to detect automatically and searching is going to cost significantly more hunger. I don’t want to make finding all of these new rooms too easy, but hopefully missing them won’t be too frustrating either. This also nicely increases the value of food for experienced players, as excess food now rewards you with the ability to search more. Secret room spawn rates are also fairly consistent, so I expected experienced players will eventually get a sense for whether they’ve missed a secret or not.

Because of this more purposeful design, it’s also easier for me to control and vary how many of these rooms appear. You may recall that back when I [talked about the rogue rework](/blog/coming-soon-to-shattered-the-rogue-rework.html) I mentioned that he would be able to find more secrets. This was what I was referring to. In addition to his greater search radius, the rogue will be able to find more of these secret rooms in the dungeon. Specifically, the game will spawn roughly 25% more secret rooms over the course of the run, and their spawn rate will be more consistent, so it’ll be a bit easier to determine whether you’ve missed a room or not. So, if you’re hungry to find all the secrets of the dungeon, the rogue is the class for you!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/78a5ta/coming_soon_to_shattered_better_secrets/)

