---
title: Running homebrew on your Wii U
date: 2025-02-07 HH:MM:SS +/-TTTT
categories: [Homebrew, Wii U]
tags: [wiiu, homebrew, nintendo] 
---
The Wii U is a video game console released in 2012 by Nintendo, to fix some quirks of the Wii. It unfortunately failed to sell since it **confused people**:
Most people took the Wii U as an accessory for the Wii. Also, the Wii U game library is tiny, like **really** tiny: 791 games were released for Wii U, compared to
4915 on the Nintendo Switch. A pretty huge differency, right?

Unfortunately, all the Wii U services are now down (Miiverse, YouTube for Wii U, Online...).

Just like the Wii, the Wii U can be hacked with some tools in order to load a payload at startup to start a custom firmware, and i'll tell you how you can hack your
Wii U to do whatever you want on it.

## Prerequisites
* Have a Wii U on the latest firmware version. (how did you guess it?)
* Have an SD card (i'd recommend 4 gb if you have only homebrew, or 32gb if you plan to install/dump games on your console)
* Have a computer (Most desktop OSes can be used)

## Step 1: Choosing an homebrew environment
### Aroma
Aroma is today's homebrew, allowing you to add your own apps on the Wii U Menu, running plugins in the background, and
much more... It allows good integration of the homebrew apps to the Wii U's OS (Opening the HOME menu on HOME press, ...)
It may not support all homebrew apps.

### Tiramisu
Tiramisu is an older homebrew environment that replaces the Mii editor with a custom app. (mainly Dimok's Homebrew Launcher)
I don't recommend using this, unless you need some legacy homebrew that doesn't works with Aroma.

Of course there are [more choices](https://wiiubrew.org/wiki/Category:Homebrew_voiding_your_warranty), but these 2 ones are the most used today.
For this blog post, i'll go with Aroma, as i use it on my Wii U, but you can do it for other homebrew environment by going on [Wii U Hacks Guide](https://wiiu.hacks.guide/).

## Step 2: Downloading Aroma for your café
Firstly, insert the SD card on your PC, and format it as FAT32, then go on https://aroma.foryour.cafe, and check the 4 cases.
A downloader will appear, allowing you to choose what you want.
Then, when you choosed everything, click on "Download Payloads", "Download Base Aroma", and optionally on "Download Additional Plugins & Modules".
It will download 2 or 3 zips, all containing a "wiiu" folder that you should extract on the FAT32-formatted SD.

## Step 3: Run the exploit
When you finished extracting the zips to your SD card, you can eject it, and put it on your Wii U.
Then, start the Wii U, open the Internet Browser, go to https://wiiuexploit.xyz and press "Run Exploit!".
Immediately after you pressed the Run Exploit! button, hold B.
If you see a black screen with some text on it, you succeded, but if it's locked up, or
you see the Environment Loader, then restart by force the console and retry.

## Step 4: Backup your NAND
In case of a wrong operation bricking your console, you can restore the NAND if you backed it up.
I'll let you read the Wii U Hacks Guide's article, since they explain better than me: https://wiiu.hacks.guide/aroma/nand-backup.html.

(TODO: finish article)
