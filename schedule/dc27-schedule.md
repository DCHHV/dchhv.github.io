---
title: DC27 Schedule
layout: page
---

[Event Schedule](#event-schedule)

[Talk/Workshop schedule](#talkworkshop-schedule)

[Talk/Workshop Details](#talkworkshop-details)

[Videos Played in Village](#video-list)

<br/>
<br/>
## Event Schedule
### Friday

| Time | Events |
|------|--------|
| 1000 | HHV/SSV Startup |
| 1400 | [RoboSumo](/events/robosumo.html) |
| 1800 | HHV/SSV Shutdown |

### Saturday

| Time | Events |
|------|--------|
| 1000 | HHV/SSV Startup |
| 1800 | HHV/SSV Shutdown |

### Sunday

| Time | Events |
|------|--------|
| 1000 | HHV/SSV Startup |
| 1300 | HHV/SSV Shutdown |

<br/>
<br/>
## Talk/Workshop Schedule
### Friday

| Time      | Events | Location |
|-----------|--------|----------|
| 1000~1050 | Talk - [Reversing Corruption In Seagate Hdd Translators, The Naked Trill Data Recovery Project](#reversing-corruption-in-seagate-hdd-translators-the-naked-trill-data-recovery-project) | Bally's Event Villages Track 1 (Just outside the HHV)|
|           | Allison Marie Naaktgeboren, MrDe4d | |
| 1100~1150 | Talk - [Another Car Hacking Approach](#another-car-hacking-approach) | Bally's Event Villages Track 1 (Just outside the HHV) |
|           | Benjamin Lafois, Vladan Nikolic | |
| 1100~1250 | Workshop - [Rapid Prototyping For Badges](#rapid-prototyping-for-badges) | Inside HHV, Workshop Area |
|           | Securelyfitz and friends | |
| 1200~1230 | Talk - [Infrared: New Threats Meet Old Devices](#infrared-new-threats-meet-old-devices) | Bally's Event Villages Track 1 (Just outside the HHV) |
|           | Wang Kang | |
| 1400~1450 | Talk - [Making A Less Shitty Sao: How To Use Kicad To Build Your First Pretty Pcb](#making-a-less-shitty-sao-how-to-use-kicad-to-build-your-first-pretty-pcb) | Inside HHV, Workshop Area |
|           | Steve Ball (hamster) | |
| 1500~1550 | Talk - [Ebolaphone Or Bust](#ebolaphone-or-bust) | Inside HHV, Workshop Area |
|           | SciaticNerd | |

### Saturday

| Time      | Events | Location |
|-----------|--------|----------|
| 1100~1150 | Talk - [Understanding & Making Pcb Art](#understanding--making-pcb-art) | Inside HHV, Workshop Area |
|           | TwinkleTwinkie | |
| 1200~1250 | Talk - [What You Print Is Not What You Get Anymore: Mitm Attack On 3D Printers Network Communications](#what-you-print-is-not-what-you-get-anymore-mitm-attack-on-3d-printers-network-communications) | Inside HHV, Workshop Area |
|           | Hamza Alkofahi | |
| 1400~1450 | Talk - [Hacking Con Badges for Fun and Profit](#hacking-con-badges-for-fun-and-profit) | Inside HHV, Workshop Area |
|           | Rob Rehr | |
| 1700~1750 | Followup - [Fireside Chat Style Followup To Main Track Talk: Tag-side attacks against NFC](https://defcon.org/html/defcon-27/dc-27-speakers.html#Wade) Bring your questions, get some answers. | Inside HHV, Workshop Area |
|           | Christopher Wade | |

## Talk/Workshop Details
* * *
### Reversing Corruption In Seagate Hdd Translators, The Naked Trill Data Recovery Project
Allison Marie Naaktgeboren MrDe4d

#### Abstract
Translation tables are a dynamic component of HDD firmware that translate logical addresses to physical locations on the disk. Corrupted translators can be the cause of drive failures in drives that appear undamaged and are without physical trauma. That failure can be reversed in many cases. We will present ways to identify if a drive’s translator has been corrupted for the Moose & Pharaoh drive families specifically, how to force a translator rebuild, and open source tool(s) to help you repair the translator.

Data recovery is a notoriously secretive field. Very little information about firmware and its internal data structures is public. Knowledge should be open source. By sharing what we’ve learned we hope to open this field up to more people, encourage repair, encourage re-use rather than disposal of hard drives, and encourage further publicly shared research.  After the talk, attendees should be able to fix this type of error themselves in HDDs of the appropriate families using a TTL converter and the supplied code. Familiarity with the basic components of hard drive firmware is helpful, but not required.

#### Bio
MrDe4d is the lead Data Recovery Engineer and founder of Revenant Data Recovery. She is also a hobbyist embedded systems security researcher. She leads local workshops in Binary and Assembly CTF challenges. She has presented at conferences such as HushCon and Teardown, as well as at other hackerspaces around the USA.  In 2017 she co-founded PASCAL Hackerspace and in 2019 co-founded the QultoftheQuantumQapybaras CTF team. She is passionate about learning, freedom of information, promoting self-advocacy, and hacking the planet!

Allison Marie Naaktgeboren is a Software Engineer with security roots at Signal Sciences. She has written and regretted code at Mozilla, Amazon, Cisco, FactSet Research Systems, and the Biorobotics Laboratory of the Robotics Institute.  She holds a Bachelor’s Degree in Computer Science from Carnegie Mellon University. Allison leads classes on computer science fundamentals, cofounded & captains the QultoftheQuantumQapybaras CTF team, and mentors disadvantaged high school students in robotics, software, and hardware hacking.
* * *
### Another Car Hacking Approach
Benjamin Lafois Vladan Nikolic

#### Abstract
Cars now have infotainment systems for several years. Those systems accomplish basic tasks such as radio, music, navigation and Bluetooth handsfree, but can also embed sophisticated features, using wireless connectivity (with cloud backends) and vehicle bus connectivity. Previous talks have presented some vulnerabilities in the past. This talk will introduce a different approach to compromise embedded infotainment systems, with both software and hardware attacks. 

While previous methods focused on OS and network hacking (access to DBus, telnet, firmware update mechanism…), those vulnerabilities do not exist anymore and different approach had to be used, using 3rd party applications. Multiple protections had to be bypassed, such as multiple level of signature (installation package, code-signing), and read-only file systems just to name few.
Post-exploitation forensics demonstrated that the vulnerabilities identified would likely be exploited in many different cars.

How to proceed to test such systems? What are the steps to compromise infotainment system and what vulnerabilities can be found and exploited?

#### Bio
Benjamin Lafois is a senior security consultant that has been working in IT security and compliance for more than 10 years. Benjamin is an expert penetration tester on distributed systems as well as modern infrastructures such as IoT, embedded devices and OT systems.
Benjamin has identified several zero-day vulnerabilities on IoT and ICS devices.  He has been involved on critical projects in Oil & Gas projects. 
He also has application assessment expertise and is a Java-guru. 

* * *
### Rapid Prototyping For Badges
Securelyfitz and friends

#### Abstract
Messy wires can get the job done, but leveling up your hardware hacking sometimes requires some custom circuit boards.
This workshop will be a crash course in rapid prototyping for hardware hacking. We'll start you off with a complete schematic for flashing some LEDs. After a brief lecture about how PCBs are made, you'll get to adjust your schematic, layout components in Eagle or KiCAD PCB layout software, and customize it with some artwork. With help, you'll manufacture a PCB on a PCB Mill, and if time permits you can assemble it in class or bring it to the HHV/SSV to assemble.

You'll walk away with your own custom PCB badge with flashy lights and a better understanding of how to make your own custom PCBs in the future.

#### Bio
Joe FitzPatrick (@securelyfitz) is an Instructor and Researcher at SecuringHardware.com. Joe has spent over a decade working on low-level silicon debug, security validation, and penetration testing of CPUS, SOCs, and microcontroller. He has spent the past 5 years developing and leading hardware security-related training, instructing hundreds of security researchers, pen-testers, hardware validators worldwide. When not teaching classes on applied physical attacks, Joe is busy developing new course content or working on contributions to the NSA Playset and other misdirected hardware projects, which he regularly presents at all sorts of fun conferences.

* * *
### Infrared: New Threats Meet Old Devices
Wang Kang

#### Abstract
Before the Bluetooth technology kicks in, infrared remote control has been widely used. Many systems still use IR as their control interface. With the proliferation of new smart devices with IR-related components, such as face recognition systems, night vision infrared cameras, slow motion cameras, etc., this ancient technology may bring some new attack surfaces.

First, we will demonstrate a new attack scenario. After a COTS security camera is pwned through Internet, the infrared night vision fill light could be flashed to control devices such as TV and AC. In this way, dumb devices that were originally considered to be air-gapped will also face security threats from the network side. With much greater TX power, larger area could be influenced. Additional attack surfaces will also be discussed. 

Second, we will demonstrate the use of an electric drill and a pure mechanical design similar to a fan blade, constructed as a Spatial Light Modulator. We will demonstrate how to construct a remote control signal that can be recognized by COTS IR remote control from still infrared light. Who said hacking an electric fan doesn't matter?  

Third, we will analyze the frame structure of an infrared remote control signal by utilizing a smartphone with 960fps 'Super Slow-mo' function as a poor man's logic analyzer.  

#### Bio
Wang Kang is a Security Expert of Alibaba Group, focusing on security issues of IoT, cyber-physical system, V2X, and trusted computing. He is a contributor of Linux Kernel, (TDD-LTE USB Dongle support) as well as a founder of the Tsinghua University Network Administrators. He was a speaker at Black Hat {Europe 2015, USA 2017, USA 2018, Asia 2019}, Virus Bulletin 2018, HITB {Dubai 2018, AMS 2019}.

* * *
### Making A Less Shitty Sao: How To Use Kicad To Build Your First Pretty Pcb
Steve Ball (hamster)

#### Abstract
SAOs are everywhere at Defcon, but for many, it's hard to imagine how to design and manufacture them.  In this talk, we'll go through the process of taking artwork to a final PCB that is ready to order.  Along the way we'll talk about different PCB layers and their effects in art, schematic capture, and options available at the board house.

#### Bio
hamster has been making badges for dczia and dc801 for the last 5 years, and has been an all-around hardware hacker for many more.  He enjoys bending commercial design software to the silly and open sourcing the result.

* * *
### Ebolaphone Or Bust
SciaticNerd

#### Abstract
We should all invest in being lifelong learners. That much is a given. When challenged to come up with something new for a boss’s Summer Project, I combined my love of hunting for hardware with some software learning to set up my own phone system. This kicked off an adventure in questing for hardware and figuring out how to set things up. Expect to hear about how to find things, how simple is sometimes better, and we’ll even risk a live demo of how to prep and get ready to deploy one of the phones!

#### Bio
SciaticNerd has been working in the field of Digital Identity since 2002, first as a trainer, then advancing to trusted and engineering roles. Along the way he's connected with people in the computing community who have a passion for helping others to learn and grow. He speaks and volunteers at several conferences, coordinates the San Antonio, Texas BSides conference, and attends and contributes to local groups. He also promotes and discusses involvement with computing, security, privacy, technology related activities through podcasts like Security Endeavors, Hackers with Bourbon, Grumpy Hackers, DangerousMinds, and others.

* * *
### Understanding & Making Pcb Art
TwinkleTwinkie

#### Abstract
PCB Art is all over DEF CON and for some attendees one of their primary goals is to see, admire, and collect some of the dozens of stunning examples of PCB Art that premieres at DEF CON every year.  In this talk I will walk you through an explanation of what a PCB is, how it's made, how PCB Artists use the limitations of the PCB Manufacturing process to produce stunning artwork and finally how you can make your own PCB Art using Inkscape & KiCAD.  This talk is intended for anyone who appreciates PCB Art, wants to make their own PCB Art, or just wants to know how the sausage gets made.

#### Bio
TwinkleTwinkie is an independent PCB Artist and has manufactured dozens of Artistic PCB Badges & Indie Badge Addons. His work was featured in Hackaday’s 2018 “Badge Life” Documentary. Some of his notable works that he has produced are: Arc Badge, BSides Vancouver 2019 Badge, BSides Atlanta 2019 Badge, Queercon 15 Badge Top Board & Access Pass, Krusty the It "SAO", Prince & Pharoah OSHCat "SAO" for OSHPark, the Cheshire Cat "SAO", and the Chestoro "SAO".

* * *
### What You Print Is Not What You Get Anymore: Mitm Attack On 3D Printers Network Communications
Hamza Alkofahi

#### Abstract
Additive Manufacturing (AM) and 3D Printing were conceived to reduce the cost of the prototyping process. Over time,  these technologies became faster, more accurate, and much more affordable.  All of these factors, as well as the potential to use AM in production parts and systems,  have helped rapidly drive the growth of AM in both industrial and personal uses.  Thus, there is a concomitant demand to understand the implications of cybersecurity in this field and these systems. In our research, we show how manufacturers of high-end 3D printers failed to protect the confidentiality and integrity of the printed 3D models. Also, our proof of concept demonstrates how network attacks (such as MITM) on 3D printers communication channels can cause a massive impact (such as stealing, replacing or even sabotaging models) on the whole printing process.

#### Bio
Hamza is a cybersecurity researcher and a white-hat hacker, currently doing his Ph.D. at Auburn University. He is interested in vulnerability assessment, reverse engineering, and detecting business logic vulnerabilities. He developed the first parser for a closed source file format (CMB) also built an automated system for detecting vulnerabilities in critical infrastructure websites.

* * *
### Hacking Con Badges for Fun and Profit
Rob Rehr

#### Abstract
designs before the event starts. This can often be enough information to start crafting a hack for the badge, leading to a large advantage if the conference holds a badge hacking competition.

Additionally, teams are now making accessories for their badges, known as Shitty Add-ons (SAOs). While the main use of SAOs seems to be a way to add more flashy features to badges, increasingly, more and more badges are utilizing the serial communication lines outlined in the SAO standard to control and expand badge and capabilities. In some cases, add-ons are being used for challenges and CTFs, where important information is being transferred between and/or stored on add-ons.

In this talk I'll go over my techniques for hacking badges pre-con, including the original Bender Badge and the BSides PDX Badge. I'll also show off a man-in-the-middle tool I've been developing for SAOs, allowing for the monitoring and manipulation of i2c traffic on the badge. I'll also demonstrations on how to interface with the tool and use it to hack badge add-ons.

#### Bio
Rehr is a hardware hacker and senior electrical engineer at IDEO, with an excitement towards embedded systems design and repurposing. When not planning attacks on unreleased hardware devices, Rehr enjoys running, cycling, and repurposing Furbys.

* * *

## Video List
###Joe Grand
[JTAGulator: Introduction and Demonstration](https://www.youtube.com/watch?v=uVIsbXzQOIU)
[JTAGulator: UART Discovery](https://www.youtube.com/watch?v=yYCDOWI1xfo)

###NorCal715
[Replacing a jack on a circuit board when the copper pads are missing](https://www.youtube.com/watch?v=cTnVg6Pmf-U)

###Jeri Ellsworth
[Resistive Multi-touch Pad Prototype](https://www.youtube.com/watch?v=d7eQ2LHzYMQ)
[Homebrew NMOS Transistor Step by Step - So Easy Even Jeri Can Do It](https://www.youtube.com/watch?v=w_znRopGtbE)
[Make a Point Contact Transistor at home](https://www.youtube.com/watch?v=vmotkjMSKnI)
[Magnetic Logic - Forgotten Technology](https://www.youtube.com/watch?v=p7SkE5pERtA)
[Secret to Learning Electronics - Fail and Fail Often](https://www.youtube.com/watch?v=xhQ7d3BK3KQ)

###LiveOverflow
[RSA Power Analysis Side-Channel Attack - rhme2](https://www.youtube.com/watch?v=bFfyROX7V0s)
[Hardware Power Glitch Attack - rhme2 Fiesta (FI 100)](https://www.youtube.com/watch?v=6Pf3pY3GxBM)

###CrowdSupply
[Searching for the Light Using OpticSpy to Receive Optical Transmissions](https://www.youtube.com/watch?v=O46FxU2M9bI)
[Design and Reverse Engineering Playing on both sides of the field](https://www.youtube.com/watch?v=f9hjALIymkw)
[How to Make Your Own Designs Hackable](https://www.youtube.com/watch?v=HEERR0PQ59Q)
[Kicad Designing With Complex Shapes](https://www.youtube.com/watch?v=AfmdjmGnVgo)
[Making Open Source Schematics Not Suck](https://www.youtube.com/watch?v=lId2NJX8NBc)

###Applied Science
[Tutorial How to design a transistor circuit that controls low-power devices](https://www.youtube.com/watch?v=8DMZSxS-xVc)

###Great Scott
[Battery Spot Welder (CD Welder) DIY or Buy](https://www.youtube.com/watch?v=5TVNdMqVZpk)
[DIY LiPo ChargeProtect5V Boost Circuit](https://www.youtube.com/watch?v=Fj0XuYiE7HU)
[How to Solder properly Through-hole (THT) & Surface-mount (SMD)](https://www.youtube.com/watch?v=VxMV6wGS3NY)

###Scanlime
[Intel Euclid Teardown - scanlime_022](https://www.youtube.com/watch?v=0tYpfqi3KbY)
[Flexible Keypad Experiment - scanlime_023](https://www.youtube.com/watch?v=zultG4QwgTg)

###StrangeParts 
[Bringing BACK The iPhone Headphone Jack - in China](https://www.youtube.com/watch?v=utfbE3_uAMA)
[Inside a Huge PCB Factory - in China](https://www.youtube.com/watch?v=ljOoGyCso8s)
[How I Made My Own iPhone - in China](https://www.youtube.com/watch?v=leFuF-zoVzA)
[How I Upgraded My iPhone Memory 800 - in Shenzhen, China](https://www.youtube.com/watch?v=rHP-OPXK2ig)
[I found wireless LEDs - no batteries needed in Akihabara, Tokyo](https://www.youtube.com/watch?v=PsUsByrOveE)

###Make
[Circuit Skills Circuit Board Etching](https://www.youtube.com/watch?v=tWnfnt2rNO0)
[Collins Lab: Schematics](https://www.youtube.com/watch?v=9cps7Q_IrX0)
[MAKE presents: The Capacitor](https://www.youtube.com/watch?v=ZYH9dGl4gUE)
[MAKE presents: The Diode](https://www.youtube.com/watch?v=AqzYsuTRVRc)
[MAKE presents: The Transistor](https://www.youtube.com/watch?v=-td7YT-Pums)

###Adafruit Industries
[Collins Lab Desoldering](https://www.youtube.com/watch?v=N_dvf45hN6Y)
[Collins Lab Soldering](https://www.youtube.com/watch?v=QKbJxytERvg)
[Collins Lab Surface Mount Soldering](https://www.youtube.com/watch?v=QzoPxvIM2qE)

###Kevin Darrah
[Easy way to Solder Surface Mount Parts! - How I do it](https://www.youtube.com/watch?v=qqoHTKhIBRo)

###Pace World Wide
[Basic Soldering Lesson 1 - "Solder & Flux"](https://www.youtube.com/watch?v=vIT4ra6Mo0s)
[Basic Soldering Lesson 2 - "Soldering To PCB Terminals"](https://www.youtube.com/watch?v=Mrhg5A1a1mU)
[Basic Soldering Lesson 6 - "Component Soldering"](https://www.youtube.com/watch?v=AY5M-lGxvzo)
[Basic Soldering Lesson 7 - "Integrated Circuits: The DIP-Type Package"](https://www.youtube.com/watch?v=VgcPxdnjwt4)
[Basic Soldering Lesson 8 - "Integrated Circuits"](https://www.youtube.com/watch?v=sTv3gK9tAKA)
[Basic Soldering Lesson 9 - "Integrated Circuits: The Flatpack & Other Planar-mounted Components"](https://www.youtube.com/watch?v=Nq5ngauITsw)

###FSE elearning
[Basic Soldering Technique](https://www.youtube.com/watch?v=AqvHogekDI4)

###ElectroBOOM
[Destruction with EMP Device, Understand and Battle EM Interference](https://www.youtube.com/watch?v=Y5M6YKR7wUw)

###RetroComputing
[DTV engineering Jeri Ellsworth](https://www.youtube.com/watch?v=g05Wfqv-8es)

###RetroGameModz
[PCB solder pad repair & corrosion clean up - The epoxy method](https://www.youtube.com/watch?v=vx50YtEC2S8)
[Repair tip - What to look for on corroded through-hole PCBs](https://www.youtube.com/watch?v=S9q3s4mB5PM)
[Soldering to a QFP that has broken pins - Maxtor HDD repair](https://www.youtube.com/watch?v=xqkXvmvusws)
[LCD TV repair - Samsung LW20M21CP not powering up](https://www.youtube.com/watch?v=zxqDLDNuCfw)

###CuriousInventor
[How to Desolder Through-Hole Parts, Why Some Joints are Difficult](https://www.youtube.com/watch?v=Z38WsZFmq8E)

###G-Lon
[iPhone 6S Plus Replace RAM](https://www.youtube.com/watch?v=mWqNY7umCNg)
[iPhone 7 Plus change the CPU Baseband CPU and Hard disk](https://www.youtube.com/watch?v=tWDOZFhCOPw)
[iPhone 7 water damage repair](https://www.youtube.com/watch?v=DjH22xDDhpU)
[iMesa Repair Touch ID](https://www.youtube.com/watch?v=txAJJW8bZy8)

###Samy Kamkar
[MagSpoof - magnetic stripe spoofer / credit card magstripe emulator](https://www.youtube.com/watch?v=UHSFf0Lz1qc)
[OpenSesame - hacking garages in seconds using a Mattel](https://www.youtube.com/watch?v=iSSRaIU9_Vc)
[PoisonTap - exploiting locked machines w/Raspberry Pi Zero](https://www.youtube.com/watch?v=Aatp5gCskvk)
[USBdriveby - exploiting USB in style](https://www.youtube.com/watch?v=aSLEq7-hlmo)

###DEFCON
[DEF CON 22 - Joe Grand aka Kingpin - Deconstructing the Circuit Board Sandwich](https://www.youtube.com/watch?v=O8FQZIPkgZM)
[DEF CON 23 - Hardware Hacking Village - Soldering 101 - Melting metal for fun and profit](https://www.youtube.com/watch?v=u6qVTMNY9Fo)
[DEF CON 24 - Joe FitzPatrick, Joe Grand - 101 Ways to Brick your Hardware](https://www.youtube.com/watch?v=acNu_JFJe50)

###Naomi Wu
[Hardware Manufacturing, LED Rings Pt.3- I demonstrate SMT soldering (poorly)](https://www.youtube.com/watch?v=-g4DgOLSKfg)
[Hardware Manufacturing, LED Rings Pt.2- A Visit to JLCPCB](https://www.youtube.com/watch?v=r5hrP5iMTmM)
[Wearable Video Player Boots!](https://www.youtube.com/watch?v=PyajZsQlNe4)
[Infinity Skirt Build](https://www.youtube.com/watch?v=Zo3SG2iNSXg)
[Face Changer- Biometric Countermeasures Based on Traditional Chinese Opera](https://www.youtube.com/watch?v=D-b23eyyUCo)

