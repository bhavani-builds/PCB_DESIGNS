# Square Wave Inverter Circuit using Complementary Transistors

## Overview

This project demonstrates the design and simulation of a simple Square Wave Inverter Circuit using complementary bipolar junction transistors (BJTs) in Proteus 8 Professional.

The circuit converts DC power into a square-wave AC-like output by alternately switching an NPN and PNP transistor using a pulse input signal.

## Project Objectives

- Understand the basic operation of inverter circuits.
- Study transistor switching behavior.
- Simulate DC-to-AC conversion using Proteus.
- Design and visualize the circuit and PCB layout.

## Circuit Components

| Component | Description |
|------------|------------|
| Q1 | 2N2222 (NPN Transistor) |
| Q2 | 2N2907 (PNP Transistor) |
| R1 | 10 Ω Resistor |
| R2 | 10 Ω Resistor |
| BAT1 | 12V DC Supply |
| BAT2 | 12V DC Supply |
| Pulse Generator | Input Switching Signal |
| Ammeter | Current Measurement |

## Working Principle

1. A pulse generator provides a square-wave control signal.
2. The signal drives the complementary transistor pair.
3. During the positive pulse:
   - The NPN transistor conducts.
   - Current flows through the load in one direction.
4. During the negative pulse:
   - The PNP transistor conducts.
   - Current flows in the opposite direction.
5. This alternating conduction creates a square-wave output.

## Software Used

- Proteus 8 Professional

## Project Files

- `SQUARE WAVEINVERTER CIRCUIT.pdsprj`
- `SQUARE WAVEINVERTER CIRCUIT_PCB_LAYOUT.pdsprj`
- `SQUARE WAVEINVERTER CIRCUIT_PCB_3D.pdsprj`

## Features

- Simple inverter implementation
- Proteus simulation support
- PCB layout design
- 3D PCB visualization
- Educational and beginner-friendly project

## Applications

- Power Electronics Learning
- Inverter Fundamentals
- Digital Switching Circuits
- Electronics Laboratory Experiments

## Future Enhancements

- MOSFET-based inverter design
- Transformer-coupled output
- PWM control implementation
- Pure sine-wave inverter development
- Higher power handling capability

## How to Run

1. Open the project in Proteus 8 Professional.
2. Load the `.pdsprj` file.
3. Start the simulation.
4. Observe transistor switching and current flow.
5. Analyze the generated square-wave output.
