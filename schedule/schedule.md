---
title: DC32 Schedule
layout: page
---

**Note** All listed times are Las Vegas local time, PDT/UTC-7

<br/>
<br/>

[Village Hours](#village-hours)

[Events Schedule](#events-schedule)

[Talk/Workshop Schedule](#talkworkshop-schedule)

<br/>
<br/>

## Village Hours

| Day | Times |
| --- | ------|
| Thursday, Aug 8 | Setup (Closed to Public) |
| Friday, Aug 9 | 10:00 - 18:00 |
| Saturday, Aug 10 | 10:00 - 18:00 |
| Sunday, Aug 11 | 10:00 - 13:00 |

The village will be located in the Las Vegas Convention Center - [venue map here](https://defcon.org/images/defcon-32/dc-32-map-public.pdf)

<br/>
<br/>

## Events Schedule

| Event | Times |
| --- | ------|
| Prizes for all events announced | Saturday Aug 10, 16:00  |

[RoboSumo](/events/robosumo.html) will be available to play and test code during all open hours. Competition will be Saturday at 13:00 for as long as it takes to run a bracket.

[HHV Rube Goldberg Machine](/events/hhv_rgb.html) will be running during all open hours. Come by and bring some text to print! Modules will be allowed to be added and removed all open hours as well. Those that want to be involved in the judging will need to have had their module inline before Saturday at 16:00 when prizes will be announced.

[HHV Capture The Flag (CTF)](https://dchhv.org/announcement/ctf/dc32/2024/08/01/dc32-hhv-challenges.html) is back in person and will be running during all open hours. More details to follow!

<br/>
<br/>

## Talk/Workshop Schedule

| Time | Talk/Workshop |
| ---- | ------------- |
| | Talk - [All Your Keyboards Are Belong to US!](#the-creation-of-the-out-of-band-anti-virus-dock-oobavd) |
| | Talk - [Taking off the blindfold: Detecting persistent threats on Draytek edge devices](#taking-off-the-blindfold-detecting-persistent-threats-on-draytek-edge-devices) |
| | Talk - [Custom cheap, easy and safe badges - without starting from scratch](#custom-cheap-easy-and-safe-badges-without-starting-from-scratch) |

## Talk/Workshop Details
* * *
### All Your Keyboards Are Belong to US!
Federico Lucifredi
#### Abstract
This is a live tutorial of hacking against keyboards of all forms. Attacking the keyboard is the ultimate strategy to hijack a session before it is encrypted, capturing plaintext at the source and (often) in much simpler ways than those required to attack network protocols. 

In this session we explore available attack vectors against traditional keyboards, starting with plain old keyloggers. We then advance to "Van Eck Phreaking" style attacks against individual keystroke emanations as well as RF wireless connections, and we finally graduate to the new hotness: acoustic attacks by eavesdropping on the sound of you typing! 

Use your newfound knowledge for good, with great power comes great responsibility!

A subset of signal leak attacks focusing on keyboards. This talk is compiled with open sources, no classified material will be discussed.
#### Bio
Federico Lucifredi is the Product Management Director for Ceph Storage at IBM and Red Hat and a co-author of O'Reilly's "Peccary Book" on AWS System Administration. Previously, he was the Ubuntu Server product manager at Canonical, where he oversaw a broad portfolio and the rise of Ubuntu Server to the rank of most popular OS on Amazon AWS. A software engineer-turned-manager at the Novell corporation, he was part of the SUSE Linux team, overseeing the update lifecycle and delivery stack of a $150 million maintenance business. A CIO and a network software architect at advanced technology and embedded Linux startups, Federico was also a lecturer for over 200 students in Boston University's graduate and undergraduate programs, and simultaneously a consultant for MIT implementing fluid-dynamics simulations in Java.

* * *
### Taking off the blindfold: Detecting persistent threats on Draytek edge devices
Octavio Gianatiempo, Gastón Aznarez
#### Abstract
Advanced attackers are increasingly choosing edge devices as targets, many of which are security appliances such as VPNs and Firewalls. They run closed-source firmware, and defenders and researchers must understand it to assess its security and integrity. We faced this firsthand when a client that used Draytek equipment was compromised. With at least 500k Draytek routers exposed to the Internet globally, no working tools exist to extract their firmware and assist researchers and defenders working with them.
We reverse-engineered Draytek's firmware format, developed tools to extract it, and discovered that its RTOS kernel can load code modules dynamically. These stored modules remain active even after firmware upgrades, inadvertently facilitating persistent threats. We crafted and uploaded malicious modules using our tools and newly found vulnerabilities to achieve persistence.
End-users lack straightforward means to detect such compromises. In response to this threat, we developed our own module to assess the integrity of other modules loaded in memory, mitigating its impact. In our pursuit of a more secure internet, we are sharing our knowledge and opening our tools to the community, enabling observability, hardening, transparency, and vulnerability research on Draytek edge devices.
#### Bio
Octavio Gianatiempo is a Security Researcher at Faraday and a Computer Science student at the University of Buenos Aires. He's also a biologist with research experience in molecular biology and neuroscience. The necessity of analyzing complex biological data was his point of entry into programming. However, he wanted to gain a deeper understanding of how computers work, so he enrolled in Computer Science. As a Security Researcher at Faraday, he focuses on vulnerability research on IoT and embedded devices and fuzzing open and closed-source software to find new vulnerabilities and exploit them. He has presented his findings at various conferences, including DEFCON, Ekoparty, 8.8, and Nerdearla.

Gastón Aznarez is a computer enthusiast who is passionate about cybersecurity. He earned a degree in Computer Science and began working in malware detection in firmware. He currently works as a Security Researcher at Faraday, specializing in discovering and exploiting vulnerabilities in IoT and embedded devices. Gastón also participates in CTF competitions and has shared his expertise as a speaker at different conferences.

* * *
## Custom cheap, easy and safe badges - without starting from scratch
securelyfitz
### Abstract
Electronic conference badges are cool and everything, but they're A LOT of time, money, and effort including but not limited to hardware, software and art design, testing, manufacturing, testing, provisioning, and repairing.

I've got a relatively simple, cheap, mass-producible badge design. We'll start out by looking at and understanding the design and implementation, highlighting the areas worth customizing (and which to leave as-s). Then we'll spend the majority of our time working in KiCAD to customize the hardware, CircuitPython to customize the software, or both if you have time.

We'll wrap up with some discussion of how to handle badge logistics for events of different sizes, and warn about some of the many pitfalls that electronic badges suffer. You should walk away with the design for your own customized badge design plus everything you need to have it mass produced.

Everyone should bring a laptop and install [KiCad](https://www.kicad.org/download/) and/or a good text editor for python code ([Mu](https://codewith.mu/), [VSCode](https://code.visualstudio.com/download), etc)
#### Bio
Joe FitzPatrick (@securelyfitz) is an Instructor and Researcher at SecuringHardware.com. Joe started his career working on low-level silicon debug, security validation, and penetration testing of CPUS, SOCs, and microcontrollers. He founded SecuringHardware.com and has spent decades developing and leading hardware security-related training, instructing hundreds of security researchers, pen-testers, hardware validators worldwide. When not teaching classes on applied physical attacks, Joe is busy developing new course content or working on contributions to the NSA Playset and other misdirected hardware projects, which he regularly presents at all sorts of fun conferences.


