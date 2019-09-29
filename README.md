# GimmeSoul

[![Build](https://img.shields.io/badge/Build-Stable-green.svg)](https://github.com/TiagoPaulaSilva/GimmeSoul)
[![Donate](https://img.shields.io/badge/Donate-Buy%20Me%20a%20Coffee-yellow.svg)](https://www.buymeacoffee.com/TiagoPaulaSilva)

GimmeSoul is a standalone (no computer needed) bootloader programmer for ATmega328P. It can be used to facilitate programming of chips used by [Arduino UNO](https://store.arduino.cc/usa/arduino-uno-rev3) and [Senaino](https://github.com/TiagoPaulaSilva/Senaino), for example. 

This makes the process of flash the ICs so much faster than conventional way and eliminates the need for a computer.

## Mounted PCB
![Mounted PCB](https://lh3.googleusercontent.com/wEgzzrwWFOXGO3YkiD_pZtRbCWQpugLJpkmKNPH7OJ_K2hq77eh_ZTPw8kOnITuWVGsAojfYdgyA0w)

## PCB Gerber Preview
![enter image description here](https://lh3.googleusercontent.com/nIToOH6tOP8V6YTB77NmxzNem5c2N3wR6zNyF-sfcsGTXmM2lakn-CSjGWn2qzALiI3_n1oUDvh1pQ)

## Schematic
![enter image description here](https://lh3.googleusercontent.com/AHHnmKVK-I-i_wTlw6jTIGntzJRpIFq3xoOx97R3P0ko0mQc31HL2QWThcjjNv_U7E4xbQ02cF6MKQ=s2000)

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
1|JP1/JP4|PTH Pin Header|Male 180°|1X08
1|JP2|PTH Pin Header|Male 180°|1X10
1|JP3|PTH Pin Header|Male 180°|1X06
1|ZX1|PTH ZIF socket|28-pin|Slim Width

## Video
[# GimmeSoul - How to](https://vimeo.com/363052289?activityReferer=1)

### License Information
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br /><span xmlns:dct="http://purl.org/dc/terms/" property="dct:title">Senaino</span> by <a xmlns:cc="http://creativecommons.org/ns#" href="https://github.com/TiagoPaulaSilva" property="cc:attributionName" rel="cc:attributionURL">Tiago Silva</a> is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.<br />Based on a work at <a xmlns:dct="http://purl.org/dc/terms/" href="[https://learn.adafruit.com/standalone-avr-chip-programmer/](https://learn.adafruit.com/standalone-avr-chip-programmer/)" rel="dct:source">[https://learn.adafruit.com/standalone-avr-chip-programmer/](https://learn.adafruit.com/standalone-avr-chip-programmer/)</a>.<br />Permissions beyond the scope of this license may be available at <a xmlns:cc="http://creativecommons.org/ns#" href="https://twitter.com/tiagopsilvaa" rel="cc:morePermissions">https://twitter.com/tiagopsilvaa</a>.
