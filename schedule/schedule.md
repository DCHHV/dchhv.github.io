---
title: DC33 Schedule
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
| Thursday, Aug 7 | Setup (Closed to Public) |
| Friday, Aug 8 | 10:00 - 18:00 |
| Saturday, Aug 9 | 10:00 - 18:00 |
| Sunday, Aug 10 | 10:00 - 13:00 |

The village will be located in the Las Vegas Convention Center

<br/>
<br/>

## Events Schedule

| Event | Times |
| --- | ------|
| Prizes for all events announced | Saturday Aug 9, 16:00  |

[RoboSumo](/events/robosumo.html) will be available to play and test code during all open hours. Competition will be Saturday at 13:00 for as long as it takes to run a bracket.

[HHV Capture The Flag (CTF)](https://dchhv.org/announcement/ctf/dc32/2024/08/01/dc32-hhv-challenges.html) is back in person and will be running during all open hours. More details to follow!

<br/>
<br/>

## Talk/Workshop Schedule

| Time | Location | Talk/Workshop | 
|------|----------|---------------|
| TBA  | | Talk - [All Your Keyboards Are Belong To Us!](#all-your-keyboards-are-belong-to-us!) |
| TBA  | | Talk - [The Missing Link: Draytekâ€™S New Rces Complete The Chain](#the-missing-link:-draytekâ€™s-new-rces-complete-the-chain) |
| TBA  | | Talk - [The Power(Point) Glove](#the-power(point)-glove) |
| TBA  | | Meetup - [Hack My Bot](#hack-my-bot) |


## Talk/Workshop Details
* * *
### All Your Keyboards Are Belong To Us!
Federico Lucifredi F2
#### Abstract
This is a live tutorial of hacking against keyboards of all forms. Attacking the keyboard is the ultimate strategy to hijack a session before it is encrypted, capturing plaintext at the source and (often) in much simpler ways than those required to attack network protocols.

In this session we explore available attack vectors against traditional keyboards, starting with plain old keyloggers. We then advance to "Van Eck Phreaking" style attacks against individual keystroke emanations as well as RF wireless connections, and we finally graduate to the new hotness: acoustic attacks by eavesdropping on the sound of you typing!

Use your newfound knowledge for good, with great power comes great responsibility!

A subset of signal leak attacks focusing on keyboards. This talk is compiled with open sources, no classified material will be discussed.
#### Bio
Federico Lucifredi is the Product Management Director for Ceph Storage at IBM and Red Hat and a co-author of O'Reilly's "Peccary Book" on AWS System Administration. Previously, he was the Ubuntu Server product manager at Canonical, where he oversaw a broad portfolio and the rise of Ubuntu Server to the rank of most popular OS on Amazon AWS. A software engineer-turned-manager at the Novell corporation, he was part of the SUSE Linux team, overseeing the update lifecycle and delivery stack of a $150 million maintenance business. A CIO and a network software architect at advanced technology and embedded Linux startups, Federico was also a lecturer for over 200 students in Boston University's graduate and undergraduate programs, and simultaneously a consultant for MIT implementing fluid-dynamics simulations in Java.
* * *
### The Missing Link: Draytekâ€™S New Rces Complete The Chain
Octavio Gianatiempo Gaston Aznarez
#### Abstract
Draytek routers are widely deployed edge devices trusted by thousands of organizations, and therefore remain a high-value target for attackers. Building on our prior DEFCON32 HHV presentation (https://www.youtube.com/watch?v=BiBMsw0N_mQ) on backdooring these devices, where we also exposed six vulnerabilities and released Draytek Arsenal (https://github.com/infobyte/draytek-arsenal), a toolkit to analyze Draytek firmware. We return with two new unauthenticated RCEs: CVE-2024-51138, a buffer overflow in STUN CGI handling, and CVE-2024-51139, an integer overflow in CGI parsing. When chained with our prior persistence techniques, these bugs enable a full device takeover and backdoor from the internet.

This talk provides an in-depth analysis of the new vulnerabilities and their exploitation strategies with demos and the full end-to-end exploitation chain. Weâ€™ll also explore their potential link to the mass Draytek reboot incidents of March 2025, suggesting that real-world exploitation of some of these vulnerabilities may already be underway. Attendees will gain insight into edge device exploitation, persistent compromise, and the importance of transparency and tooling in embedded security research.
#### Bio
Octavio Gianatiempo is a Security Researcher at Faraday and a Computer Science student at the University of Buenos Aires. He's also a biologist with research experience in molecular biology and neuroscience. The necessity of analyzing complex biological data was his point of entry into programming. However, he wanted to gain a deeper understanding of how computers work, so he enrolled in Computer Science. As a Security Researcher at Faraday, he focuses on vulnerability research on IoT and embedded devices and fuzzing open and closed-source software to find new vulnerabilities and exploit them. He has presented his findings at various conferences, including DEFCON, Ekoparty, 8.8, and Nerdearla.

Gaston Aznarez is a computer enthusiast deeply passionate about computers and security. He has a Computer science degree and is a Security Researcher at Faraday, focused on vulnerability research on IoT and embedded devices.
* * *
### The Power(Point) Glove
Parsia Hakimian N/A
#### Abstract
Inspired by the cult following of the Nintendo Power Glove, this talk explores an unconventional use as a presentation remote. Using a generic ESP32 dev board and basic C code, it becomes a Bluetooth keyboard controlling presentations with ease. In fact, I will deliver this talk using the same Power Glove.

In this beginner-friendly talk, I'll share my experience "hacking" the Nintendo Entertainment System (NES) accessory. I'll cover:

- Choosing the right dev board: Arduino vs ESP32
- NES controller protocol crash course
- Translating button presses to PowerPoint shortcuts with ESP32

Attendees will learn how to replicate this project and add pizzazz to their presentations. I'll release the code, so you can spice up your own talks. Maybe you'll even use the Power Glove to pop a shell on a remote machine in your next Proof of Concept.

Note: This is a personal project developed independently and is not affiliated with or endorsed by Microsoft, Nintendo, or any other employer.
#### Bio
Parsia Hakimian is an offensive security "engineer" at Microsoft. He is a noob with hardware and spends most of his time reading code, but wishing he was gaming. Previously, he's experimented with videogame security.

Parsia has presented at DEF CON's main venue and the AppSec Village. When not breaking (or fixing) things, he plays videogames, D&D, spends time with family outside - and, as his wife jokes, "subjects himself to the tax and immigration systems of US and Canada."
* * *
### Hack My Bot
l3xic0n lexicon121
#### Abstract
DEFCON Hack the Bots is a live-action hardware hacking competition where four teams face off using robotic platforms like the Tengu Marauder. The Tengu Marauder is an open source hacking bot platform that has presented at DEFCON32 and Blackhat USA. Each bot is operated by a two-person crew: one pilot to drive and engage in kinetic tactics, and one hacker to launch wireless, IoT, or hardware-based exploits. The mission? Reach the "King of the Hill" zone, capture the flag, and hold it against other attackers. Teams must bypass IoT-controlled barriers, dodge spinning and piston-powered obstacles, and survive attacks from rival robots. This session blends robotics, wireless warfare, and hands-on hacking in a physical capture-the-flag arena. No prior robotics experience is required, but a basic understanding of wireless or hardware attacks will give teams an edge. Bring your skills. Break their bots. Win the hill.
#### Bio
Lexicon121 is a cybersecurity engineer, robotics hacker, and founder of Ex Machina Parlor; Philadelphiaâ€™s first hackerspace focused on offensive and defensive robotics. With over a decade of experience in red teaming, wireless exploitation, and autonomous system security including military cyber operations. Lexicon121 is known for building high-impact training environments that merge hardware, software, and adversarial tactics. They developed the Tengu Marauder, a modular robot designed to simulate real-world exploitation scenarios, from deauth attacks to sensor spoofing. At DEFCON 33, Lexicon121 brings a live-action robotics CTF to the Hardware Hacking Village, challenging participants to outmaneuver, out-hack, and outlast rival bots in a chaotic, capture-the-flag arena. Their mission: make hardware hacking as hands-on and accessible as lockpicking.
* * *
