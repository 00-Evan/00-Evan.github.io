---
title: "Coming Soon to Shattered: Alchemy Streamlining!"
header:
  image: /assets/images/2019/2019-01-25/header.png
  teaser: /assets/images/2019/2019-01-25/header.png
  width: 1280px
---

Hey Folks, remember that 2019 blog post? Well, I'm getting the first item crossed off that list right now! 0.7.2 is going to be a grab-bag of various improvements. I haven't locked down what all of them will be yet, but one is definitely some improvements to alchemy!

## The Problem

The primarily motivation behind the alchemy system was always to give new uses to consumables which the player may not otherwise want to use. Most recipes already fulfill this well, especially for seeds and runestones, but the top-end recipes stray away from this by being too rigid with their ingredients. 

However, making these recipes more flexible doesn't work well as you can easily get recipe overlap. As a simple example, consider two recipes: 'liquid flame + any potion' and 'toxic gas + any potion'. If the player puts a liquid flame and toxic gas into the alchemy pot, the system has no way to know which recipe the user meant without getting into complexities like how the items are ordered. Now imagine 20+ high-end recipes which may use 'any potion' or 'any scroll', and you'll realize why I decided to avoid this.

It's very clear that the rigidity of top-end recipes needs to go though, so I went back to the drawing board and tried to think of whether there was another way to make recipes work with any potion or any scroll.

## Introducing Catalysts!

The idea I settled on was a new item type: Catalysts! Catalysts are made with any potion/scroll plus a single seed/runestone, and very small amount of alchemical energy. This produces either an alchemical catalyst, which is used in making brews and elixirs, or an arcane catalyst, which is used in creating spells. Catalysts mean I can avoid recipe overlap while still making recipes which work more flexibly. 

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/catalysts.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/catalysts.png"/>
  <figcaption>
   An alchemical catalyst on the left and arcane on the right.
  </figcaption>
 </a>
</figure>

Many top-end recipes that used to be specific are now going to make use of a primary item plus a catalyst instead. Catalysts also provide a bit of usefulness on their own as well. Alchemical catalysts can be used for a random potion effect and arcane catalysts can give a random scroll effect. Of course, these items will not randomly produce the effects of progression items such as scrolls of upgrade or potions of strength.

## Other Alchemy Adjustments

Catalysts let me streamline the system in other ways as well. I originally created combination brews and elixirs because I wanted there to be some ways to spend very small amounts of alchemical energy, but catalysts now fulfill that purpose. So, I've decided to remove those combination items, as they offered no unique gameplay and mainly just ended up cluttered the system. The frostfire brew in particular did have a bit of uniqueness to it though, so I will likely look at letting that one return at some point.

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/guidebook.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/guidebook.png"/>
  <figcaption>
   How the final 3 guidebook pages look with catalysts added and combo items removed.<br>Note that I expect catalysts to mix up the balancing, so some of these recipes may change.
  </figcaption>
 </a>
</figure>

I'm also revising alchemy guidebook page droprate. Guidebook page drops now stops after page 3/10 in the sewers, and page 7/10 in the prison, but if you make it to the late stages of the game quickly you'll get multiple pages at once. Infact a single won run will now fill all 10 pages, where it used to fill 5/10. I want to balance the guidebook so that finding pages doesn't stand in the way of experienced players, but also doesn't reveal too much too quickly for new players. Hopefully this adjustment better balances that.

Lastly, I'm taking this as an opportunity to revise how heavily alchemy leans on the identification system. For some recipes obviously it will be necessary for items to be IDed, but for others I want to relax things a bit. In 0.7.2 you won't need IDed potions/scrolls to create catalysts or exotics. Of course, if you use an unknown potion/scroll to make an exotic, the resulting exotic will also be unknown.

---

I'm very happy with the core of the alchemy system, but I'm going to keep tweaking the surface-layer stuff going forward to improve the system. I think there's a great benefit to having this big consumable crafting system, but I'd like to have that benefit be in as manageable a package as possible.

I also want to start expanding the system a little bit at a time once I feel the existing content is in a good place. There's lots of opportunities for new spells/brews/elixirs, and some of the balance on runestones and exotics could easily be improved as well.

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/ajx25y/)