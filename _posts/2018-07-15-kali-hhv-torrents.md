---
layout: post
title: DEF CON 26 Kali HHV live CD torrents are live!
date: 2018-07-15 00:00:00 -0000
author: kbembedded
author_url: https://github.com/kbembedded
categories: announcement livecd DC26
---

With DEF CON 26 quickly approaching, we've locked in to place our official Kali HHV live CD images and have begun distribution via bittorrent. If you are unfamilar or unaware of this, we've forked Offensive Security's Kali Linux image builder. We used this opportunity to cram as much hardware hacking goodness that we could in to a CD and DVD sized image. This allows us to give out and use our own live CD that has nearly all of the hardware hacking tools one could need during DEF CON. And, since it's based on the existing Kali Linux framework, it has all of the features one would expect from a security focused live CD.

We will have a limited amount of discs to hand out during DEF CON. They are nothing special or limited edition, I only have so many blank CD-R and DVD-R discs on hand. Because of the limited amount, we wanted to get the ISOs out in to the world early for people to grab and set up on their own.

Interested in building your own, or want to learn more about this project? You can find the source repo [here](https://github.com/DCHHV/kali-live-build-config).

Note that we will keep seeding these torrents up until and through DEF CON. After August 12th, 2018 however, these may just disappear without warning.

* * *
## HHV
The HHV variant is the full distribution. It uses XFCE4 as the GUI. It includes all of the standard Kali boot features (memtest, install to disk, live, live forensic mode, USB persist, etc.), all of the WiFi device firmware that is in kali-rolling at time of build, and a whole lot of utilities for hardware and embedded device hacking. It weighs in at about 2.3 GB, so it fits nicely on a standard DVD or 4 GB USB flash drive with room to spare. We built both i386 and amd64 CPU variants and have made torrents of them available below.

* [HHV amd64 torrent magnet link](magnet:?xt=urn:btih:c10b843b0676041050a2d99a676b7549683644fb&dn=kali-linux-DC26-hhv-rolling-amd64.iso&tr=http%3a%2f%2f104.236.218.246%3a6969%2fannounce)

SHA256 (kali-linux-DC26-hhv-rolling-amd64.iso) = 90382d6e37d6b1e8ed0b13a97be9c19a93e7adaa92849208c65f48e50503ef93

* [HHV i386 torrent magnet link](magnet:?xt=urn:btih:1ce9dcc4b0f83299c5383329c37db5c9ef99e272&dn=kali-linux-DC26-hhv-rolling-i386.iso&tr=http%3a%2f%2f104.236.218.246%3a6969%2fannounce)

SHA256 (kali-linux-DC26-hhv-rolling-i386.iso) = f750cf59b4d0ca8d7e2a39fe3d9adad905664fcf89a805b7dcc7dd4d243a9283

* * *
## HHV-light
The HHV-light variant is a more stripped down version of the above ISO. It also uses XFCE4 as the GUI but we had to drop some of the Kali themes. It includes only some of the standard Kali boot features; we had to remove the ability to install to disk. However, everything else, including USB persist mode, work just fine. There is absolutely no support for WiFi devices that require firmware. All of those binary blobs add up in size quickly. Besides, you're at DEF CON, you probably shouldn't be on the WiFi anyway. There are far fewer utilities here, but we put in everything we thought would be bare bones necessary for some basic hacking and reverse engineering. The ISO just barely squeezes on a 700 MB CDR, only a few MB to spare. This does mean that it will fit comfortably on a 1 GB USB drive though. We build both i386 and amd64 CPU variants and have made torrents of these available below.

* [HHV-light amd64 torrent magnet link](magnet:?xt=urn:btih:9aa791946f9fe59c688f2579b895ceb5a6b9ef36&dn=kali-linux-DC26-hhv-light-rolling-amd64.iso&tr=http%3a%2f%2f104.236.218.246%3a6969%2fannounce)

SHA256 (kali-linux-DC26-hhv-light-rolling-amd64.iso) = 925d545125e57e9df9d44734256c536e85cd7277fb88df62a60638e75f529b54

* [HHV-light i386 torrent magnet link](magnet:?xt=urn:btih:c8fa0b3f3495989a900be24efefe31a0b8f43390&dn=kali-linux-DC26-hhv-light-rolling-i386.iso&tr=http%3a%2f%2f104.236.218.246%3a6969%2fannounce)

SHA256 (kali-linux-DC26-hhv-light-rolling-i386.iso) = 74ef30a69840eabede62b5cddaedcc9226a4bb3a46aaef0559a9f921afafae43
* * *
### Legal
KALI LINUX™ is a trademark of Offensive Security.

The KALI LINUX™ logo and name for this project are used with permission from Offensive Security and may not be re-used without written permission from Offensive Security.

Disc images created may not be produced or distributed commercially (whether or not it is for profit) without written permission of Offensive Security.

This project is not produced or sponsored by Offensive Security, it was created by DEF CON Hardware Hacking Village volunteers.
* * *
