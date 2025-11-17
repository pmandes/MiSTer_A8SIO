# MiSTer_A8SIO
Adapter for the SIO port to connect peripheral devices of the 8-bit Atari to the MiSTer FPGA.

## Interactive BOM: ##

<p align="center"><a href="https://htmlpreview.github.io/?https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/MiSTer_A8SIO/bom/ibom.html"><img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/MiSTer_A8SIO/bom/bom.png" height="400"></a></p>

## Components ##

The following modules can be used to build an adapter without using SMD components:

- AMS 1117 3.3V stabiliser module
- 2 x 4ch level shifter module
- USB 3.0 Type A angled socket
- SIO socket

<p align="center">
  <img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/img/ldo.png" height="200">
  <img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/img/ls.png" height="200">
  <img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/img/usba.png" height="200">
</p>

For basic functionality, one level shifter (mounted on J5/J6) and an LDO power supply module (mounted on J7/J8) are sufficient.

The MOTOR CTRL circuit for controlling the tape recorder is optional.

New SIO sockets can be purchased here:
http://sikorsoft.waw.pl/hardware/gniazda-sio/

**To connect to MisterFPGA, you need a USB3.0 A data transfer cable (blue type A plugs on both sides).**

**The adapter can ONLY be connected to the User Port on the I/O daughter board.**

## Prototype ##

The prototype was tested with the following equipment:
- Atari 1050 Floppy disk drive
- FujiNet network adapter
- SDriveMAX drive emulator

<p align="center">
  <img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/img/prototype1.jpg" height="200">
  <img src="https://raw.githubusercontent.com/pmandes/MiSTer_A8SIO/main/img/prototype2.jpg" height="200">
</p>


## Changleog: ##

**1.2**
- fix: crossed lines from USB3 A-A cable

**1.1**
- prototype / not published
- 2 * 4ch level shifters modules instead of HW221
  
**1.0**
- initial project

## PCB ##
Please consider supporting my open projects and order PCBs here:
https://www.pcbway.com/project/shareproject/MiSTer_A8SIO_a2581e8f.html

