---
title: DC28 Challenge
layout: page
---

<br/>
<br/>

## DC28 HHV Challenge
Welcome to this year's HHV challenges! We've tried to design them for maximum remote fun! Each challenge is a logic analyzer captures (we've taken care of the hard part of capturing signals on some suspicious devices ;D), and it will be your job to figure out what secret messages are being conveyed. Challenges are designed to range in difficulty, but difficulty can be relative, so feel free to ask questions in this channel and/or join the various HHV challenge chats (https://dchhv.org/schedule/schedule.html).

Below are the challenges. Be sure to read the scenario for the challenges, as they will likely give some clues. Additionally, you will need Logic (https://www.saleae.com/downloads/) to open the challenge files. There may also be additional files necessary to solve, and for those challenges the files will be zipped together.

Good luck, and most importantly, have fun! If you've enjoyed these and/or have ideas for future HHV challenges, please reach out! We'd love to have more collaborators for next year!

If you need help, check out [#hhv-meetups-a-text](https://discord.com/channels/708208267699945503/739567085004521533) and [#hhv-meetups-a-voice](https://discord.com/channels/708208267699945503/739571117756383333) on the [DEF CON Discord Server](https://discord.gg/DEFCON)!

### Challenge 1
We sniffed this capture between two communicating parties. We need help figuring out what was said? We believe a critical key was exchanged.

_note: there is a known typo, it should not affect the solution._

[Challenge 1 Capture](/assets/challenge/challenge1.logicdata)

<br>

### Challenge 2
We sniffed this capture between a microcontroller and various eeproms. Unfortunately, the capture was cutoff before we could see the results of the read. Could you figure out what would have come out from the read?

[Challenge 2 Capture](/assets/challenge/challenge2.logicdata)

<br>

### Challenge 3
We sniffed another capture between two communicating parties. I think this one has more layers than the previous captures, they must know that we're listening. See if you can capture the what was exchanged.

[Challenge 3 Capture](/assets/challenge/challenge3.logicdata)

<br>

### Challenge 4
We found a strange, random 7-segment display laying around, but it was flashing too fast for us to read it. It looks like a controller was transmitted to a shift register (74HC595), and the shift register was connected to segment pins of the 7-segment display. We were only able to capture the signals latch, clock, and data signals between the controller and the shift register before we heard someone coming. Can you help us decode what was being set on the 7-segment display?

[Challenge 4 Capture](/assets/challenge/challenge4.logicdata)

<br>

### Challenge 5

_Coming Soon._
<!-- [Challenge 5 Capture](/assets/challenge/challenge5.logicdata) -->
