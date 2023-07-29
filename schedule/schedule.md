---
title: DC31 Schedule
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
| Thursday, Aug 10 | Setup (Closed to Public) |
| Friday, Aug 11 | 10:00 - 18:00 |
| Saturday, Aug 12 | 10:00 - 18:00 |
| Sunday, Aug 13 | 10:00 - 13:00 |

The village will be located in the Caesars Forum - [venue map here](https://defcon.outel.org/dcwp/dc31/maps/maps-caesars-full/)

<br/>
<br/>

## Events Schedule

| Event | Times |
| --- | ------|
| Prizes for all events announced | Saturday Aug 12, 16:00  |

[RoboSumo](/events/robosumo.html) will be available to play and test code during all open hours. Competition will be Saturday at 13:00 for as long as it takes to run a bracket.

[HHV Rube Goldberg Machine](/events/hhv_rgb.html) will be running during all open hours. Come by and bring some text to print! Modules will be allowed to be added and removed all open hours as well. Those that want to be involved in the judging will need to have had their module inline before Saturday at 16:00 when prizes will be announced.

[Make Your 0wn Use Contest](/events/makeyourownuse.html) will be running during all open hours. We have space for display, if you are comfortable leaving it out for people to look at. Judging will conclude on Saturday at 16:00 when prizes will be announced.

[HHV Capture The Flag (CTF)]() is back in person and will be running during all open hours. More details to follow!

<br/>
<br/>

## Talk/Workshop Schedule

| Time | Talk/Workshop |
| ---- | ------------- |
| Friday, Aug 11th, 1100~1120 | Talk - [The Creation Of The Out-Of-Band Anti Virus Dock (Oobavd)](#the-creation-of-the-out-of-band-anti-virus-dock-oobavd) |
| Friday, Aug 11th, 1200~1250 | Workshop - [Introduction To Esp8266/Esp32 Microcontrollers And Building A Wi-Fi Deauthentication Detector](#introduction-to-esp8266esp32-microcontrollers-and-building-a-wi-fi-deauthentication-detector) |
| Friday, Aug 11th, 1300~1350 | Talk - [Sadprotocol Goes To Hollywood: Hijacking An Ip Camera Stream As Seen In The Movies](#sadprotocol-goes-to-hollywood-hijacking-an-ip-camera-stream-as-seen-in-the-movies) |
| Friday, Aug 11th, 1400~1450 | Talk - [Open Sesame! How To Open One Thousand And One Locks In The 21St Century ?](#open-sesame-how-to-open-one-thousand-and-one-locks-in-the-21st-century-) |
| Friday, Aug 11th, 1500~1550 | Workshop - [Radiation Detection For The Rest Of Us - Diy Radiation Spectroscopy](#radiation-detection-for-the-rest-of-us---diy-radiation-spectroscopy) |
| Saturday, Aug 12th, 1500~1550 | Talk - [Generating Rf With Stock Hardware For Drones](#generating-rf-with-stock-hardware-for-drones) |

## Talk/Workshop Details
* * *
### The Creation Of The Out-Of-Band Anti Virus Dock (Oobavd)
Pengfei "BigZaddy" Yu Bosen Zhang, Howard Yang, Tan Jing Zhi
#### Abstract
USB-based attacks account for over 52% of all cybersecurity attacks on operational technology (OT) systems in the industrial control systems (ICS) industry. Stuxnet's discovery in 2015 showed the vulnerability of air-gapped systems, previously considered invulnerable. These systems are found in secure military organizations and SCADA systems. The societal impact of such attacks can be enormous, as evidenced by Stuxnet's impact on Iran's nuclear programs.

Air-gapped systems, while considered secure, mostly require mobile storage devices like USB sticks for updates and data transfers, exposing them to malware. Adding peripherals like keyboards and mice will also render the systems vulnerable to BadUSB attacks. This all can be prevented by OOBAVD, which acts as an intermediary between air-gapped systems and USB devices, blocks malicious files from entering the air-gapped systems. OOBAVD being out of band also mitigates the risk of malware attacking the host's antivirus software.

So what exactly is OOBAVD and how does one take an anti-virus out of band?
#### Bio
Pengfei is a professional cyber firefighter, always jumping from fire to fire.
Bosen loves breaking things, he lives by his mantra: "Just Nuke It"
Howard is the data science-wiz, we asked him for one good model, and he gave us five.
Jing Zhi is slenderman, the hardware padawan.

* * *
### Introduction To Esp8266/Esp32 Microcontrollers And Building A Wi-Fi Deauthentication Detector
Ryan Zagrodnik
#### Abstract
Join us as we provide an introduction to the Adruino IDE and the ESP8266 microcontroller. Receive a free ESP8266 **(Limited to the first 30 attendees to approach the speaker before the start of the talk and ask for a kit)**, and build your own Wi-Fi deauthentication detector. We will walkthrough assembly, flashing, and configuration steps.
#### Bio
Ryan Zagrodnik has been consulting as a Penetration Tester for SynerComm for almost five years. Ryan brings over sixteen years of red and blue team experience. Ryan started his career maintaining large enterprise networks as a System Administrator in 2007. Ryan earned his CISSP in 2011 and has been working in offensive security ever since. Prior to starting at SynerComm, Ryan spent three years on an internal red team at a Fortune 1000 organization. Ryan also spent several years working in offensive and defensive security roles for large enterprises who provided services for the U.S. Department of Defense and Department of Education.
* * *
### Sadprotocol Goes To Hollywood: Hijacking An Ip Camera Stream As Seen In The Movies
Octavio Gianatiempo Javier Aguinaga
#### Abstract
When people think about a compromised surveillance camera, privacy is their first concern. But what about attacking the stream integrity? How hard can this movie hacking stunt be in real life? Previous research has focused on the network layer, but we wondered if we could achieve the feat by finding a zero-day on a device we owned.

Our research has uncovered two LAN RCE vulnerabilities in the implementation of Hikvision’s Search Active Devices Protocol (SADP) and SDK server found in several Ezviz products. Exploiting either of these bugs, we managed to serve a victim an arbitrary stream by tunneling their connection with the camera into an attacker-controlled server while leaving all other camera features operational.

We will take a deep dive into the whole research process: firmware analysis, vulnerability discovery, building a toolchain to compile a debugger for the target, developing an exploit capable of bypassing ASLR, and all the details about the Hollywood-style post-exploitation including tracing, in memory code patching and manipulating the execution of the binary that implements most of the camera features.

By filling the gap between IoT hacking and the big screen, we put the integrity of video surveillance systems into question and hope to raise awareness about the security risks posed by these devices.
#### Bio
Octavio Gianatiempo is a Security Researcher at Faraday and a Computer Science student at the University of Buenos Aires. He's also a biologist with research experience in molecular biology and neuroscience. The necessity of analyzing complex biological data was his point of entry into programming. But he wanted to achieve a deeper understanding of how computers work, so he enrolled in Computer Science. As a Security Researcher at Faraday, he focuses on embedded devices, reverse engineering and fuzzing open and closed source software to find new vulnerabilities and exploit them.

Javier Aguinaga is a self-taught reverse engineer with a principal focus in exploiting, currently working at Faraday for the last 7 years. He started his journey as a hobbyist electronic enthusiast and began learning how to crack security systems for video games. This led him to pursue a career in reverse engineering, where he has gained extensive experience analyzing and breaking down complex systems. With his expertise, Javier has been able to identify vulnerabilities in various technologies and has presented his findings at several conferences. He looks forward to sharing his insights and learning from others at the upcoming conference.
* * *
### Open Sesame! How To Open One Thousand And One Locks In The 21St Century ?
Thomas BYGODT
#### Abstract
In an ever increasingly connected society, we are often introduced to “new and improved” devices that offer smart capabilities, and door locks are no exception. Increased security and ease of use are some of the key selling points for these locks.  
While some devices are hard to attack, the majority are not, because manufacturers are not following simple security practices in their physical, hardware and code design. Improving their security is essential, but how do you do that when hardware and IoT hacking looks like black magic at every step?  
From electrical signals inside the lock to the Bluetooth Low Energy (BLE) communication with a mobile application developed using a widely used software development kit (SDK), I will share my simple spells that has led me to find vulnerabilities impacting tens of thousands of smart devices from multiple manufacturers. That and why never giving up can pay off!
#### Bio
Thomas BYGODT is a penetration tester at Orange Cyberdefense, a CTF player and a developer. 
He does not want to remain passive in front of the technologies that interact with the real world. Testing and understanding them allows us to better understand their limits, both for people's privacy and for their security. He has been specializing in connected devices for 3 years now. 
* * *
### Radiation Detection For The Rest Of Us - Diy Radiation Spectroscopy
Patrick Kiley none
#### Abstract
When radiation detectors are mentioned, one tends to think of the
geiger counter. This type of detector happens to be just one method of
radiation detection. This workshop will introduce gamma ray
spectrography, which measures the energy absorbed by the individual
gamma rays. This energy level can let us know what radioactive isotope
generated the gamma and can aid in identifying the material being
examined.
#### Bio
Patrick Kiley is a Security Consultant doing hardware penetration
testing and has over 20 years of information security experience.
Patrick has performed research in Avionics security, Vehicles, and
even managed to brick a Tesla. Patrick has experience in penetration
testing all the things, hardware hacking, IoT and Transportation.
* * *
### Generating Rf With Stock Hardware For Drones
David Melendez
#### Abstract
The popularity of cheap and DIY drones has made them a target for attackers using radiofrequency (RF) signals. Frequency hopping is a technique that can be used to mitigate the risks associated with RF warfare. However, implementing frequency hopping in cheap and DIY drones presents several technical challenges, such as the need for a stable clock and synchronization between the transmitter and receiver without rising hardware costs. Despite these challenges, frequency hopping can significantly enhance the security of consumer and DIY drones making much more challenging or even useless  anti-drone systems' role.
#### Bio
David Melendez is an R&D Embedded Systems Engineer, with over twelve years of experience in cybersecurity and hardware hacking. He has a proven track record of presenting his groundbreaking investigations at prestigious conferences around the world, including DEFCON, BLACKHAT, and ROOTEDCON.

David is also a drone creator and author of the book "Hacking with Drones," which showcases his innovative use of drones in cybersecurity research. With his passion for pushing the boundaries of technology, David is constantly seeking new ways to improve the security and functionality of embedded systems
* * *
