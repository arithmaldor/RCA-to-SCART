# Copyright and Disclaimer
Copyright: Jacob Proctor 2018

This documentation describes Open Hardware and is licensed under the
CERN OHL v. 1.2.

You may redistribute and modify this documentation under the terms of the
CERN OHL v.1.2. (http://ohwr.org/cernohl). This documentation is distributed
WITHOUT ANY EXPRESS OR IMPLIED WARRANTY, INCLUDING OF
MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN OHL v.1.2 for applicable
conditions

# RCA to SCART Board

Output version of the SCART to RCA board. This one has optional sync attentuation via a jumper (closed to bypass resistor footprint) and
optional power input via microusb for TVs that automatically switch to SCART (just leave the usb and 100 ohm resistor footprints blank if you
don't need this).

# Parts

SCART Connector: K-SCARTX-024, available on Mouser

RCA Connector: PJRAS3X2S01 is available on Mouser and Digikey, but the colors are wrong. Here are the ones I used, a bit cheaper per part:

https://www.ebay.com/itm/QTY-10-6-WAY-PCB-FEMALE-RCA-JACKS-GREEN-YELLOW-BLUE-WHITE-RED-RED-RCA-268N1-14/112220720415?var=null

microusb port: Molex 105017-0001

Resistors: 0805 size, 470 ohm for sync attenuation, 100 ohm for dividing the voltage for RGB and TV detect on pins 8 and 16. Just about any decent
quality ones will do.

Mounting hole size is M3, can be used with motherboard standoffs for mounting on MDF or acrylic or something else.


# Changelog
0.1 - This board is untested, I may be a few soon after which I will update the version number to 1.0 if everything works out.

0.2 - The shield througholes of the microusb port were not connected to ground, this has been fixed. I also moved a few traces
around to make it easier to disconnect pin 8 if it is causing your TV to force to 16:9.


# OSHPark
https://oshpark.com/shared_projects/0eRQCdKa