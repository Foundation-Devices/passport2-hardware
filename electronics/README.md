# Passport Electronics

This repository contains the production circuit designs for Passport 2, an open source Bitcoin hardware wallet made by Foundation Devices.

<img width="1165" alt="main board block diagram" src="https://user-images.githubusercontent.com/62639971/185300045-8900fd17-6c01-448f-8174-edb56905cc2e.png">

Above is a basic block diagram for Passport's circuit Board.

## Project Structure

### Folder Organization
The circuit board files are in several sub-folders under the `PCB` folder.

- Assembly
- Documentation
- Fabrication
- Source Files

**Assembly** contains data for assembling components onto a bare circuit board. It includes drawings, bill of materials, and coordinates for pick-and-place and test points.

**Documentation** contains simple PDF overview documents of the schematics and board design.

**Fabrication** contains data for the circuit board fabricator. It includes drawings, Gerber files, and coordinates for drilling and test points.

**Source Files** contains circuit board designs. It includes circuit schematics and Altium design files.

Circuit designs can only be opened with Altium. We are exploring exporting these designs in multiple file formats, including formats that can be used with open source PCB design software.

If you are interested in using KiCAD, you may try this Altium to KiCAD converter: https://github.com/thesourcerer8/altium2kicad/.

### Documenting Changes
This repository includes a CHANGES.txt file. We will document all design changes in this file. If you submit a pull request that makes changes to the circuit designs, please update CHANGES.txt with a brief description of your changes.

## Open Source Components
Passport's Main Board incorporates an open-source schematic from the [Betrusted project](https://github.com/betrusted-io/betrusted-hardware-xt). Specifically, we implemented Betrusted's [Avalance Noise Source](https://betrusted.io/avalanche-noise) design into Passport to serve as a true random number generator that does not rely on black-box silicon. Thank you to the Betrusted team for open sourcing their excellent work.

## Security Vulnerability Disclosure
Please report suspected security vulnerabilities in private to security@foundationdevices.com. Please do NOT create publicly viewable issues for suspected security vulnerabilities.

## Licensing
This project, and every file included in this repository, is licensed under CERN-OHL-S v2 ??? a viral, copyleft, open source license. CERN-OHL-S v2 is similar in goals to GPLv3, but is specifically designed for hardware projects.

You are welcome to use these designs for any purpose, but you must comply with the terms of the license. This includes licensing derivative work as CERN-OHL-S v2, preserving copyright notices, and more. Instructions are included in LICENSE_GUIDE.txt. Feel free to contact us with any questions about licensing.

Included in this repository in LICENSE.txt is the full text of CERN-OHL-S v2.

### License Notice
You may redistribute and modify this source and make products using it
under the terms of the CERN-OHL-S v2 (https://ohwr.org/cern_ohl_s_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY,
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source location: foundationdevices.com/passport-electronics

As per CERN-OHL-S v2 section 4, should You produce hardware based on this
source, You must where practicable and applicable maintain the Source Location
visible (1) on the packaging of the hardware, (2) on the circuit board(s) via
silkscreen or copper, (3) in any documentation, and (4) on other products you
make using this source.