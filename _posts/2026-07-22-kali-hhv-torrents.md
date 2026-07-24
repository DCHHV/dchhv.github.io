---
layout: post
title: DEF CON 34 Kali HHV live CD torrents are live!
date: 2026-07-22 00:00:00 -0000
author: kbembedded
author_url: https://github.com/kbembedded
image: assets/images/header.png
categories: announcement livecd DC34
---

With DEF CON 34 quickly approaching, we've locked in to place our official Kali HHV live images and have begun distribution via bittorrent. If you are unfamilar or unaware of this, we've forked Offensive Security's Kali Linux image builder. We used this opportunity to cram as much hardware hacking goodness that we could in to bootable live image. And, since it's based on the existing Kali Linux framework, it has all of the features one would expect from a security focused live CD.

Interested in building your own, suggest new packages, add more packages, or just want to learn more about this project? You can find the source repo [here](https://github.com/DCHHV/kali-live-build-config).

Note that we will keep seeding these torrents up until and through DEF CON. After closing ceremonies however, they can disappear any time.

* * *
## HHV
The HHV variant is a customized Kali variant created by us. It uses XFCE4 as the GUI. It includes all of the standard Kali boot features (memtest, live, live forensic modeu etc.), all of the WiFi device firmware that is in kali-rolling at time of build, and a whole lot of utilities for hardware and embedded device hacking. It weighs in at about 4.7 GB (the software bloat is real), so we recommend at least an 8 GB USB drive. We built this to target amd64 CPUs and have made torrents of them available below.

* [HHV amd64 torrent magnet link](magnet:?xt=urn:btih:9c7e271cdb91a712db73aec2107ff3a4e6e10b40&xt=urn:btmh:1220e6c56e16ebd7b6bc6680946c5a39e458b70b810a72fe7adf5b06ab9871f52496&dn=kali-linux-rolling-live-hhv-amd64.iso&xl=4807327744&tr=udp%3A%2F%2Ftracker.opentrackr.org%3A1337%2Fannounce)

SHA256 (kali-linux-rolling-live-hhv-amd64.iso) = 2fc9d64efd89f44bd56a6a235be93206819337bef222dc482a4ff3a85d7ad7ad

(Why no i386 variant this year? Kali Rolling is fairly volatile, and linux-686-pae was not buildable while trying to build this year's liveCD. Sorry!)

* * *
### Legal
KALI LINUX™ is a trademark of Offensive Security.

The KALI LINUX™ logo and name for this project are used with permission from Offensive Security and may not be re-used without written permission from Offensive Security.

Disc images created may not be produced or distributed commercially (whether or not it is for profit) without written permission of Offensive Security.

This project is not produced or sponsored by Offensive Security, it was created by DEF CON Hardware Hacking Village volunteers.
* * *
