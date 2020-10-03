---
title: "Saying Goodbye to Android 2.2 Froyo"
excerpt: "I've got a slightly different blog post for you this time. v0.7.3 is the last version of Shattered Pixel Dungeon which will support Android 2.2 Froyo, so I thought I'd explain why, and give a retrospective on Froyo support in Shattered Pixel Dungeon."

header:
  image: /assets/images/2019/2019-06-03/header.png
  teaser: /assets/images/2019/2019-06-03/header.png
  width: 1260px

#This field is parsed by Shattered Pixel Dungeon to display an ingame icon in its news feed
tag: ["ICON: PREFS", "SHPD_INGAME"]
---

Hey Dungeoneers, I've got a slightly different blog post for you this time. v0.7.3 is the last version of Shattered Pixel Dungeon which will support Android 2.2 Froyo, so I thought I'd explain why, and give a retrospective on Froyo support in Shattered Pixel Dungeon.

Shattered is a very low-spec game, and I've always tried to support as many devices as possible, including very old Android versions. Over the last four and a half years of developing Shattered I've made a point of supporting every device the original Pixel Dungeon supported when it was released. There are two main reasons why I'm now changing that policy.

## Technical Issues

Android 2.2 Froyo was originally released in mid 2010 and was succeeded by Android 2.3 Gingerbread in late 2010. There were a lot of technical improvements in both of these updates, but of course an app can only use all of those improvements if it's running on an Android 2.3+ device. This makes supporting Android 2.2 somewhat difficult in comparison to 2.3+, as Shattered Pixel Dungeon has to contain special logic to accommodate Android 2.2 devices when it would otherwise use Android 2.3+ logic. This isn't the hardest thing to do though, and for years I have managed to support Android 2.2 regardless of some technical annoyances.

Unfortunately, recently this situation has changed due to two factors. The first is a [new Google policy regarding native code in Android apps.](https://android-developers.googleblog.com/2019/01/get-your-apps-ready-for-64-bit.html) Shattered uses native code in a couple places to support Android 2.2. This code is built for older 32-bit processors, which makes sense as it will only run on Android 2.2 devices. Google's new policies require that all native code must be built for newer 64-bit processors in addition to the older ones. This policy makes a lot of sense for most apps, but it's a bit awkward for Shattered as it means I have to include 64-bit native code that will never actually get used.

While adding native code that will never be used is annoying, I can easily do that if needed. The real issue that's making supporting Android 2.2 tough is support from multiplatform game libraries. As I [mentioned in my 2019 blog](/blog/shattered-pixel-dungeon-in-2019.html#libgdx-conversion), I plan to migrate Shattered to a multiplatform codebase so that I can one day release on new platforms. Building a multiplatform codebase from scratch is a tremendous amount of work though, so I'll be using a game library to help with the process. Unfortunately, the library which I am planning to use, LibGDX, has not supported Android 2.2 since 2017. While it is not impossible to make LibGDX work with Android 2.2, doing so would require a very large amount of work, far more than what I've had to do up to this point to support Android 2.2.

## The Number of Froyo Users

The other side of the coin when it comes to supporting Froyo is how many players are actually benefiting from that support. Even if supporting Froyo is difficult, it would be worth it if a lot of Froyo devices are still playing the game. Conveniently, I have access to some data about this!

Firstly let's take a look at the proportion of devices running a particular Android version at four key dates. I've included the release of Vanilla Pixel Dungeon, release of Shattered, Shattered v0.5.0(the visual overhaul update), and present day. I included the visual overhaul update as it is both a nice midpoint between the other dates, and it contained more logic to accommodate Android 2.2 than any other update.

| Android Version | Vanilla release (Dec 2012) | Shattered release (Aug 2014) | Shattered Visual Overhaul (Feb 2017) | Shattered drops Android 2.2 (June 2019) |
|-----------------|:--------------------------:|:----------------------------:|:------------------------------------:|:---------------------------------------:|
| 2.1-            | 0.4%                       | 0.0%                         | 0.0%                                 | 0.0%                                    |
| 2.2             | 9.0%                       | 0.7%                         | 0.0%                                 | 0.0%                                    |
| 2.3             | 50.8%                      | 13.5%                        | 1.0%                                 | 0.3%                                    |
| 3.X             | 1.6%                       | 0.0%                         | 0.0%                                 | 0.0%                                    |
| 4.0             | 27.5%                      | 10.6%                        | 1.0%                                 | 0.3%                                    |
| 4.1+            | 6.7%                       | 75.2%                        | 98.0%                                | 99.4%                                   |

<figcaption class="align-center text-center">
  Percentage of devices which connected to Google Play in a given month<br>
  All numbers are rounded to one decimal place.
</figcaption>
<br>
These numbers really showcase why Shattered runs so well on older phones. Pixel Dungeon was originally developed with Android 2.2 and 2.3 era hardware in mind, and I've worked to keep Shattered's performance consistent or better. When Shattered first released 3/4 of devices were already on OS versions at or above 4.1, and Android 2.2 was below 1% of all devices.

In January 2017, just a month before Shattered's big visual overhaul update, Android 2.2 dropped below 0.05% of all devices and was rounded to 0%. The number of overall legacy devices has continued to drop since then, however Android 2.3 and 4.0 are holding strong and have been at a consistent 0.3% since about this time last year.

The overall Android numbers don't tell the whole story though, Shattered has always had a larger group of users on legacy devices because it runs so well on them. let's take a look at the number of active Android 2.2 devices with Shattered installed: 

<figure>
 <a href="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/froyo-users.png" class="align-center text-center">
  <img src="/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/froyo-users.png"/>
  <figcaption>
   Google Play installs on active Android 2.2 devices, from June 2017 to June 2019.<br>
   An active install is an installation of the game on a device which has been used in the last 30 days.
  </figcaption>
 </a>
</figure>

Despite being at 0% of overall devices since the start of 2017, Froyo maintained a significant number of Shattered installs for quite a while past that! There were ~400 installs in mid 2017, but that number has steadily dropped to ~10 in mid 2019. That level-off followed by a spike after July 2018 was a data collection error on Google's part. When I released v0.5.0 I still had hundreds of Android 2.2 users, but now almost all of them have moved on.

---

In conclusion, the incoming technical challenges coupled with the extremely small number of active installs makes it infeasible for me to continue supporting Android 2.2. Google's libraries (such as play services) haven't supported 2.2 since 2017, and Shattered is one of the only apps that still supports 2.2 with updates. Previously I justified this because there were still some Android 2.2 users, but it now seems clear that the rest of the world has moved on, and so it's time for Shattered to move on as well.

I hope that I can continue supporting other legacy devices at least until they reach a similar user count to Froyo. Android 2.3 Gingerbread should be supported for the foreseeable future, as it still works with LibGDX and has ~100 active installs which are declining at a fairly slow rate.

If you're interesting in Android history, here are a few resources you can check out:
- Bidouille has a [lovely chart which contains all the historical info on Android version usage.](https://www.bidouille.org/misc/androidcharts) I used data in the chart to build the table on Android versions in this blog.
- Good has a [really fancy webpage on Android's history.](https://www.android.com/intl/en_ca/history/#/froyo) This blog's header image is adapted from the visuals on that page.
- If you want a more detailed page on Android history, take a look at [Wikipedia's Android history article.](https://en.wikipedia.org/wiki/Android_version_history)

---

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/bwem5d/)

[![](/assets/images/patreon-icon.png){: .align-left}](https://www.patreon.com/ShatteredPixel) And lastly, [I have a Patreon now!](https://www.patreon.com/ShatteredPixel) If you'd like to support the development of Shattered Pixel Dungeon, please consider either making a purchase in the Google Play version of the game, or [supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) The Patreon is currently in a soft-launch state, and I intend to expand it based on interest and feedback.