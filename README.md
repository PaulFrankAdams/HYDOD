# HYDODrive Pi v1 – Raspberry Pi-Based Hydrogen-On-Demand Driver Board

HYDODrive Pi v1 is an open-source driver board designed to generate efficient resonant signals for a drycell electrolysis stack using a Raspberry Pi. This board focuses on signal generation, timing, and control — forming the heart of a modular hydrogen-on-demand system for research, education, and clean energy experimentation.

## ⚡ Key Features

- Raspberry Pi (GPIO) compatibility
- Single-phase driver stage with support for 3-phase expansion
- Drives a Cathode–Neutral–Anode (CNA) drycell configuration
- Resonant LC tank circuit operation (based on original patents)
- Screw terminal outputs for cell array and power
- Modular design: expandable per drycell group
- Supports signal-level MOSFET switching for PWM/resonance
- Plug-and-play with optional HAT integration

## 📐 Intended Use

This board is designed for:

- Driving resonant drycell electrolysers (CNA stack)
- Testing waveform response (square wave, PWM, sine mod)
- Experimenting with hydrogen production efficiency
- Demonstrating pulse-resonance electrolysis for educational purposes

## 🧠 Based On

Inspired by:

- US Patent US20050246059A1 (Stanley Meyer)
- Audio-frequency and PLL-controlled experiments (e.g. Puharich, Lawton)
- Practical hydrogen-on-demand implementations (Boyce, etc.)

## 📂 Included

- KiCad schematic and PCB layout files (`.kicad_sch`, `.kicad_pcb`)
- Pre-routed board files and netlists
- Gerber files for JLCPCB fabrication
- Simulation template for 1-stage in LTSpice
- Basic GPIO code examples (Python, Arduino)
- Project BOM with part numbers
- Printable layout and connection diagrams

## 🧪 Simulation Support

The single-stage simulation (fixed 68 µF, 1.7 mH) models the resonant characteristics of one driver cell, useful for tuning and waveform testing.

## 🤝 Contributions

This is an active open hardware project. You are encouraged to fork, clone, and contribute improvements.

## 🔓 License

This repository is released under the CERN-OHL-W license (or your specified license), with **full open-source disclosure** in `DISCLOSURE.md`. It is intended to benefit humanity and must remain freely accessible.

## 📍 Repository

[https://github.com/PaulFrankAdams/HYDOD](https://github.com/PaulFrankAdams/HYDOD)
