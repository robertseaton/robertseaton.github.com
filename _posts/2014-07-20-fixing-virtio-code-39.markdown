---
title: Fixing VirtIO Code 39
layout: post
---

I'm recording this here in case anyone else is unfortunate enough to encounter this Code 39 message, and so that she can avoid wasting several hours of her life attempting to fix it, by instead Googling it and reading this.

Alas, it's too late for me.

If you're attempting to install [Red Hat's VirtIO drivers](http://www.linux-kvm.org/page/WindowsGuestDrivers/Download_Drivers) onto a virtualized Windows box, and the whole thing seems to go okay, but then you receive the message "Windows cannot load the device driver for this hardware. The driver may be corrupted or missing (Code 39)," at which point, the device doesn't work, and you have to remove the driver and do the entire thing over again...

Well, it's because you're installing the wrong VirtIO version. If you're on a Windows Server 2008 R2 box like me, and you're thinking "Oh, I'll use the drivers in the Win8 folder, because their aren't any drivers explicitly for 2008 server," *you have gone astray.* Windows Server 2008 R2 uses the Windows 7 drivers, not 8.

It would be nice if, you know, Windows would tell you this, instead of giving you this less-than-helpful-to-put-it-politely message, but it's not like people pay them for this software or anything, so what do you really expect? Or, uh, wait.
