# Development board for a replacement of the gate-array of the Thomson MO5 computer

> [WARNING] Please read carefully this note before using this project. It contains important facts.

Content

1. What is **Development board for a replacement of the gate-array of the Thomson MO5 computer**, and when to use it ?
2. What should you know before using **Development board for a replacement of the gate-array of the Thomson MO5 computer** ?
3. How to use **Development board for a replacement of the gate-array of the Thomson MO5 computer** ?
4. Known issues
5. Miscellanous

## 1. What is **Development board for a replacement of the gate-array of the Thomson MO5 computer**, and when to use it ?

**Development board for a replacement of the gate-array of the Thomson MO5 computer** is a hardware project to help programming and testing a replacement of the gate array of the Thomson MO5 computer, a French computer that appeared in 1984.


### Licence

**Development board for a replacement of the gate-array of the Thomson MO5 computer** is published under the Creative Commons CC0 license. You can find a copy of the licence there : https://creativecommons.org/publicdomain/zero/1.0/legalcode

You can copy, modify, distribute and perform the work, even for commercial purposes, all without asking permission.

**Development board for a replacement of the gate-array of the Thomson MO5 computer** is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.

### Release notes

#### Version 1.0.0

Initial release, all should be well.

## 2. What should you know before using **Development board for a replacement of the gate-array of the Thomson MO5 computer** ?

**Development board for a replacement of the gate-array of the Thomson MO5 computer** is made using Kicad.

The board accept : 

* one of the FTDI 232H breakout board available, either the version with USB-A port, or the [Adafruit version with USB-C port](https://learn.adafruit.com/adafruit-ft232h-breakout/wiring).

* A CC-CC voltage converter (boost), to convert 5V to 12V (or higher). Required only if one use CPLD with locked JTAG functionnality that is unlocked with a voltage specified by the datasheet (e.g. 12V for ATF1508)

The board has 3 footprints : 

* One footprint specific to the Motorola gate array (like a staggered PLCC 68 footprint)

* One footprint for the EFCIS gate array and later versions (a regular PLCC 68 socket).

> Do not use **Development board for a replacement of the gate-array of the Thomson MO5 computer** if this project is not suitable for your project.

## 3. How to use **Development board for a replacement of the gate-array of the Thomson MO5 computer** ?

### From sources

To get the latest available work, one must clone the git repository, build and install the package.

	git clone --recurse-submodules https://github.com/sporniket/thomson-mo5--gate-array-development-board.git

Then, open the project with Kicad.

## 4. Known issues
See the [project issues](https://github.com/sporniket/thomson-mo5--gate-array-development-board/issues) page.

## 5. Miscellanous

### Report issues
Use the [project issues](https://github.com/sporniket/thomson-mo5--gate-array-development-board/issues) page.
