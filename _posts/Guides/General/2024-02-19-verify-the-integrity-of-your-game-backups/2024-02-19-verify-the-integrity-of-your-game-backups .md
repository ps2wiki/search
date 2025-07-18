---
title: 🤔 Verifying the integrity of a game backup
categories:
  - PS2Wiki-item
tags:
  - PS2Wiki-item
---

<span class="visually-hidden"><meta http-equiv="refresh" content="0; url=https://ps2wiki.github.io/general/2024/02/19/verify-the-integrity-of-your-game-backups.html"></span>

<h3>Intro:</h3>
To verify the MD5 hash of your PS2 ISOs against the Redump database, you'll want to follow a series of straightforward steps. Redump is a project dedicated to preserving the integrity of disc-based media, and by checking your ISOs against their database, you can ensure your backups are accurate. Here's a simplified guide:

<h3>1. Obtain an MD5 Checksum Utility</h3>
* First, you need a tool to calculate the MD5 checksum of your ISO file. For Windows, an easy-to-use option is "WinMD5" or "MD5Summer". Mac users can use the built-in "Terminal" app, and Linux users can also use their terminal.

**For Windows:**
- Download and install WinMD5 or any other preferred MD5 checksum tool.
- 
**For Mac/Linux:**
- Use the terminal. No additional software is usually needed.

<h3>2. Calculate the MD5 Hash of Your PS2 ISO</h3>

**Windows:**
- Open WinMD5.
- Click on the 'Browse' button and select your PS2 ISO file.
- The program will automatically calculate the hash once the file is selected.

**Mac/Linux:**
- Open the Terminal.
- Use the `cd` command to navigate to the folder containing your ISO. For example, `cd Downloads` if your ISO is in the Downloads folder.
- Type `md5 [filename.iso]` for Mac or `md5sum [filename.iso]` for Linux and press Enter. Replace `[filename.iso]` with the name of your ISO file.

<h3>3. Compare Your MD5 Hash with Redump Database</h3>

- Visit the Redump website or any page that lists the MD5 hashes for PS2 games.
- Use the search function to find your game.
- Find the MD5 hash listed for your game on Redump and compare it with the hash you calculated.

<h4>How to Compare:</h4>
- The MD5 hash is a long string of numbers and letters. You need to ensure every character matches perfectly with the one provided by Redump for your specific game.

**If They Match:** If every character in your MD5 hash matches the one on Redump, your ISO is a perfect copy of the original disc.

**If They Do Not Match:** If there's any discrepancy, the ISO may not be an accurate copy. This could be due to data corruption, differences in the disc version, or modifications.

By following these steps, you'll be able to verify the integrity of your PS2 ISOs against the Redump database, ensuring they're accurate backups of the original media. This process is crucial for preservation purposes and for ensuring compatibility with emulators and homebrew software.
