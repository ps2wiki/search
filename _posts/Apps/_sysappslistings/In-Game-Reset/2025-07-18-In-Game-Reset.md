---
title: ⬇️ In Game Reset (IGR)
categories:
  - SAS-AA-item
tags:
  - SAS-AA-item
---

<span class="visually-hidden"><meta http-equiv="refresh" content="0; url=https://ps2wiki.github.io/sas-apps-archive/sysappslistings/In-Game-Reset/In-Game-Reset.html"></span>

An IGR (intergrated reset) binary, which will mount your default <MCE (Memory Card Emulator)> Boot Card and restart the PS2.

Most commonly used in 2 ways:

1: Use it as your `IGR.ELF` for OPL

In OPL Settings, set your In-Game-Reset path to `mc0:/SYS_IGR/IGR.ELF` or `mc1:/SYS_IGR/IGR.ELF` (mc0 for slot 1, mc1 for slot 2)
OPL will launch it when you hit the In-Game-Reset Key Combination (Unless you have Enabled Mode 6 in Game Settings), Pressing L1 + L2 + R1 + R2 + select + start in-game will stop a game and launch the ELF you set for IGR path, which will switch the MCE device back to it's assigned Boot Card, and then restart the PS2.
This is especially useful for using the Game-ID Card Switching feature of MCE devices, as it will bring you back to your FMCB/PS2BBL/Tuna card when exiting a game.

2: Install it as a FMCB menu item with Free MCBoot Configurator

If you have multiple cards with exploits on them on your MCE and want to quickly get back to Boot Card, this would allow you to do so. Simply add it to the cards that need a way back to Boot Card, and map the addition with Free MCBoot Configurator.
Scroll to it and hit `X` when FMCB starts to load your default Boot Card on the MCE Device.
