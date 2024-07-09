WindOS-Pi
==========  
.. raw:: html

    <img src="https://raw.githubusercontent.com/terminalMCP/WindOS-Pi/devel/media/windtermCursor.png?raw=true" alt="WindOS logo" style="width: 10%;">

FullPageOS (WindOS-Pi version)

This is a fork from https://github.com/guysoft/FullPageOS.

Original README file can be found [here](README.rst)

Proposed changes to the original version:

### Add
- Add WindOS splash image
- Add WindOS HTML, CSS, and Java to /www/
- HID Drivers for 5-wire resistive and other touch display.

### Update
- Chromium to the latest version
- Power profile and display sleep settings

### Remove/Disable
- Camera driver
- Usage statistics
- FullPageOS Dashboard
- FullPageOS Welcome page
- Bluetooth driver

A `Raspberry Pi <http://www.raspberrypi.org/>`_ distribution to display one webpage in full screen. It includes `Chromium <https://www.chromium.org/>`_ out of the box and the scripts necessary to load it at boot.
This repository contains the source script to generate the distribution out of an existing `Raspbian <http://www.raspbian.org/>`_ distro image.

FullPageOS started as a fork from `OctoPi <https://github.com/guysoft/OctoPi>`_, but then joined the distros that use `CustomPiOS <https://github.com/guysoft/CustomPiOS>`_.
