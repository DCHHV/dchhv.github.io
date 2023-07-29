---
title: DC30 Schedule
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
| Thursday Aug 11 | Setup (Closed to Public) |
| Friday Aug 12 | 10:00 - 18:00 |
| Saturday Aug 13 | 10:00 - 18:00 |
| Sunday Aug 14 | 10:00 - 13:00 |

The village will be in the lower floors of the Flamingo Conference space - [venue map here](https://defcon.org/html/defcon-30/dc-30-venue.html)

<br/>
<br/>

## Events Schedule

| Event | Times |
| --- | ------|
| RoboSumo | Saturday Aug 13, 13:00 |
| Prizes for all events announced | Saturday Aug 13, 16:00  |

[RoboSumo](/events/robosumo.html) will be available to play and test code during all open hours. Competition will be Saturday at 13:00 for as long as it takes to run a bracket.

[HHV Rube Goldberg Machine](/events/hhv_rgb.html) will be running during all open hours. Come by and bring some text to print! Modules will be allowed to be added and removed all open hours as well. Those that want to be involved in the judging will need to have had their module inline before Saturday at 16:00 when prizes will be announced.

[Make Your 0wn Use Contest](/events/makeyourownuse.html) will be running during all open hours. We have space for display, if you are comfortable leaving it out for people to look at. Judging will conclude on Saturday at 16:00 when prizes will be announced.

[Bring The Other Half](/events/bringtheotherhalf.html) will be running during all open hours. Get the full firmware and bring your device by the HHV booth. Judging will conclude on Saturday at 16:00 when prizes will be announced.

[HHV Capture The Flag (CTF)](/challenges/dc30.html) is back in person and will be running during all open hours. We have been working on developing a new SOC, the HHVDC30, to drive our new "Badge" prototype and enforce our new SAO DRM protocol. This new chip design and DRM implementation should be perfect, but the higher-ups still want us to test it out at DEF CON. Good luck finding any flaws!

<br/>
<br/>

## Talk/Workshop Schedule

| Friday | Talk/Workshop |
| ------- | ----- |
| 1000 | [Uwb Security Primer: Rise Of A Dusty Protocol](#uwb-security-primer-rise-of-a-dusty-protocol) |
| 1100 | [From Zero To Sao ... Or, How Far Does This Rabbit Hole Go?](#from-zero-to-sao--or-how-far-does-this-rabbit-hole-go) |
| 1300 | [Reversing An M32C Firmware -- Lesson Learned From Playing With An Uncommon Architecture](#reversing-an-m32c-firmware----lesson-learned-from-playing-with-an-uncommon-architecture) |
| 1400 | [Movie-Style Hardware Hacking](#movie-style-hardware-hacking) |
| 1500 | [Injectyll-Hide: Build-Your-Own Hardware Implants](#injectyll-hide-build-your-own-hardware-implants) |

## Talk/Workshop Details
* * *
### Uwb Security Primer: Rise Of A Dusty Protocol
Göktay Kaykusuz k4r4koyun
#### Abstract
UWB has been available for nearly 20 years now but never took off the way it was meant to. Every use-case designed or considered for UWB had been taken over by other protocols such as Bluetooth, and like the VR tech, UWB did not become a widespread way of communication for a long time.

During this talk, we will look at the standards, current applications, and possible attack vectors alongside the available hardware that we can utilize to discover these vectors. This session will be a primer for anyone interested in the current UWB landscape and will try to provide the basis for security research.

REFERENCES
- Singh, Mridula, et al. "Security analysis of IEEE 802.15. 4z/HRP UWB time-of-flight distance measurement." Proceedings of the 14th ACM Conference on Security and Privacy in Wireless and Mobile Networks. 2021.
- Compagno, Alberto, et al. "Modeling enlargement attacks against UWB distance bounding protocols." IEEE Transactions on Information Forensics and Security 11.7 (2016): 1565-1577.
- Leu, Patrick, et al. "Ghost Peak: Practical Distance Reduction Attacks Against HRP UWB Ranging." arXiv preprint arXiv:2111.05313 (2021).
#### Bio
Göktay Kaykusuz has more than five years of experience in various cyber security fields and is currently a Security Engineer at eyeo GmbH. Previously he worked as a Security Engineer at Jotform Inc. and did freelance/consultancy work before that. Göktay also has Bachelor’s Degree in Computer Engineering, a Master’s Degree in Information Security, and OSCP/OSCE certifications. He also designed a custom badge to wear, just for DEFCON 30.

Göktay also likes riding cruisers/choppers, smoking churchwardens, and robotics in general. He also dislikes nature to a degree (especially bugs/spiders) and would welcome the warm embrace of Cult Mechanicus if given the opportunity.
* * *
### From Zero To Sao ... Or, How Far Does This Rabbit Hole Go?
Bradán Lane
#### Abstract
If you have a ounce of desire and a sprinkle of creativity then you can make fun electronic tchotchkes!

You will take a journey through the software and hardware tools often used to make small electronic gadgets like DEFCON SAOs, electronic pins, and annoying blinky-beepy gifts for parties and holidays. The skills covered will also serve as the stepping off point for your own badgelife creation ... should you dare.

You will see how to take your personal strengths - be it art, maths, engineering, or fabrication - and build out to other skills.

You won't learn everything there is to know about completing your dream project but you will have learned the steps involved and where to get help along the way!
#### Bio
Bradán Lane is a UX Design and User Researcher who had his own "Alice’s Adventures in Wonderland" experience when he discovered badge making. While he has made a number of fun blinky beepy ornaments and badges, he found his passion with the eChallengeCoin - an interactive and text story challenge puzzle in the shape of a coin. He releases a new eChallengeCoin each year. Bradán also designs hardware for the CircuitPython echo system so users "have a low barrier to productivity and creativity". 
* * *
### Reversing An M32C Firmware -- Lesson Learned From Playing With An Uncommon Architecture
Philippe Laulheret
#### Abstract
While busy hacking the planet, have you ever encountered an unfamiliar architecture and simply had no idea where to start? You pried the firmware from a reluctant (and almost not smoldering) flash chip, loaded the thing in IDA, but what's next? 
We got into this pickle while working on reversing the firmware of a medical device. The mystery architecture turned out to be M32C, and thankfully, IDA Pro added support for it a few months prior.

This talk is not exactly about reversing yet another embedded device. Instead, this is more about the journey and lessons learned so that it could be abstracted away for the next project. Rather than focusing on the specifics of the firmware itself, we will see how it interacts with the micro-controller and the steps taken to approach an unfamiliar embedded architecture. 
 
During this presentation, you can expect digging into low-level micro-controller notions such as interrupt handlers, special purpose registers, how to find flash handling code, and way too much M32C assembly. 
If you've ever dabbled in hardware hacking and want to have a look at something that is not Linux-based, this talk will give you some pointers in how to get the ball* rolling. 
(*not talking about the ones we dropped at the reballing station)
#### Bio
Philippe Laulheret is a Senior Security Researcher on the Trellix vulnerability research team. With a focus on Reverse Engineering and Vulnerability Research, Philippe uses his background in Embedded Security and Software Engineering to poke at complex systems and get them behave in interesting ways. In his spare time, Philippe enjoys playing CTFs, immersing himself in the beauty of the Pacific Northwest, and exploring the realm of Creative Coding.

Philippe holds a MSc in Computer Science from Georgia Tech and a MSc in Electrical and Computer Engineering from Supélec (France).
* * *
### Movie-Style Hardware Hacking
Bryan C. Geraghty
#### Abstract
We all have hardware devices sitting around: In server rooms or your IoT devices at home. What are these things actually doing? It would be really handy to have root access on them to aid us in future adventures.

Or maybe you want to perma-root the device and re-sell it to some unsuspecting victim. Or maybe you want to know if you're the unsuspecting victim. Who am I to judge?

What does it take to cause these devices to fail? Can we get them to fail open?

I'm going to tell a story about circuit-shorting attacks, how to build a hardware circuit to perform this attack with a computer, and give you the instructions and code to build one yourself... with a device you may already have :)

#### Bio
Bryan leads and executes highly technical software and hardware assessments. He specializes in cryptography, reverse engineering, and analyzing complex threat models.

* * *
### Injectyll-Hide: Build-Your-Own Hardware Implants
Jonathan Fischer Jeremy Miller
#### Abstract
Hardware implants are not a new topic; however, their evolution seems to have stagnated outside of closed source, for-profit solutions. The disadvantage to these is that they lack the customization to adapt to large targeted deployments. Open-source projects exist but focus more on individual workstations (dumb keyboards/terminals), relying on corporate networks for remote control. This leaves a gap that we decided to address with our research. 
Our solution is an open source, hardware implant which adopts IoT technologies, using non-standard channels to create a remotely managed mesh network of hardware implants. Attendees will learn how we created a new breed of open-source hardware implant, along with lessons that we learned throughout the project. Topics covered in this talk include a detailed dive into the hardware that we used, the evolution of the project from start to finish, the complete design of our project, and our lessons learned along the way. Attendees will also be able to interact with a live version of the project.
#### Bio
Jonathan Fischer is a hardware, RF, and IoT security enthusiast that started off designing, programming, and implementing electronic controls for industrial control systems and off-highway machinery. After a decade in that industry, Jonathan obtained his BS in Computer Science and transitioned over to the cyber security industry where he has been working as a Red Team consultant and researcher for more than five years at a Fortune 500. Since joining the cyber security industry, Jonathan has since earned various industry certifications (OSCP, GPEN, etc.) and continues to leverage his unique experience in his research into hardware hacking.

Jeremy Miller is a 12+ year security professional that has worked in various industries including life-sciences, finance, and retail. Jeremy has worked both sides of the security spectrum ranging from Security Research, Red Teaming and Penetration Testing to Threat Intelligence and SOC Analyst. Jeremy currently works as a Security Technical Lead for an emerging R&D Life Science Platform where he works on product and infrastructure security.
* * *
