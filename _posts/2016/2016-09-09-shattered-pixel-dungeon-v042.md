---
title: 'Shattered Pixel Dungeon v0.4.2: Performance Improvements!'
---
0.4.2 is all about improving the efficiency of Shattered’s game engine, reducing hitching and improving framerates on a large number of devices! This is both so the game plays better now, and so I have more headroom for future changes.

There are also a few balance tweaks, but nothing too major.

The update is available now through Google Play, and will be available to desktop, amazon, and f-droid users within a day or two, along with the source release.

Thanks so much for playing, if you have any feedback don’t hesitate to either contact me here, or email me directly: Evan@ShatteredPixel.com

Here’s a full list of changes:

```
Optimizations:
- Many general performance improvements
- Game now uses 2 CPU cores, up from 1
- Reduced hitching on many devices
- Framerate improvements for older devices
- Game size reduced by ~10%

Balance Changes:
- Spear and Glaive damage reduced
- Runic blade damage reduced
- Grim enchant now procs more often
- Glyph of stone adds more weight
- Glyph of potential procs less often
- Wand of Fireblast less dangerous to caster
- Wand of Pris. Light reveal area reduced
- Ring of Wealth slightly more effective
- Ring of Sharpshooting gives more accuracy
```

To give an idea of what sort of fps improvements you can expect, here are a few numbers from my tester devices:

| GPU                    | Resolution | 0.4.1  | 0.4.2  |
| ---------------------- | ---------- | ------ | ------ |
| PowerVR SGX530 @110mhz | 480x854    | 15 fps | 40 fps |
| Adreno 200 @133mhz     | 320x480    | 50 fps | 60 fps |
| Adreno 200 @133mhz     | 480x800    | 42 fps | 50 fps |

For anyone rocking an older PowerVR gpu, the game just got A LOT smoother, and the very common Adreno 200 also got a nice boost. Note that old phones with weaker cpus may also see fps boosts from improvements to cpu usage, but that is harder to measure.

All devices will experience much less hitching as well, as rendering and game logic now run independently, rather than having to wait for one another to finish.

I may write or record a blog at some point for those who are interested in the details of the technical improvements. Let me know if you would be interested in seeing that.
