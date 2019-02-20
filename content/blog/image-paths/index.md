---
title: Non ascii images paths
date: "2015-05-01T22:12:03.284Z"
---

This post has non ascii image paths.

`./salty_egg_♥.jpg` - working

![Chinese Salty Egg](./salty_egg_♥.jpg)

`./salty_egg_€.jpg` - working

![Chinese Salty Egg](./salty_egg_€.jpg)

`.♥/salty_egg.jpg` - not working

![Chinese Salty Egg](.♥/salty_egg.jpg)

- Non ascii characters in file name ok.
- Non ascii characters in folder name NOT ok.
