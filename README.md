# ampedia-lite
A lite-version of Ampedia. Guitar Amplifier Simulator Project

> This project provides a lightweight, open-source implementation of a core guitar amplifier simulation algorithm. It is a simplified, oversampling-free version of a larger private AU plugin project, designed to showcase tone shaping logic and analog-style behavior without proprietary components.

## Overview
Ampedia-Lite is a C++-based amplifier simulation engine focusing on the fundamental signal path: gain staging, soft clipping, EQ/tone stack, and output shaping. While intentionally minimalist, it retains musical responsiveness and can be used as a reference or starting point for DIY plugin development.

## Features
- Simple core architecture (preamp → poweramp → (speaker IR plugin/Filter))
- Real tube amplication curve (vout vs. vin) support
- Written all in C++

## Repository Structure
```
TBD
```

## Sound Demo
A demo clip is available on YouTube demonstrating the sound of this core simulator:

Marshall 1959 SLP: https://youtu.be/kWy7xnjtBL4?si=jrKbJEHTM1jpUbPn
Marshall JMP-800 2203: https://youtu.be/YN9nAcvoObw?si=cwO0VjDRZitwc7aS

## Notes
This version excludes oversampling, anti-aliasing filters, or detailed cabinet/mic simulation. It is intended for educational and prototyping use.

## Target Audience
- Audio DSP learners
- Guitar tone hackers
- DIY plugin developers
- Engineers interested in analog modeling

---
This project is licensed under the **GNU General Public License v3.0 (GPLv3)**.
See the LICENSE file for details.
