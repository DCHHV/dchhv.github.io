---
title: DC30 Challenge Write Up
layout: page
---

<br>
<br>

## DC30 HHV Write Up

### Hidden Badge Flag 1

This flag was meant to be the starting point for the CTF. It was designed to be simple first step that would introduce participants to the theme/story, CTFd, and most importantly, the HHVDC30 and its datasheet. While reading through the datasheet, one string should have stood out from the rest under the `features` section on the front page

<img src="/assets/images/dc30/flag_badge1.png" alt="screenshot of HHVDC30 data sheet showing the flag text" width="500" />

A few people did read until the end and noticed there was a recommendation to reach out about getting samples, and that was a great guess, but not the intended first flag. ...maybe in a future CTF.

<br>
<br>

### SAO DRM 1

Participants were given an SAO and asked recreate a hardware resistor DRM using different resistor values. The first step was reversing the DRM schematic from the SAO or the provided layout image to uncover that the circuit was just a voltage divider using R3 and R4. 

<img src="/assets/images/dc30/SAO1_schematic.png" alt="section of HHV CTF Badge showing the resistor divider circuit" width="500" />

The result of the voltage divider, given the values of 820k for R3 and 430k for R4, is IO2 sensing ~1/3 of the voltage output from IO1 (yes, this was checked by outputting 1V, 2V, and 3V to make sure no one was trying to pull a fast one ;D).

At this point, the challenge became creating a 1/3 voltage divider using 10k resistors. Luckily, all that's required for this is making sure R3 is double R4, so there were two possible solutions, put two 10k resistors in series for R3, or stack two 10k resistors in parallel on R4.

Once the voltage divider is correctly assembled, plugging the SAO into the badge gives the flag.

Flag: `HHV{SAO1_s0_passiv3}`.

<br>
<br>

### SAO DRM 1.5

What started as a design mistake, became a challenge. To get the flag, participants had to follow the [SAO1 assembly instructions](dc30#SAO1_assembly), and if they showed the LEDs powered on SAO1 to an HHV volunteer, they received the flag.

Flag: `HHV{bodge_the_planet}`

<br>
<br>

### SAO DRM 0

This challenge was modified partway through the con to become a challenge to get another SAO to pass the SAO1 DRM check. All that was required was to implement a 1/3 voltage divider, using the same pins (5 and 6), on another SAO (or really anything). Show an HHV volunteer that the SAO passed the check and receive the flag.

Flag: `HHV{SAO0_m4k3_ur_0wn_us3}`

<br>
<br>

### Hidden Badge Flag 2

Reading through the datasheet uncovered that there were two UART interfaces. The baudrate for these was not specified, but with a little guess and check of common rates, a response could be found on UART0 wtih 115200 8N1.

<img src="/assets/images/dc30/badge2_datasheet.png" alt="screenshot of HHVDC30 data sheet showing UART interfaces and associated pins" width="500" />

A new line would trigger the badge to send `Shall we play a game?`. This is a reference to the move WarGames, so responding with `Love to` results in the badge sending `the only winning move is to not play`, followed by the flag.

Flag: `HHV{badge2_th3rmonuclear_w4r}`

<br>
<br>

### Hidden Badge Flag 3

Finally, if you looked closely at the datasheet, you'd notice that morse code was listed as one of the serial communication features. By probing some of the HHVDC30's pins, you'd see toggling on PA2. Hooking that up to a logic analyzer, and either manually tracing or using a decoder would outputs the flag.

<img src="/assets/images/dc30/badge3_morse.png" alt="screenshot of Saleae Logic2 showing the logic capture of the morse code signal" width="500" />

Flag: `HHVbadge2cantstopthesignal` or `HHV{badge2cantstopthesignal}` (both were accepted)

<br>
<br>

If you had a chance to participate, we hope you enjoyed the HHV CTF. Either way, we hope you'll come hack with us next year!

<br>
<br>