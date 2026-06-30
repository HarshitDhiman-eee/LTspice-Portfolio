# Half Wave Rectifier

## Objective
To simulate a half-wave rectifier using LTspice and observe the conversion of AC voltage into pulsating DC.

## Components Used
- AC Voltage Source
- Diode (1N4007)
- Load Resistor

## Simulation Type
- Transient Analysis

## Files Included
- `Half-Wave-Rectifier.asc` – LTspice schematic
- `Circuit.png` – Circuit diagram
- `Output-Waveform.png` – Simulation output

## Observation
The diode conducts only during the positive half-cycle of the input signal, blocking the negative half-cycle. As a result, the output is a pulsating DC waveform.

## Learning Outcome
- Understanding diode operation
- Basics of AC-to-DC conversion
- Performing transient analysis in LTspice
