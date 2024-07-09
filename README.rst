.. raw:: html

    <img src="https://raw.githubusercontent.com/terminalMCP/WindOS-Pi/devel/media/windtermCursor.png?raw=true" alt="WindOS logo" style="width: 10%;">

WindOS-Pi (FullPageOS version)

 A Wind Terminal and WindOS serve as an ethereal bridge to the spiritual realm, offering a text-based means for sharing thoughts and ideas with those beyond.

The Wind Terminal combines a text-based interface with the traditional Wind Phone function, allowing users to either pick up the receiver or type out a message and speak to their chosen loved ones, continuing the legacy of comforting connection.

 Our objective is to offer the Wind Terminal and WindOS as an extension of the Wind Phone project, continuing efforts to give back to our communities and support recovery, reconciliation, and personal solace during difficult times.

Do you have an old laptop or tablet kicking around? A forgotten tower PC, fax machine, netbook, sidekick, or palm pilot? We encourage you to find the personal Wind Terminal platform of your own by transforming lost technology and 'ewaste' into memories and connections once again.

WindOS is cross-platform and medium agnostic capable of running on nearly any configuration.

Proposed changes to the original version:

 ## Add
- Add WindOS splash image
- Add WindOS HTML, CSS, and Java to /www/
- HID Drivers for 5-wire resistive and other touch display.

 ## Update
- Chromium to the latest version
- Power profile and display sleep settings

 ## Remove/Disable
- Camera driver
- Usage statistics
- FullPageOS Dashboard
- FullPageOS Welcome page
- Bluetooth driver

This is a fork from https://github.com/guysoft/FullPageOS.

FullPageOS is a `Raspberry Pi <http://www.raspberrypi.org/>`_ distribution to display one webpage in full screen. It includes `Chromium <https://www.chromium.org/>`_ out of the box and the scripts necessary to load it at boot.
This repository contains the source script to generate the distribution out of an existing `Raspbian <http://www.raspbian.org/>`_ distro image.

FullPageOS started as a fork from `OctoPi <https://github.com/guysoft/OctoPi>`_, but then joined the distros that use `CustomPiOS <https://github.com/guysoft/CustomPiOS>`_.
