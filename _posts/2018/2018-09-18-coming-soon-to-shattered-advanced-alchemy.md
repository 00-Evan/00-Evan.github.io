---
title: 'Coming Soon to Shattered: Advanced Alchemy'
---
Hey Everyone! Despite delays, we are now getting close to the release of 0.7.0! I’m afraid I can’t commit to a release date just yet, but late this month seems quite possible. I’ve consistently missed my deadlines with 0.7.0 so far though, so take that with a bit of salt =S. I’m still working at it though, here’s one more blog!

Last time, I covered the alchemy system in more depth, including talking about the new customization options it’s going to give to scrolls and potions, and how there is a focus on providing new ways to use and combine items. This ability to remix and modify potions and scrolls is great, but any crafting system worth its salt should also provide ways to create new powerful and unique items as well! This time around I’m focusing on those, which make up the final major new additions coming in 0.7.0.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/brews-and-elixirs.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/brews-and-elixirs.png"/>
  <figcaption>
   <strong>Firstly, Take a look at Brews and Elixirs!</strong><br>(note that most of the sprites in this blog are still a bit WIP. I’m going to try and make them look a bit fancier before release)
  </figcaption>
 </a>
</figure>

Elixirs and Brews are essentially single use super-potions, and primarily use potions as their ingredients. Elixirs focus on restorative effects and buffs, while brews are all about damaging and debuffing enemies. Some are simple combination items, while others grant entirely new effects! Here are a few examples:

- **Wicked Brews** are created by mixing a potion of toxic gas and a potion of paralytic gas. This simple combination brew acts as both of the potions at once, allowing players to use the classic toxic + paralysis combo a little faster.
- **Elixirs of Honeyed Healing** are created by mixing a potion of healing and a shattered honeypot. This elixir can be thrown to heal allies, and can also be used on bees to calm them, turning them into more of an ally.
- **Infernal Brews** are created by mixing a potion of dragon’s breath (which is the exotic variant of liquid flame) and a potion of liquid flame. This brew spreads fire like a gas, creating a huge lasting area of flame! You’ll need to be careful with this one, unless you have ways to resist fire.
- **Elixirs of Dragon’s Blood** are created by mixing a potion of liquid flame and a potion of purity. This elixir temporarily makes the hero invulnerable to fire, and grants a burning effect to their regular attacks. Conveniently, this elixir combos well with an infernal brew, though you’ll need to save up a lot of liquid flame potions.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/spells.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/spells.png"/>
  <figcaption>
   There’s more opportunity for flexibility than just with single use items though…<br><strong>Introducing spells!</strong>
  </figcaption>
 </a>
</figure>

Spells are multi-use items (stackable, essentially) which are primarily made using scrolls. They take the form of pretty crystals which precipitate out of an alchemy pot, and are invoked to create a wide variety of effects. Spells are a huge game-changer design-wise for me, because they are a perfect place to put interesting mechanics which aren’t strong enough to be part of equipment, or generally useful enough to be a randomly dropped consumable with a single use. Here are a few examples:

- **Aqua blast** is created by mixing a scroll of identification with a potion of storm clouds (exotic levitation). This spell creates a small pool of water at a target location, ideal for situations where you want water-synergy against a specific target, rather than a whole area. The blast will even very briefly stun enemies caught in the center, though it won’t harm them.
- **Magical porter** is created by mixing a scroll of mirror image with a merchant’s beacon. This spell allows a player to remotely send items deeper into the dungeon, rather than selling them to a shop. This is more flexible than a merchant’s beacon, but does have the added recipe cost.
- **Alchemize** is created by mixing a scroll of recharging with a potion of liquid flame. This spell allows the caster to perform alchemy without the need for an alchemy pot! Its usage is limited however…
- **Beacon of Returning** is created by mixing a scroll of passage (exotic teleportation) and a scroll of magic mapping. As the name implies, this powerful spell lets you set a location, and return to it! The massive convenience factor of Lloyd’s beacon is no longer limited to people who get a lucky drop from Goo!

With all these new more powerful items, there needs to be a limiting factor though. These recipes are all limited by a new resource: Alchemical Energy. Every pot has a finite amount of energy, and many alchemy recipes will consume that energy. Naturally, some recipes (such as the ones discussed in previous blogs) will cost no energy, and ones which add little power ontop of the ingredients used will be quite cheap. Limited energy allows me to make recipes satisfyingly powerful without making players feel forced to put literally all of their items into the alchemy system. It also allows me to balance recipes costs in a variety of interesting ways, simple ingredients that produce powerful results will cost a lot of energy.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/toolkit.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/toolkit.png"/>
  <figcaption>
   A new resource also presents an opportunity for an item that interacts with it directly. Infact, a very long time ago Shattered had a dedicated alchemy artifact…<br><strong>Return of the Alchemist’s toolkit!</strong>
  </figcaption>
 </a>
</figure>

The Alchemist’s toolkit was originally added in Shattered Pixel Dungeon v0.2.3, and was removed in v0.3.0. It increased the number of potions you could get from seeds, and I ended up removing it because it was extremely powerful in regrowth runs and useless otherwise. It has laid dormant for over 3 years, and now that alchemy is becoming so much more interesting it is finally time for it to come back!

The toolkit now acts as the best way to maximize the amount of alchemical energy in a run, in a similar way to the horn of plenty. The toolkit can be used on alchemy pots, will absorb the energy contained in them, and in exchange will steadily pay you back with energy as you gain exp. When equipped, the toolkit can also act as a portable alchemy pot, so long as no enemies are nearby. Just like the horn of plenty, this allows you to lose energy in the short-term in exchange for having more energy over the course of your run.

## A Note About Complexity

Gameplay-wise, 0.7.0 is easily the largest update shattered has ever received, with about 80 new items in total. This puts the total amount of items craftable through alchemy at over 100! I’m beginning to move my development direction away from just remixing systems which are already in the game, and instead adding entirely new things, such as this new crafting system. Naturally adding new systems gives lots of opportunity for adding complexity. I’m not going to be afraid to crank the complexity dial when appropriate, but I’m definitely aware that it’s quite easy to have too much of it.

I think the new alchemy system is pushing it a bit, but there is an incredible gameplay payoff which justifies it. Most notably, alchemy provides me with a way to add all kinds of awesome and interesting items without diluting the regular item pool. There are so many times where I’ve had ideas for an item but stopped myself because it just wouldn’t fit in as a piece of equipment or a regularly dropped consumable. Alchemy solves this problem by giving me a place to introduce those ideas to the game in the form of alchemy recipes.

As always, I’m going to be eager to see how the system plays when it goes live, and I won’t shy away from making adjustments as needed. I have made efforts to try and lessen the up-front complexity of the alchemy system though:

- The game will have an ‘alchemy guidebook’, which functions very similarly to the adventurer’s guide. The player will find pages steadily as they adventure, which means the full potency of the alchemy system will be revealed in manageable pieces. The guidebook also tries to sort recipes based on clear categories, which makes it easier to remember all the different recipes and quickly reference the ones you want.
- Alchemy only occurs at alchemy pots, and when the player interacts with them they are now whisked away into a separate game interface. I want 'alchemy mode’ and 'gameplay mode’ to be quite separate visually, which encourages a switch in mindset and helps prevent people from constantly thinking about alchemy options. Of course, alchemy on-the-go is possible with items such as the alchemist’s toolkit.
- Not all recipes involve complicated ingredients and situationally useful produce. There are a variety of simple recipes with simple outputs which help warm people up to the alchemy system.
- The alchemy system is entirely optional. While I don’t want players to ignore it, they are never forced to use it as part of regular gameplay. Crafting intelligently will be an advantage obviously, but there is no point in the game where alchemy is mandatory to progress.

I’m always happy to hear what people think, and so I’ll be paying close attention to feedback on 0.7.0 when it does finally go live. If there are problems (balance, design etc.) I will be paying attention and tweaking post-release. There’s no way to do an update this big without a few growing pains!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/9gzrg4/)

