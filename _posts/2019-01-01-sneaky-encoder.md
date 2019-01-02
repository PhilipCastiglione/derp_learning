---
layout: post
title:  SneakyGAN
---

Stanford and Google recently trained a CycleGAN to lie to them. More specifically,
researchers tried to build a system that would translate aerial photos to
street-view photos, then generate aerial photos from those that resembled the
originals.

![maps](assets/images/mapdetails.jpg)

_Wait, how did those trees get back there?_

In fact, they trained a system that translated aerial photos to street-view
photos ...secretly encoded with visually imperceptible data that the GAN used to
generate approximations of the original aerial photos again. Naughty little GAN!

[TLDR; measure the right things!](https://techcrunch.com/2018/12/31/this-clever-ai-hid-data-from-its-creators-to-cheat-at-its-appointed-task/)
