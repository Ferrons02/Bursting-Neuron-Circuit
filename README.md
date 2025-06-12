# Bursting Neuron Circuit — Neuromorphic Engineering 2

This project was developed as part of the course *Neuromorphic Engineering 2*.  
The goal was to design, simulate, and layout a biologically plausible analog circuit capable of reproducing the bursting behavior observed in cortical neurons.

The initial schematic was provided to all students. However, each of us was responsible for the full custom design flow: sizing the transistors, tuning the circuit parameters to achieve bursting behavior, and performing the physical layout in a 180 nm CMOS technology.

---

## Overview

Neuromorphic engineering aims to replicate the computational principles of biological neural systems using energy-efficient hardware.  
In this project, I implemented a modular neuron circuit featuring four distinct feedback mechanisms integrated via a soma block.  
Each feedback path is independently tunable, enabling fine control over:

- Spike frequency  
- Interburst interval  
- Burst duration

This structure allows the emulation of various biologically realistic firing patterns while minimizing power and silicon area.

---

## Features

- Biologically plausible bursting behavior  
- Modular and tunable architecture  
- Compact full custom layout in 180 nm CMOS  
- Validated via extensive pre- and post-layout simulations

---

## Tools Used

- Cadence Virtuoso (schematic, simulation, layout)  
- 180 nm CMOS PDK

---

## Author

Developed by **Marco Ferroni**  
As part of the ETH Zurich course *Neuromorphic Engineering 2*
