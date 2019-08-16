---
layout: post
title: Boot from flash drive Mac OS Mojave
date: 2019-08-16
Author: Chang
categories: 

tags: [macOS Use]

comments: true

---



## Boot from flash drive macOS Mojave



1. Prepare a flash drive with 8GB+ volume (it will be erase)

2. Download macOS Mojave from App Store

3. Use Disk Utility to erase the flash drive

4. Open Terminal, run

   ~~~
   sudo /Applications/Install\ macOS\ Mojave.app/Contents/Resources/createinstallmedia --volume /Volumes/Mojave /Applications/Install\ macOS\ Mojave.app --nointeraction
   ~~~

5. Keep the flash drive insert, Restart Mac, press option till you can select boot

6. Select Mojave Installer, if you want to keep your files, go to install Mojave, or use disk utility to erase the Macintosh, and then go to install Mojave 

