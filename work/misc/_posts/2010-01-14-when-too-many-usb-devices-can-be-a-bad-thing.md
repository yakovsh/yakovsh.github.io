---
title: 'When Too Many USB Devices Can Be a Bad Thing'
date: '2010-01-14T09:00:24+00:00'
layout: post
---

Just a strange problem I ran into recently with a client. They were using a Windows XP computer with multiple USB devices. Somewhere after about 300 inserts and removes, Windows gave the following error message

> The system has reached the maxium size allowed for the system part of the registry. Additional storage requests will be ignored.

Once that happens, all kinds of weird behavior starts to occur beginning with the fact that USB devices no longer work. The cause of this is due to the fact that every time a USB device is inserted, it creates registry entries. Apparently, with storage devices like Flash drives it is even worth, since there may be multiple devices – one for the drive, one for the actual physical key, and possibly a bridge as well. While Windows XP is not supposed to have such limits, it does occur, especially on systems using the “3GB” switch for bootup.

The solution – [download the VxScrub utility from Veritas/Symantec](http://seer.entsupport.symantec.com/docs/277301.htm) which will clean out your registry from any old entries.