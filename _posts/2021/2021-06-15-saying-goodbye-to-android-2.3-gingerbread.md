---
title: "Saying Goodbye to Android 2.3 Gingerbread"
excerpt: "v0.9.3 will be the last version of Shattered Pixel Dungeon to support Android 2.3 and 3. I wanted to write a little blog post to summarize why this is happening, and to reminisce a bit on these versions of Android from 2010 and 2011."

header:
  image: /assets/images/2021/2021-06-15/header.jpg
  teaser: /assets/images/2021/2021-06-15/header.jpg
  width: 1260px

#These tags are parsed by Shattered Pixel Dungeon to determine display in its news feed
tags: ["SHPD_INGAME", "SHPD_ICON_v464: ICON: PREFS"]
---

Hey Dungeoneers!

Almost exactly 2 years ago, with the release of v0.7.3, [I announced that Shattered would be dropping support for Android 2.2 Froyo](/blog/saying-goodbye-to-android-2.2-froyo.html). Now, unfortunately, it's time to say goodbye to more legacy Android versions.

v0.9.3 will be the last version of Shattered Pixel Dungeon to support <span style="color:orangered">Android 2.3 Gingerbread</span>, and the less popular <span style="color:gold">Android 3 Honeycomb</span>. I'll try to keep support for <span style="color:deepskyblue">Android 4.0 Ice Cream Sandwich</span> going as long as I can, but that one may be near the end of its support life as well.

Just like with Froyo, I wanted to write a little blog post to summarize why this is happening, and to reminisce a bit on these versions of Android from 2010 and 2011.[^1]

## Why Drop Support?

Android 2.3 - 4.0 represents a period of major technical changes for the Android platform. Android 4.0 also brought a complete UI refresh called 'holo', which was the first time Android had a consistent visual design.

Phones were also roughly doubling in processing power each year during this period. Phones from 2010 topped out at around a single core 1ghz processor, such as my first phone, a [Nexus S](https://www.gsmarena.com/samsung_google_nexus_s-3620.php). In 2011 though [their successors](https://www.gsmarena.com/samsung_galaxy_nexus_i9250-4219.php) could easily have dual core 1.2ghz processors.

Supporting these old Android versions means supporting all of the hardware and software from just before this major transition, which can often cause some technical trouble.

For Shattered specifically, two game libraries dropped support for Android 2.3 and 3 in mid 2020: [libGDX](https://libgdx.com/) and [Google Play Billing](https://developer.android.com/google/play/billing). For now I've been making do with using outdated versions, but as I look to [release on new platforms](/blog/shattered-pixel-dungeon-v093.html#whats-coming-next), and as an [update deadline by Google](https://developer.android.com/google/play/billing/deprecation-faq) starts to loom, I'd really like to update to the latest versions. Some parts of libGDX also recently dropped support for Android 4.0, but for the moment I should be able to work around that.

## Legacy Android by the Numbers

Just like with Android 2.2, it's important to also look at how many devices this change will actually impact.

Firstly, let's take a look at the proportion of all devices on Google Play running a particular Android version at five key dates:

| Android Version | Vanilla release (Dec 2012) | Shattered release (Aug 2014) | Shattered Visual Overhaul (Feb 2017) | Shattered drops 2.2 (June 2019) | Shattered drops 2.3 (June 2021) |
|:--------|:-------:|:-------:|:------:|:------:|:------:|
| 2.1-    | 3.1%    | -       | -      | -      | -      |
| 2.2     | 10.3%   | 0.7%    | -      | -      | -      |
| 2.3     | 50.8%   | 13.6%   | 1.0%   | 0.3%   | -      |
| 3.X     | 1.6%    | -       | -      | -      | -      |
| 4.0     | 27.5%   | 10.6%   | 1.0%   | 0.3%   | 0.1%   |
|**Total**|**93.3%**|**24.9%**|**2.0%**|**0.6%**|**0.1%**|

<figcaption markdown="1" class="align-center text-center">
  Data taken from [Bidouille's android version chart](https://www.bidouille.org/misc/androidcharts), and [AppBrain's Android version chart](https://www.appbrain.com/stats/top-android-sdk-versions).[^2]
</figcaption>

When PD originally launched these legacy versions where almost the entire Android ecosystem! Even when Shattered launched they were still at almost 25% of all devices. However, today only Android 4.0 has enough devices left to even register in this data. Shattered's legacy comes from an era where supporting these Android versions was absolutely necessary, but in 2021 the number of devices on these versions is extremely tiny.

What about the device share for Shattered in particular though? Here's a chart showing Shattered's device share for Android 2.2 to 4.0 starting in October 2016:

[![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/chart-1.png)](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/chart-1.png){: .align-center}

In October 2016 these legacy Android versions were almost 4% of Shattered installs combined, twice the rate they had in Google Play overall! From more approximate data around when Shattered launched (Aug 2014), Android 2.2 was somewhere around 2.5% of all devices and 2.3 and 4.0 were both about 8%.

As time has gone on usage of these legacy Android versions have fallen substantially though, especially after 2018. Let's zoom in 2019 and onward for a better look at where things are today:

[![](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/chart-2.png)](/assets/images/{{page.date|date:'%Y/%Y-%m-%d'}}/chart-2.png){: .align-center}

After their drop in 2018, all of the legacy versions were steady for a while. 2.2 and 3 faded first and went toward 0% in late 2020. Android 2.3 lasted longer, but has been dropping sharply over this year. 4.0 has held on a bit better, even growing in 2020, but is now falling away at a slower rate.

Just like with Android 2.2 in 2019, it seems that the vast majority of the devices which I am ending support for have already stopped playing Shattered.

## What About Other Android Versions?

Even just going up to Android 4.1 bumps the user count considerably. Here's the current proportion of each Android version, first for all apps, then for Shattered, and then the % difference between those:

|      | 4.0- | 4.1-3 | 4.4  | 5    | 6    | 7    | 8    | 9   | 10  | 11  |
|:-----|:----:|:-----:|:----:|:----:|:----:|:----:|:----:|:---:|:---:|:---:|
| All  | 0.1% | 0.6%  | 1.5% | 4.2% | 5.3% | 7.6% | 14%  | 19% | 35% | 12% |  
| SHPD | 0.1% | 0.8%  | 1.2% | 1.8% | 2.6% | 5.7% | 9.2% | 17% | 34% | 28% |
| Diff | ~0%  | <span style="color:yellowgreen">33%</span> | <span style="color:gold">-20%</span> | <span style="color:orangered">-57%</span> | <span style="color:orangered">-51%</span> | <span style="color:gold">-25%</span> | <span style="color:darkorange">-34%</span> | <span style="color:gold;">-11%</span> | -3% | <span style="color:lime">133%</span> |

<figcaption markdown="1" class="align-center text-center">
  Data from Shattered's own Google Play numbers, and [AppBrain's Android version chart](https://www.appbrain.com/stats/top-android-sdk-versions).[^2]
</figcaption>

One thing that interests me here is that Shattered used to have a much higher proportion of old android devices than the average. This made sense, if most apps had stopped supporting an Android version, Shattered would have more devices on that version than the average. This doesn't look like it's the case anymore though. Shattered now has a meager lead for Android 4.3 and older, but otherwise has **LESS** old android devices than average!

In fact, Shattered has more than twice the average number of devices on Android 11! It seems that the days of Shattered having a large number of players on ancient devices have passed. Nowadays the game's more complex nature causes it to skew heavily toward more dedicated users, who tend to use more modern devices.

I'll keep support going as long as I can for each Android version, but it's nice to know that Shattered has largely outlasted the older devices that it used to support.

---

I'm going to be making another blog post soon, to talk more about the next update. I'm currently planning for this post to be late this month, or possibly early July. If you want quicker, shorter updates about what I'm working on, consider following me on [Twitter](https://twitter.com/ShatteredPixel)!

[![](/assets/images/icons/patreon.png){: .align-left .rounded}](https://www.patreon.com/ShatteredPixel) If you enjoy Shattered and want to help me keep making it, [please consider supporting me on Patreon!](https://www.patreon.com/ShatteredPixel) Patrons get access to exclusive weekly mini blogs about upcoming updates, a monthly Q&A livestream, and also help determine content direction through community polls!

[You can discuss this blog post on the Pixel Dungeon Subreddit!](https://www.reddit.com/r/PixelDungeon/comments/o0jcdw/)

---

[^1]: The title image for this blog was taken from Google's Android history page, which has wonderful graphics for each version up to 6.0. It's unfortunately no longer online, but can be accessed (with a little jank) via the [wayback machine](http://web.archive.org/web/*/https://www.android.com/intl/en_ca/history/#/froyo).

[^2]: The AppBrain's charts aren't perfectly accurate to all devices on Google Play, but it's the best we've got since Google stopped reporting their own numbers. From looking at past data, it seems AppBrain skews slightly in favor of more modern Android versions, which only strengthens the points I made in this post.