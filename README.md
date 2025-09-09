🚀 Team JANUS Avionics - Round 3 PCB Design
This repository contains the PCB design solution for the final round of the Team JANUS Avionics Subsystem inductions for 2025-2026. The project involves creating a PCB layout from a provided schematic using KiCad.


📋 Task Requirements
The goal was to design a functional PCB based on a given schematic. The board includes an STM32 MCU, a BMP280 sensor, a USB-to-UART bridge, and a Micro-USB port for power and data.


The design adheres to the following key constraints as specified in the problem statement:

Component Footprints: Footprints were chosen from the KiCad standard library. Modifications were not necessary for this design.


Trace Widths: Separate trace widths are used for power and signal lines to ensure stable power delivery.


Ground Plane: The bottom copper layer is dedicated to a solid ground plane for signal integrity and noise reduction.


Vias: Vias are used as needed to route signals between the top and bottom layers.


Manual Routing: All routing was performed manually; auto-routing was strictly prohibited.

📁 Repository Contents
NewFile.kicad_pro: The main KiCad project file.

NewFile.kicad_sch: The schematic file containing the complete circuit diagram.

NewFile.kicad_pcb: The final PCB layout file.

README.md: This file.
