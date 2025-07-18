---
title: '⬇️ [EMU] Xbox 2 PlayStation Emulator'
categories:
  - SAS-AA-item
tags:
  - SAS-AA-item
---

<span class="visually-hidden"><meta http-equiv="refresh" content="0; url=https://ps2wiki.github.io/sas-apps-archive/applistings-emulators/Xbox-2-PlayStation/Xbox-2-PlayStation.html"></span>

X2P is an Xbox emulator for the PlayStation 2. It was developed in secrecy, with consistent updates over the last 15 years. The GUI is adapted from Open PS2 Loader Beta 1.2.0 1996, but at its core, it's an emulator. Running Xbox games on a PS2 might seem unthinkable, but here's how it's done.  

The emulator is entirely written in Assembler—around 120,000 lines—to ensure efficiency surpassing that of C implementations. However, it's important to note that it only operates on DECKARD models, thanks to their faster PPC (replacing the IOP) and a sufficiently large L-cache to handle the Xbox's additional RAM compared to the PS2's capabilities. Full-speed emulation is technically unfeasible, particularly for demanding games like Conker or Oddworld SW. Nevertheless, many games run well, including the first Halo, while some, such as GTA SA, only boot to a black screen.  

<strong>Note:</strong> Using the <code>8MB MemoryCard Patched</code> version sometimes breaks the Custom Dakota Speedway protocols which can result in some games not booting properly or crashing after a few minutes. If possible use the <code>Full Release</code> instead.

<strong>Release Mirror:</strong> <a href="https://github.com/koraxial/Xbox-2-PlayStation-Emulator-AlFa/releases/tag/SAS">X2P Releases page</a>
