# 8-bit Manchester Carry Chain (MCC) Adder

## Overview
This project involves the design and implementation of an 8-bit Manchester Carry Chain (MCC) adder for optimum performance. The design is implemented using Cadence Virtuoso with the GPDK 180 nm technology library. The MCC adder achieves high-speed addition with modular design.

This repository contains the layout and extracted views of the MCC Adder design.

## 1-Bit MCC Layout
The following image shows the layout view of the 1-bit MCC.

![1-Bit MCC Layout](MCC%201-Bit%20Layout.png)

## 8-Bit MCC Extracted View
The following image shows the extracted view of the complete 8-bit MCC.

![8-Bit MCC Extracted View](MCC%208-Bit%20Extracted%20View.png)

## Features
- Modular design for scalability.
- Simulation at multiple frequencies to determine performance.
- Reports on area, power consumption, and area-delay product.

## Project Contents
- **Schematic and Layout Files**: Includes MCC 1-bit and MCC 8-bit schematic and layout designs.
- **Testbench**: MCC8 testbench for functional verification.
- **Simulation Results**: Waveform outputs at different frequencies (100 MHz, 200 MHz, etc.).
- **Reports**: Area, power consumption, and area-delay product analysis.

## Results
- **Maximum Input Frequency**: 200 MHz.
- **Area**: 12,268.61 μm².
- **Power Consumption**: 524.6 μW.
- 
## Usage
1. Open Cadence Virtuoso and load the provided schematic and layout files.
2. Run simulations using the MCC8 testbench to verify functionality.
3. View waveforms to analyze performance at different frequencies.
