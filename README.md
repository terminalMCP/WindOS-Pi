# Welcome to WindOS-Pi (FullPageOS Version)

<p align="center"><img src="https://windterminal.com/windtermCursor25.png" alt="WindOS"></p>

## What is Wind OS?

A Wind Terminal and WindOS serve as an ethereal bridge to the spiritual realm, offering a text-based means for sharing thoughts and ideas with those beyond.

WindOS is cross-platform and hardware agnostic terminal application capable of running on nearly any configuration. 

The Wind Terminal combines a text-based interface with the traditional Wind Phone function, allowing users to either pick up the receiver or type out a message and speak to their chosen loved ones, continuing the legacy of comforting connection.

**Our objective is to offer the Wind Terminal and WindOS as an extension of the Wind Phone project, continuing efforts to give back to our communities and support recovery, reconciliation, and personal solace during difficult times.**

Do you have an old laptop or tablet kicking around? A forgotten tower PC, fax machine, netbook, sidekick, or palm pilot? We encourage you to find the personal Wind Terminal platform of your own by transforming lost technology and 'ewaste' into memories and connections once again.

### To learn more, try our [Live WindTerminal Demo](https://windterminal.com) 

## What is a Wind Phone?

The Telephone of the Wind, known as Kaze No Denwa (風の電話) in Japanese, was created by Itaru Sasaki in 2010. He established this unique phone booth in his garden in Ōtsuchi, Japan, to cope with the grief of losing his cousin to cancer. The booth features an old-fashioned rotary phone, not connected to any network, allowing individuals to hold one-sided conversations with their deceased loved ones, thereby finding solace and a sense of continued connection.

*"The telephone won't carry my voice, so I let the wind do it."*
	- Itaru Sasaki

In 2011, the Tōhoku earthquake and tsunami devastated the northeastern coast of Japan, causing immense loss of life and destruction. Ōtsuchi was particularly hard-hit, with many residents losing family members and friends. The Wind Phone gained widespread attention as it provided a way for the bereaved to express their grief and find comfort in the aftermath of this disaster. It became a symbol of hope and healing for many affected by the tragedy.

Over time, the Wind Phone has drawn thousands of visitors from across Japan and around the world, each seeking to process their own losses. Its story has inspired similar installations in other countries, emphasizing the universal need for emotional expression and connection in times of grief.

The Wind Phone's profound impact highlights the importance of finding personal and communal ways to cope with loss and underscores the resilience of the human spirit.

Join us in exploring the possibilities in finding connection amongst the disconnected.

## Current Status

### Platform Compatibility

A main goal is to offer WindOS on a variety of platforms such as x86, ARM, PowerPC, RISC-V and more!

Our initial deployment utilizes a customized version of FullPageOS running on a Raspberry Pi 4 and Zero 2W.

| Architecture   | Status  |
| :------------- | :-----: |
| x86	         |   ❌    |
| ARM(raspi)     |   ✅    |
| PowerPC        |   ❌    |
| RISC-V         |   ❌    |
| MIPS           |   ❌    |

### Software Architecture

For maximum compatibility the terminal is written simply in HTML, CSS, and JS.

Our objective is to offer WindOS in a bootable instance and allow any historical piece of hardware to load our ethereal bridge.

## Deployed Wind Terminals

### WindOS-Pi (FullPageOS Version)

Solar powered Raspberry Pi 4b+

### Changes to the original FullPageOS version:

#### Add
- Add WindOS splash image
- Add WindOS HTML, CSS, and Java to /www/
- HID Drivers for 5-wire resistive and other touch display.

#### Update
- Chromium to the latest version
- Power profile and display sleep settings

#### Remove/Disable
- Camera driver
- Usage statistics
- FullPageOS Dashboard
- FullPageOS Welcome page
- Bluetooth driver

This is a fork from https://github.com/guysoft/FullPageOS.

FullPageOS is a [Raspberry Pi](http://www.raspberrypi.org/) distribution to display one webpage in full screen. It includes [Chromium] (https://www.chromium.org/) out of the box and the scripts necessary to load it at boot.
This repository contains the source script to generate the distribution out of an existing [Raspbian](http://www.raspbian.org/) distro image.

FullPageOS started as a fork from [OctoPi](https://github.com/guysoft/OctoPi), but then joined the distros that use [CustomPiOS](https://github.com/guysoft/CustomPiOS)
