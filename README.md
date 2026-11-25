# 🚀 Compact CoreXY Multi-Tool 3D Printer

## 🔧 Voron-Inspired Tool-Changing CoreXY Platform

> 🔩 Built for high-speed printing, modular experimentation, and entirely too many future upgrades.

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active%20Development-10B981?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-GPL--3.0-2563EB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Motion-CoreXY-DC2626?style=for-the-badge">
  <img src="https://img.shields.io/badge/Z%20System-Triple--Z-059669?style=for-the-badge">
  <img src="https://img.shields.io/badge/Toolheads-Multi--Tool-7C3AED?style=for-the-badge">
</p>

A scratch-built compact CoreXY 3D printer inspired by Voron architecture, featuring a **sub-200 mm build volume**, **Trident-style Triple-Z moving bed**, **automated multi-tool capability**, and an **industrial DIN-rail Side Pack** for thermally isolated electronics and power distribution.

---

# ⚠️ Project Status

```diff
ACTIVE DEVELOPMENT
```

**Official project name is currently TBD.**

Mechanical architecture, enclosure design, electronics integration, and tool-changing systems are actively being developed and refined.

---

# ✨ Key Features

## 🔄 Multi-Tool Printing Platform

- Automated multi-tool docking system
- Designed for future multi-material and specialty-tool support
- Optimized for efficient low-footprint operation
- Modular architecture for future expansion

## 🏭 External Side Pack Electronics Bay

- Dedicated enclosure for power distribution and control hardware
- Keeps sensitive electronics isolated from elevated chamber temperatures
- Improves accessibility and serviceability
- Enables cleaner cable management and maintenance

## 🔌 Industrial DIN-Rail Infrastructure

- DIN-rail-mounted power supplies
- Modular terminal block distribution
- Organized AC/DC wiring paths
- Simplified maintenance and troubleshooting

## ⚡ High-Speed CoreXY Motion System

- Lightweight CoreXY kinematics
- Designed around tool-changing mass considerations
- Focused on acceleration, rigidity, and reliability
- Optimized for future performance upgrades

## 🔥 Fully Enclosed Printing Environment

- Polycarbonate enclosure panels
- Improved thermal stability
- Engineering filament capable
- Reduced environmental influence on print quality

## 📐 Trident-Style Triple-Z System

- Three independently driven Z motors
- Automatic gantry leveling capability
- Excellent bed support and alignment
- Open upper deck for easy maintenance and tool access

---

# 🏗️ Core Architecture

| Subsystem | Specification | Notes |
|:---|:---|:---|
| **Build Volume** | < 200 × 200 × 200 mm | Compact chamber design |
| **Frame** | 2020 Aluminum Extrusions | Voron-inspired rigid cube chassis |
| **XY Kinematics** | CoreXY | High-speed motion platform |
| **Z Kinematics** | Triple-Z Moving Bed | Trident-style leveling system |
| **Tool System** | Multi-Head Tool Changer | Automated tool docking |
| **Electronics Bay** | External Side Pack | Thermal isolation architecture |
| **Mounting Method** | Industrial DIN Rails | Modular power distribution |
| **Enclosure** | Polycarbonate Panels | Elevated-temperature capability |
| **Firmware** | Klipper (Planned) | High-performance motion control |

---

# 🌟 Design Highlights

## 🧊 Thermally Isolated Electronics

Unlike many enclosed printers where electronics occupy the same space as the heated chamber, all major power and control hardware are relocated into a dedicated **Side Pack** assembly.

### Benefits

- Reduced thermal stress on electronics
- Easier servicing and upgrades
- Higher potential chamber temperatures
- Cleaner internal printer layout
- No oversized electronics compartment beneath the machine

---

## 🏭 Industrial Electrical Design

The Side Pack incorporates industrial control-panel concepts commonly used in automation systems.

### Features

- DIN-rail component mounting
- Structured cable routing
- Modular terminal block distribution
- Expandable power architecture
- Simplified diagnostics and troubleshooting

---

## 🎨 Compact Multi-Material Capability

One of the primary goals of the project is combining:

- 🔄 Tool-changing functionality
- 📏 Compact footprint
- 🔥 High chamber temperatures
- 📐 Trident-style mechanics

without requiring the physical size and complexity typically associated with large-format multi-tool machines.

---

# 📂 Repository Structure

```text
.
├── CAD/
│   ├── STEP Files
│   └── Reference Models
│
├── Images/
│
├── Manuals/
│   ├── Wiring Diagrams
│   ├── DIN Rail Layouts
│   ├── Assembly Documentation
│   └── BOM
│
├── STLs/
│   └── Printable Components
│
├── Usermods/
│
├── LICENSE
└── README.md
```

---

# 🛠️ Planned Components

| Component | Status |
|:---|:---|
| CoreXY Motion System | 🚧 In Progress |
| Triple-Z Platform | 🚧 In Progress |
| Side Pack Architecture | 🚧 In Progress |
| Tool Changer System | 🚧 In Progress |
| Wiring Documentation | 🚧 In Progress |
| Complete CAD Package | 🚧 In Progress |
| Initial Prototype Build | 🚧 In Progress |

---

# 📸 Project Gallery

## 🖥️ CAD Renders

Coming Soon™

## 🔩 Mechanical Assembly

Coming Soon™

## ⚡ Electrical Side Pack

Coming Soon™

## 🔄 Tool Changer Development

Coming Soon™

---

# 🛣️ Development Roadmap

## 🏗️ Phase 1 – Architecture

- [x] Mechanical concept development
- [x] Motion system selection
- [x] Triple-Z architecture selection
- [x] Side Pack concept development

## 📐 Phase 2 – Design Validation

- [ ] CAD finalization
- [ ] Electrical layout validation
- [ ] Tool changer design validation

## 🔧 Phase 3 – Physical Prototype

- [ ] Initial assembly
- [ ] Motion testing
- [ ] Tool-changing validation
- [ ] First print verification

## 🚀 Phase 4 – Public Release

- [ ] Documentation package
- [ ] Wiring guides
- [ ] BOM release
- [ ] Source file publication

---

# 🎯 Current Focus Areas

- 📐 CAD Finalization
- 🔄 Tool Changer Development
- ⚡ Side Pack Layout Optimization
- 📝 Documentation Creation

---

# 🙏 Thanks

Thanks to everyone following the project, offering feedback, sharing ideas, and helping push the design forward. Community knowledge and collaboration are what make projects like this possible.

---

# 🤝 Credits & Acknowledgments

### 🚀 Voron Design

Huge thanks to the Voron Design team and community contributors for creating and maintaining one of the most influential open-source 3D printer ecosystems available.

### 📐 Voron Trident

This project draws significant inspiration from the design philosophy, mechanical architecture, and engineering practices demonstrated by the Voron Trident platform.

### 🔗 Official Resources

- https://vorondesign.com
- https://github.com/VoronDesign

> **Disclaimer:** This is an independent community project and is not affiliated with, endorsed by, or supported by the Voron Design team.

---

# 👨‍💻 Authors

## 👤 Anthony Sleck

GitHub: **[@3lkgrove](https://github.com/3lkgrove)**

## 👤 Nathan Hochhalter

GitHub: **[@nhoch1535](https://github.com/nhoch1535)**

---

# 📜 License

Licensed under the terms of the **GNU General Public License v3.0 (GPL-3.0)**.

See the **LICENSE** file for complete details.

---

<p align="center">
  © 2026 @3lkgrove
</p>
