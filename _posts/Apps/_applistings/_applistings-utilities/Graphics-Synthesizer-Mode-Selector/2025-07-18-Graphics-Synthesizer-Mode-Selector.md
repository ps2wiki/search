---
title: ⬇️ Graphics Synthesizer Mode Selector (GSM)
categories:
  - SAS-AA-item
tags:
  - SAS-AA-item
---

<span class="visually-hidden"><meta http-equiv="refresh" content="0; url=https://ps2wiki.github.io/sas-apps-archive/applistings-utilities/Graphics-Synthesizer-Mode-Selector/Graphics-Synthesizer-Mode-Selector.html"></span>

GSM intends to make on-the-fly conversion from the original graphic mode of PS2 game (or application) choosen by user, to the ones he/she wants to force.

One of benefits of using GSM is have a progressive scan output for a game originally designed to use interlace output. Or have a VGA output in your CRT/LCD Monitor for your preferred games. It seems great, isn't ii?

Well, GSM just makes a simple upscaling. It doesn't making interpolation (i.e. it doesn't add extra pixels / lines). So it doesn't increase the internal(=original=source) resolution, only the output (=forced=target) one.

So, there is no miracle here... The greater the quality of source (original) resolution of the game, the better will be the results that will be displayed on target (forced) resolutions - specially on the higher ones, where the images naturally tend to be pixelized.

Newer versions of GSM are integrated into [Open PS2 Loader](https://github.com/ps2homebrew/Open-PS2-Loader).
