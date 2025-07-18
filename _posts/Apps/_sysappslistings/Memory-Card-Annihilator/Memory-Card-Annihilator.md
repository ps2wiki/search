---
title: ⬇️ Memory Card Annihilator
categories:
  - SAS-AA-item
tags:
  - SAS-AA-item
---

<span class="visually-hidden"><meta http-equiv="refresh" content="0; url=https://ps2wiki.github.io/sas-apps-archive/sysappslistings/Memory-Card-Annihilator/Memory-Card-Annihilator.html"></span>

Memory Card Annihilator is a tool created back in 2007.  
Its main purpose is formatting/unformatting memory cards (both PS2 and PSX)
as well as managing memory card images (creating images of physical
cards and writing images onto physical cards). <br><br>
It can be used to restore cards broken by other formatters back to normal
(eg. when 64MB card has been formatted to 8MB by MCKiller and similar tools). <br><br>
It has quite nice bad block handling, so even worn cards should
work fine after formatting (unless it's the very first block that
got screwed - because of the way mcman handles the cards when
recognizing the file system, it might not be possible to solve this kind of error
in a different way than hardware block remapping). <br><br><br>

The previous version, although worked really nice (got quite
a lot of success stories), had two big drawbacks:  
- was all in Polish language  
- display mode was fixed to PAL  
<br><br>

Basic usage:  
The video mode needed should be detected automatically
(for PAL/NTSC - depending on console).  
If it fails for some reason, you can always force particular mode
by keeping a button pressed during application startup. <br><br>
The options are as follows:
- PAL - press dpad RIGHT
- NTSC - press dpad LEFT
- VGA (640x480) - press dpad UP
