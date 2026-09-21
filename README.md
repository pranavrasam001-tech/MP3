# MP3 PCB

## About the Project

This is a custom PCB project designed in KiCad. The board is based on the STM32WB55 microcontroller and includes USB Type-C, 3.3V power regulation, RF connections, programming support, LEDs, a reset switch, and required passive components.

The purpose of this project was to understand how to create a complete PCB design using KiCad, from schematic design to PCB routing and Gerber file generation.

---

## Features

- STM32WB55 microcontroller
- USB Type-C connector
- 3.3V power supply section
- USB ESD protection
- SWD programming interface
- Reset push button
- LED indicator
- Crystal oscillator circuit
- RF matching components
- Coaxial RF connector
- PCB mounting holes and fiducials

---

## Tools and Components Used

- KiCad
- STM32WB55CEUx microcontroller
- USB Type-C connector
- MIC5365-3.3V voltage regulator
- USBLC6-2SC6 USB protection IC
- Crystal oscillators
- Capacitors
- Resistors
- Inductors
- Transformer / RF matching circuit
- LED
- Reset switch
- SWD Tag-Connect programming connector

---

## What I Did

- Created the schematic in KiCad.
- Added the STM32WB55, USB Type-C, power supply, RF section, programming connector, LED, and other components.
- Connected power, ground, USB, reset, programming, and RF signals.
- Added capacitors, resistors, inductors, and crystal circuits where required.
- Assigned footprints to all components.
- Converted the schematic into a PCB layout.
- Arranged the components carefully for proper routing.
- Routed the PCB tracks and checked the connections.
- Generated Gerber files for PCB manufacturing.

---

## Project Files

```text
MP3
│
├── MP3.kicad_sch
├── MP3.kicad_pcb
├── MP3.kicad_pro
├── MP3.pdf
├── MP3-F_Cu.gbr
├── MP3-B_Cu.gbr
├── MP3-F_Mask.gbr
├── MP3-B_Mask.gbr
├── MP3-F_Silkscreen.gbr
├── MP3-B_Silkscreen.gbr
├── MP3-Edge_Cuts.gbr
└── MP3-job.gbrjob
