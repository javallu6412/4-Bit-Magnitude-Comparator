<h1> 4-Bit Magnitude Comparator</h1>

<p>
  <img src="https://img.shields.io/badge/Cadence-Virtuoso-blue">
  <img src="https://img.shields.io/badge/VLSI-Design-red">
  <img src="https://img.shields.io/badge/CMOS-PMOS%2FNMOS-green">
  <img src="https://img.shields.io/badge/Digital-Logic-yellow">
  <img src="https://img.shields.io/badge/4--Bit-Comparator-blue">
  <img src="https://img.shields.io/badge/Circuit-Simulation-red">
  <img src="https://img.shields.io/badge/License-MIT-green">
</p>

> ### VLSI System Design — VIT Chennai, April 2024  
> **Joseph Alex Valluvassery**

## Overview

This project compares two 4-bit binary numbers and generates three outputs:

- A > B
- A < B
- A = B

The design was implemented using PMOS and NMOS transistor-level logic and simulated using Cadence Virtuoso.

---

## Features

- CMOS-based transistor-level implementation
- Logic gate level comparator design
- Cadence Virtuoso schematic design
- Simulation and waveform verification
- Modular gate implementation

---

## Software Used

- Cadence Virtuoso

---

## Project Components

### Circuit Diagram

![Circuit](assets/circuit.png)

### Truth Table

![Truth Table](assets/truth_table.png)

### PMOS and NMOS Implementation

![Cadence Design](assets/cadence_sim.png)

### Simulation Output

![Output](assets/output.png)

---

## Logic Gates Implemented

- Inverter
  ![Output](assets/inveter.png)
- 2 Input AND
  ![Output](assets/2_AND.png)
- 2 Input OR
  ![Output](assets/2_OR.png)
- 3 Input AND
  ![Output](assets/3_AND.png)
- 4 Input AND
  ![Output](assets/4_AND.png)
- 4 Input OR
  ![Output](assets/4_OR.png)

---

## Working Principle

The comparator checks bits from MSB to LSB.

- If A > B → Greater output HIGH
- If A < B → Less output HIGH
- If A = B → Equal output HIGH

---

## Applications

- Arithmetic Logic Units (ALUs)
- Digital Signal Processing
- Microprocessors
- Embedded Systems

---

## Future Improvements

- Extend to 8-bit and 16-bit comparators
- Optimize power and area
- Improve propagation delay
- Implement layout-level optimization

---

## Authors

- Joseph Alex Valluvassery
