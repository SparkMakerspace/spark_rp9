# Spark RP9 (xiao-keypad)
[Github Hardware Link](https://github.com/sparkmakerspace/spark_rp9). [Software is here](https://github.com/SparkMakerspace/spark_rp9_sw)
The **RP9** was developed by some of the nerds at [Spark Makerpace](https://sparkmakerspace.org) for use in the Electronics & Technology Lab's soldering certification. Sign up for a class at [Spark Makerspace](https://sparkmakerspace.org]!

##Note:
This repository contains the hardware design files for the PCB designed in KiCAD. Pull requests are welcome and will be happily reviewed by our team.

##Software

Example firmware for this project is housed in the [spark_rp9_sw repository](https://github.com/SparkMakerspace/spark_rp9_sw).

Reach out to [electronics@sparkmakerspace.org](mailto:electronics@sparkmakerspace.org).

## Design Goals

**The problem:** most entry-level soldering kits are not useful following
**The solution:** make it a keyboard (macropad). the kids tell us it's what they're into these days.



Requirements:
* Ability to read values to demonstrate oscilloscope.
* Assemblable 2-3 hours of class time.

Assumptions:
* Decent temperature-adjustable soldering irons.
* An instructor skilled in through-hole and surface-mount soldering.
* students with little-to-no prior soldering experience.

Requirements:
* Seeedstudio Xiao RP2040 as MCU
  * Mounted on top of board so RGB LED is visible
  * Instructions printed on board.
  * Leave serial pin unused. Break to testpoint?
  * Pinout for Xiao fully labeled on board.
  * SMT 3.5mm jack for I2C SDA/SCL/GND (no power!!)
  * Diodes and MCU **not stacked**.
  * COL2ROW diode alignment.
  
v2 goals:
* wider Xiao pads for mounting castellations.
* hotswap
* rgb (reverse-mount)
* support non-mx switches
* SAO connector
* cat pics.

References:
The following documents are included in this repository for student reference but are property of their respective authors:
* [Basics of Digital Multimeters](/basics-of-digital-multimeters.pdf)
* [Adafruit's Guide to Excellent Soldering](/adafruit-guide-excellent-soldering.pdf)
