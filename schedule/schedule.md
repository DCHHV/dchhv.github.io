---
title: DC27 Schedule
layout: page
---

[Event Schedule](#event-schedule)

[Talk/Workshop schedule](#talkworkshop-schedule)

[Talk/Workshop Details](#talkworkshop-details)

<br/>
<br/>
## Event Schedule
### Friday

| Time | Events |
|------|--------|
| 1000 | HHV/SSV Startup |
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
| 1100~1150 | Talk - [Another Car Hacking Approach](#another-car-hacking-approach) | Bally's Event Villages Track 1 (Just outside the HHV) |
| 1100~1250 | Workshop - [Rapid Prototyping For Badges](#rapid-prototyping-for-badges) | Inside HHV, Workshop Area |
| 1200~1230 | Talk - [Infrared: New Threats Meet Old Devices](#infrared-new-threats-meet-old-devices) | Bally's Event Villages Track 1 (Just outside the HHV) |
| 1400~1450 | Talk - [Making A Less Shitty Sao: How To Use Kicad To Build Your First Pretty Pcb](#making-a-less-shitty-sao-how-to-use-kicad-to-build-your-first-pretty-pcb) | Inside HHV, Workshop Area |
| 1500~1550 | Talk - [Ebolaphone Or Bust](#ebolaphone-or-bust) | Inside HHV, Workshop Area |

### Saturday

| Time      | Events | Location |
|-----------|--------|----------|
| 1100~1150 | Talk - [Understanding & Making Pcb Art](#understanding--making-pcb-art) | Inside HHV, Workshop Area |
| 1200~1250 | Talk - [What You Print Is Not What You Get Anymore: Mitm Attack On 3D Printers Network Communications](#what-you-print-is-not-what-you-get-anymore-mitm-attack-on-3d-printers-network-communications) | Inside HHV, Workshop Area |
| 1700~1750 | Followup - [Fireside Chat Style Followup To Main Track Talk: Tag-side attacks against NFC](https://defcon.org/html/defcon-27/dc-27-speakers.html#Wade) Bring your questions, get some answers. | Inside HHV, Workshop Area |

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
