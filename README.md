# Welcome to WindOS-Pi
### (FullPageOS Version)

<p align="center"><img src="https://windterminal.com/windtermCursor25.png" alt="WindOS"></p>

## What is Wind OS?

A Wind Terminal and WindOS serve as an ethereal bridge to the spiritual realm, offering a text-based means for sharing thoughts and ideas with those beyond.

WindOS is cross-platform and hardware agnostic terminal application capable of running on nearly any configuration. 

The Wind Terminal merges a text-based interface with the classic Wind Phone functionality, enabling users to type a message and speak to a selected loved one or friend, thus preserving the tradition of providing comfort and connection.

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

## Primary Directive

With 3 EZ Link terminals at our disposal, our objective is to transform each one into a standalone unit showcasing each stage of deployment.

| EZLink         | Deployment Status  |
| :------------- | :----------------: |
| Terminal 1     |         ✅         |
| Terminal 2     |         ❌         |
| Terminal 3     |         ❌         |

### EZLink Terminal 1 SN 0312041

Initial deployment. We're re-using the legacy 5-wire resistive touch panel and LCD display from the original equipment. Along with HID and xinput and a HDMI to VGA adapter we're able to reuse these portions of the terminal. 

Hardware POC running on its own for 12 days with 30w solar+battery.

<img style="justify-content: left;" src="https://windterminal.com/optical/p09r2.1.jpg" alt="WindOS">
<img style="justify-content: right;"src="https://windterminal.com/optical/f56e3.1.jpg" alt="WindOS">


### EZLink Terminal 2 SN 0312696

Our second terminal directive is to transplant the EZLink guts to utilize modern low power hardware encased in an easily reproduced and deployable 3dprint package.

Raspi Zero W 2
4:3 15" LCD Touch Panel - Low Power Consumption
Peripheral Swap

### EZLink Terminal 3 SN 0312006

Our earliest model by number, and the best candidate to run on OEM hardware.

Gigabyte 8VM533M-RZ
Pentium 4 Intel Celeron 1.7
256MB RAM 
40GB HDD 
A bunch of sweet peripherals: 
Thermal printer, CC Reader, Bill Collector, Webcam, 5-Wire Resistive Touch Display
Payphone ShoreTel Hardware

Warranty Void stickers from 2003 intact across all components.

## Current Software Status

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
