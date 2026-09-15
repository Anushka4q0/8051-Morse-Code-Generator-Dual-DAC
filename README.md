# 8051 Morse Code Generator with Dual DAC Interface

## Project Overview
Designed and implemented a Morse Code Generator on an 8051 Microcontroller using Embedded Assembly Language. The system converts text characters into Morse DOT/DASH pulse sequences and generates corresponding digital output signals through Port-1. The output waveform was verified using a Digital Storage Oscilloscope and Logic Analyzer.

## Features
- Converts characters into standard Morse Code format
- Generates DOT and DASH pulse sequences
- Digital output through 8051 Port-1
- Dual DAC interface for waveform generation
- Continuous Morse Code transmission
- Hardware validation using DSO and Logic Analyzer

## Hardware Used
- 8051 Microcontroller Development Board
- Dual DAC Module
- Digital Storage Oscilloscope (DSO)
- Logic Analyzer
- Power Supply

## Software Used
- Keil µVision
- Embedded Assembly Language

## Project Files
- `Morse_Code_Generator.asm` – Source Code
- `report_morsecode_project.pdf` – Project Report
- `Hardware setup image.jpeg` – Hardware Setup
- `Oscilloscope output image.jpeg` – DSO Output
- `Logic analyzer output image.jpeg` – Logic Analyzer Output
- `MorseCodes.jpeg` – Morse Code Reference Chart

## Working Principle
1. Input text is mapped to Morse Code symbols.
2. DOT and DASH pulses are generated using timing delays.
3. Digital pulses are sent through Port-1 of the 8051 microcontroller.
4. The Dual DAC module converts digital signals for waveform observation.
5. Output signals are verified using a Digital Storage Oscilloscope and Logic Analyzer.

## Results
- Successfully generated Morse Code pulse sequences.
- Verified waveform timing using a Digital Storage Oscilloscope.
- Confirmed pulse patterns using a Logic Analyzer.
- Demonstrated real-time hardware implementation on an 8051 development board.

## Author
Lakshmi Anushka Vemula
B.Tech Electronics and Communication Engineering
