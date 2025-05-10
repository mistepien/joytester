![alt text](https://github.com/mistepien/joytester/blob/main/top.svg)
![alt text](https://github.com/mistepien/joytester/blob/main/bottom.svg)

# joytester
Joytester for testing of Atari-like+ joysticks

Joytester for testing Atari-like joysticks -- tests also Fire2 and Fire3 in C64 and Amiga/Atari mode.

Populate only one of U1 or U2, never both!

SW3 is redundand.

You can use the <a href="https://github.com/mistepien/joytester/tree/main/production">gerber file<a> to order the PCB.

Here you have <a href="https://github.com/mistepien/joytester/blob/main/joytester.pdf
">the schematic file<a> to order the PCB.


BOM:
| Qty	| Reference(s) | Description |
|-----|--------------|-------------|
|10 | D1, D2, D3, D4, D5, D6, D7, D8, D9, D10 | LEDs 3mm |  
|10 | R1, R2, R3, R4, R5, R6, R7, R8, R9, R10 | resisors for D1...D10 |
|3 | R11, R12, R13 | 10KΩ pull-up/pull-down resistors |
|1 | J1| DB9 Male Connector ( eg. <a href="https://www.tme.eu/pl/en/details/ld09p13a4gx00lf/d-sub-plugs-and-sockets/amphenol-communications-solutions/">LD09P13A4GX00LF Amphenol</a>) |
|1 | J2 | USB B socket |
|1 | J3 | USB C power-only socket (eg.  <a href="https://www.tme.eu/pl/en/details/usb4125-gf-a/usb-ieee1394-connectors/gct/">USB4125-GF-AGCT</a> ) |
| 2 | R14, R15 | 5K1Ω resistors for J3 USB C power-only socket |
|1 | J4 | USB B Mini socket |
|1 | J5 | USB B Micro socket |
|1 | U1 | DIP14 socket (width 7.62mm) + 4070IC or 4030IC XOR Gates|
|1 | U2 | DIP14 socket (width 7.62mm) + 74HC86 XOR Gates |
|2 | SW1, SW2 | SPDT switches or 3x1 2.54mm pinheaders |
|1 | SW3 | SPDT switch, terminal pitch: 4.7mm | 
