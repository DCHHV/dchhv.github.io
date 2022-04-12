---
title: HHV Rube Goldberg Machine 
layout: page
---

To celebrate DEF CON 30, the Hardware Hacking Village (HHV) is hosting a Rube Goldberg Machine (RGM) Event! This idea has been kicking around the HHV volunteer circle in one shape or another since at least DEF CON 20 so it's about time it happened! The goal is to create a series of devices that combine to form an end-to-end Rube Goldberg machine for transmitting messages. The hope is that all sorts of creative devices will be connected up to each other to move bits through various complicated and fun analog/digital methods. Ideas have ranged from simply wiring RX to TX to using radios to bounce the message off the moon!

In order to make this event successful it's helpful to standardize the connectivity requirements between devices. The hope is that selecting a simple specification (RS-232) and publishing it early will allow:
* Participants to prepare more advanced materials for the conference ahead of time
* Participants to construct their own devices on site as well

## Connectivity
* Devices all speak RS-232 (TIA-232-F)
* Devices will communicate at 9600 Baud 8N1 w/o flow control
* Each device will expose a DCE and a DTE port
* Devices are connected to each DCE -> DTE in series
* Messages are input by an external device connected to the DTE port of the first RGM device and received by another external device connected to the DCE port of the last RGM device
* All signaling and electrical requirements should follow the TIA-232-F specification
    * Ex: -15V to +15V (will require level shifter if involving TTL electronics)

## Between the ports
* A device can do whatever the designer wants in order to move data from the DCE to the DTE port
* The simplest device is two DB-9 connectors with two wires tied between them
    * Shared ground (pin 5)
    * RX from DCE (pin 2) to TX of DTE (pin 3)
* Devices must adhere to all safety precautions
    * This event is not meant to circumvention restrictions imposed by the conference, hotel, property, or local/state/federal jurisdiction
    * Participants should strive to not cause damage to any of their neighboring devices
* Latency should be kept to less than 600 seconds
    * We don't want the conference to end before a message is transmitted!
    * Exceptions can be made for spectacular reasons :)

## Joining/Parting the network
* Like all large archaic telecommunication providers, the HHV requires new RGM devices to pass certification before joining the network
    * HHV will provide a loopback test device which can be used to validate that the TX and RX functionality of an RGM device are working
    * HHV reference devices should allow participants to quickly test
* An HHV volunteer will coordinate connecting your RGM device to end of the RGM chain
* Once attached, a new test signal from beginning to end to demonstrate successful connectivity
* If a participant wishes to remove their RGM device they are free to do so; but please inform an HHV volunteer so that the RGM chain can be restored

## Summary
In order to join the RGM, devices will employ standard RS-232 (TIA-232-F) for communications. Each device will be responsible for presenting a Data Terminal Equipment (DTE) port and a Data Communication Equipment (DCE) port. At a high level, participant devices will be expected to receive on their DCE port, and retransmit the data on their DTE port. Communication will be standardized at 9600 Baud, 8 data bits, No parity bit, and 1 stop bit (9600B 8N1). It is up to the device to use whatever creative mechanism it wants to move data between the two ports it exposes. System are asked to try to keep latency of message transmission to under 600 seconds to keep the messages flowing. Our goal isn't for the conference to end before a message has been transmitted!
