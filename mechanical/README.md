# Passport Mechanical

This repository contains the full production assembly for Passport, an open source Bitcoin hardware wallet made by Foundation Devices.

![Passport](https://user-images.githubusercontent.com/62639971/179804265-acd42077-fb86-46bc-b6da-1763379d1fd9.png)

## Project Structure
Passport consists of the following components:
- STEP Files
- Bill of Materials

**STEP Files** contains a set of 3D models for Passport in STEP format.

**Bill of Materials** contains all custom and stock physical components used to assemble Passport.

### Folder Organization
This repo contains the following folders:
- Bill of Materials
- Mechanical Design Files
- passport-electronics – this is a submodule
- passport-firmware – this is a submodule

**Bill of Materials** contains all custom and stock physical components used to assemble Passport.

**Mechanical Design Files** contains CAD files (STL, STEP, SOLIDWORKS) and PDF drawings. 
Full STL and STEP assemblies exceed Github's size limit and can be found [here](https://drive.google.com/drive/u/0/folders/1Z9FJ9kxqDMWf-vwsLpfFheNOHl8vTlpA).

**passport-electronics** is a submodule linking to the repo containing Passport's circuit designs.

**passport-firmware** is a submodule linking to the repo containing Passport's firmware.

### Documenting Changes
This repository includes a CHANGES.txt file. We will document all design changes in this file. If you submit a pull request that makes changes to the circuit designs, please update CHANGES.txt with a brief description of your changes.


## Security Vulnerability Disclosure
Please report suspected security vulnerabilities in private to security@foundationdevices.com. Please do NOT create publicly viewable issues for suspected security vulnerabilities.

## Licensing
The hardware in this project, including all mechanical and electrical design files, is licensed under CERN-OHL-S v2 – a viral, copyleft, open source license. CERN-OHL-S v2 is similar in goals to GPLv3, but is specifically designed for hardware projects.

The software in this project, as detailed in the passport-firmware submodule, is licensed under numerous software licenses but must be treated as copyleft due to the inclusion of GPLv3 licensed code.

You are welcome to use these designs for any purpose, but you must comply with the terms of the licenses. This includes licensing derivative work as CERN-OHL-S v2 and GPLv3, preserving copyright notices, and more. Instructions are included in LICENSE_GUIDE.txt. Feel free to contact us with any questions about licensing.

Included in this repository in LICENSE.txt is the full text of CERN-OHL-S v2.

### License Notice
You may redistribute and modify this source and make products using it
under the terms of the CERN-OHL-S v2 (https://ohwr.org/cern_ohl_s_v2.txt).

This source is distributed WITHOUT ANY EXPRESS OR IMPLIED WARRANTY,
INCLUDING OF MERCHANTABILITY, SATISFACTORY QUALITY AND FITNESS FOR A
PARTICULAR PURPOSE. Please see the CERN-OHL-S v2 for applicable conditions.

Source location: foundationdevices.com/passport-assembly

As per CERN-OHL-S v2 section 4, should You produce hardware based on this
source, You must where practicable and applicable maintain the Source Location
visible (1) on the packaging of the hardware, (2) on the circuit board(s) via
silkscreen or copper, (3) on the plastic and metal components, (4) in any documentation, 
and (5) on other products you make using this source.
