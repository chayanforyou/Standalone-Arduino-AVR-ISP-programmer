# GimmeSoul

[![Status](https://img.shields.io/badge/Status-Finished-green.svg)](https://github.com/TiagoPaulaSilva/GimmeSoul)
[![Donate](https://img.shields.io/badge/Donate-Buy%20Me%20a%20Coffee-yellow.svg)](https://www.buymeacoffee.com/TiagoPaulaSilva)

GimmeSoul is a standalone (no computer needed) bootloader programmer for ATmega328P. It can be used to facilitate programming of chips used by [Arduino UNO](https://store.arduino.cc/usa/arduino-uno-rev3) and [Senaino](https://github.com/TiagoPaulaSilva/Senaino), for example. 

This makes the process of flash the ICs so much faster than conventional way and eliminates the need for a computer.

## Mounted PCB
<img src="https://github.com/TiagoPaulaSilva/GimmeSoul/blob/master/Others/Mounted%20PCB.jpg" width="50%" height="50%">

## PCB Gerber Preview
<img src="https://github.com/TiagoPaulaSilva/GimmeSoul/blob/master/Others/GimmeSoul%20Gerber%20Preview.png" width="50%" height="50%">

## Schematic
<img src="https://github.com/TiagoPaulaSilva/GimmeSoul/blob/master/Others/GimmeSoul%20Schematic%20Preview.png" width="100%" height="100%">

## Bill of Materials
To mount the components on the board, follow the instructions: [Designator References](https://github.com/TiagoPaulaSilva/GimmeSoul/blob/master/Hardware/1.%20Mounting/Silk%20Screen.png)

| Qty | Parts | Description | Value | Package |
|--|--|--|--|--|
2|R2/R3|SMD Resistor|100R ±5%|R0805
1|R1|SMD Resistor|10k ±5%|R0805
4|C1/C2/C4/C6|SMD Capacitor|100 nF / 50V|C0805
2|C3/C5|SMD Capacitor|1 uF / 50V|C0805
2|C7/C8|SMD Capacitor|22 pF / 50V|C0805
1|D2|SMD Diode|1N4007|SOD123
1|U1|SMD Microcontroller|ATmega328P|TQFP-32
1|U2|SMD Voltage Regulator|LM1117MP-5.0|SOT223
2|S1/S2|PTH Tact Switch|DPST|6 x 6 mm
1|Q1|PTH Crystal|16 MHz|HC49/S
1|SG5|PTH Buzzer|5V Passive|F/QMBIII
1|LED1|PTH LED|Green|5 mm
1|LED2|PTH LED|Red|5 mm
2|JP1/JP4|PTH Pin Header|Male 180°|1X08
1|JP2|PTH Pin Header|Male 180°|1X10
1|JP3|PTH Pin Header|Male 180°|1X06
1|ZX1|PTH ZIF socket|28-pin|Slim Width

## How To
[SETUP Tutorial](https://github.com/TiagoPaulaSilva/GimmeSoul/wiki/SETUP)

## Video
[# GimmeSoul - Demo](https://vimeo.com/363052289?activityReferer=1)

### Contributing
0. Give this project a :star:
1. Create an issue and describe your idea.
2. [Fork it](https://github.com/TiagoPaulaSilva/GimmeSoul/fork).
3. Create your feature branch (`git checkout -b my-new-feature`).
4. Commit your changes (`git commit -a -m "Added feature title"`).
5. Publish the branch (`git push origin my-new-feature`).
6. Create a new pull request.
7. Done! :heavy_check_mark:

### License Information
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">GimmeSoul</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/TiagoPaulaSilva" property="cc:attributionName" rel="cc:attributionURL">Tiago Silva</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="[Standalone AVR Chip Programmer](https://learn.adafruit.com/standalone-avr-chip-programmer/)" rel="dct:source">[Standalone AVR Chip Programmer](https://learn.adafruit.com/standalone-avr-chip-programmer/)</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/tiagopsilvaa" rel="cc:morePermissions">tiagodepaulasilva@gmail.com</a>.
