---
number: 8
title: 'Assignment 8 - Electronics Production'
course: 'df'
pubDate: 'Feb 16 2024'
---

## Assignment 8

This weeks assignment was to produce a predesigned circuit board using one of the CNC machines in the FabLab. The circuit board should be produced using "isolation routing". As base stock we used FR-4 copper clad board.

The circuit board was designed using [KiCad](https://www.kicad.org/). The Board we produced was the FabAcademy [ft230x-updi Programmer](https://fabacademy.org/2022/labs/kamplintfort/resorces/ft230x-updi.html). The board is intended to be used to program the ATtiny microcontroller used in the final project.

The first step in this process was to export the Gerber files from KiCad.
![KiCad Design](/df/df-8a.jpeg)
The Gerber files are a set of files that describe the layout of the circuit board. The files are then used by the CNC machine to produce the board.

The next step was to use the CNC machine to produce the board. The machine was setup to use a universal 0.2mm cutter and the isolation routing process was used to produce the board.

![CNC Settings](/df/df-8b.jpeg)

The isolation routing process is a process where the copper is removed from the board using a cutter in such a way that the individual traces are isolated. The cutter is set to a depth that removes the copper but does not cut into the board itself.

The next step was to solder the components to the board. The components used mostly consisted of SMD components. The resistors, capacitors and LED's used were all in the 1206 package format. The most important component was the FT230X chip.

The components were soldered to the board using a soldering iron. After finishing soldering the components, the board was tested using a multimeter to check for shorts and continuity.

![Finished board](/df/df-8c.jpeg)

The board was then connected to a computer and the FT230X chip was tested using the Arduino IDE. The chip was recognized by the computer and the board was working as intended.

The produced board could now be used to programm a variety of microcontrollers using the UPDI protocol.
