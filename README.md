#8x8 SRAM Array Design with Row Decoder
#Overview
This project presents the design of an 8x8-bit Static Random-Access Memory (SRAM) array with an integrated row decoder, optimized for low-power applications. Using a 6T SRAM cell configuration, the design aims to minimize power consumption, latency, and read/write times. The project provides details on the peripheral circuits essential for SRAM functionality, including the pre-charge, write driver, sense amplifier, and row decoder circuits, all developed on the Cadence Virtuoso platform.

#Key Features
6T SRAM Cell: Achieves low power and high stability using CMOS technology.
Row Decoder: 3:8 decoder for efficient row selection in the memory array.
Low Power Consumption: Designed to operate at 1.8V with minimized power leakage.
Fast Read/Write Operations: Optimized pre-charge, write driver, and sense amplifier circuits.

#Technical Specifications
Technology Node: 180nm CMOS
Supply Voltage: 1.8V
Power Consumption: 3.14mW
Read Delay: 196ps
Write Delay: 830.5ps

#Project Contents
SRAM Architecture: Schematic and layout designs of the SRAM cells and peripheral circuits.
Simulation Results: Demonstrates read and write performance with a focus on efficiency and speed.
Documentation: Full design specifications and analysis.

#Getting Started
Clone this repository.
Open the schematics in Cadence Virtuoso to view the design.
Run simulations as outlined in the documentation for performance evaluation.
