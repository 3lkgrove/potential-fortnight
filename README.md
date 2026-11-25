# Compact CoreXY Multi-Tool 3D Printer

![Status](https://img.shields.io/badge/Status-In%20Design%20%2F%20Prototyping-orange?style=for-the-badge)
![Kinematics](https://img.shields.io/badge/Kinematics-CoreXY%20%2B%20Triple--Z-blue?style=for-the-badge)
![License](https://img.shields.io/badge/License-GPLv3-brightgreen?style=for-the-badge)

> **Note:** Official project name is currently TBD while the mechanical and CAD architecture is finalized.

---

## Overview

A scratch-built, Voron-inspired small-form-factor 3D printer engineered around a rigid 2020 aluminum extrusion frame, a Trident-style triple-Z moving bed, and multi-head tool changer capability. Designed to keep the main print chamber compact and thermally isolated, all high-voltage AC distribution, power supplies, and mainboard electronics are housed in an external, DIN-rail-equipped **side pack** bolted directly to the chassis flank.

---

## Core Architecture & Known Specifications

| Subsystem | Specification / Design Choice | Notes |
| :--- | :--- | :--- |
| **Build Volume** | `< 235 mm × 235 mm × 235 mm` | Compact footprint optimized for rapid chamber heat-up and high acceleration |
| **Frame** | 2020 Aluminum Extrusions | Rigid cube chassis inspired by Voron 2.4 / Trident architecture |
| **XY Kinematics** | CoreXY | High-speed motion system engineered to handle tool-changer inertia |
| **Z Kinematics** | Triple-Z Moving Bed | Voron Trident-style 3-point bed leveling with open top deck clearance |
| **Toolhead System** | Multi-Head Tool Changer | Automated multi-tool docking and umbilical/Bowden routing |
| **Electronics Bay** | External Side Pack | Asymmetrical lateral pod isolating PSU and logic from chamber heat |
| **Internal Mounting** | Industrial DIN Rails | Modular mounting for power supplies, relays, and terminal blocks |
| **Enclosure** | Polycarbonate Panels | High-temp dimensional stability for enclosed engineering filaments |

---

## Key Design Highlights

* **Thermally Isolated Electronics Bay:** Moving the power supply, DIN-rail power distribution, and BTT Manta board into an external side pack keeps sensitive electronics cool while letting the main polycarbonate chamber run at elevated temperatures without extra bottom-skirt height.
* **Industrial DIN-Rail Layout:** Inside the side pack, DIN rails organize AC/DC power distribution and control hardware cleanly for straightforward troubleshooting and future expansion.
* **Compact Multi-Tool Capability:** Combines a sub-235mm³ Trident-style moving bed with a multi-head tool changer to deliver multi-material printing without the footprint of a full-scale 350mm machine.
* **Integrated Host & MCU:** Utilizing a BigTreeTech Manta board with an onboard CB1 compute module minimizes wiring runs inside the side pack and simplifies stepper driver cooling.

---

## Repository Structure *(Planned)*

```text
├── CAD/                # Onshape exports, STEP assemblies, and reference models
├── STLs/               # Printable structural brackets, side-pack shrouds, and tool docks
├── Docs/               # Wiring diagrams, DIN-rail layout guides, and BOM
├── LICENSE             # GNU General Public License v3.0
└── README.md           # Project overview and current build specifications

```

---

## Author & Contact

- **Author:** Anthony Sleck ([@3lkgrove](https://github.com/3lkgrove))
- **Project Status:** Active Development (November 2026)

---

## Licensing

This project is licensed under the terms of the **GNU General Public License v3.0** (GPL-3.0). The full text of the license can be found in the [LICENSE](LICENSE) file in the root directory of this repository.

Copyright (c) 2026 [@3lkgrove](https://www.github.com/3lkgrove)
