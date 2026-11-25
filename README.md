# 🚀 Compact CoreXY Multi-Tool 3D Printer

### 🔧 Voron-Inspired Tool-Changing CoreXY Platform

<p align="center">
  <img src="https://img.shields.io/badge/Status-Active%20Development-10B981?style=for-the-badge">
  <img src="https://img.shields.io/badge/License-GPL--3.0-2563EB?style=for-the-badge">
  <img src="https://img.shields.io/badge/Motion-CoreXY-DC2626?style=for-the-badge">
  <img src="https://img.shields.io/badge/Z%20System-Triple--Z-059669?style=for-the-badge">
  <img src="https://img.shields.io/badge/Toolheads-Multi--Tool-7C3AED?style=for-the-badge">
</p>

A scratch-built compact CoreXY 3D printer inspired by Voron architecture, featuring a **sub-200 mm build volume**, **Trident-style Triple-Z moving bed**, **automated multi-tool capability**, and an **industrial DIN-rail Side Pack** for thermally isolated electronics and power distribution.

---

## ⚠️ Project Status

```diff
+ ACTIVE DEVELOPMENT
```

> **Official project name is currently TBD.**
>
> Mechanical architecture, enclosure design, and tool-changing systems are actively being developed and refined.

---

## ✨ Key Features

### 🔄 Multi-Tool Printing Platform
- Automated multi-tool docking system.
- Designed for future multi-material and specialty tool support.
- Optimized for low-footprint multi-tool operation.

### 🏭 External Side Pack Electronics Bay
- Separate enclosure for power distribution and control hardware.
- Keeps sensitive electronics isolated from chamber temperatures.
- Improves accessibility and serviceability.

### 🔌 Industrial DIN Rail Infrastructure
- DIN-rail-mounted power supplies.
- Modular terminal block distribution.
- Organized AC/DC routing and simplified maintenance.

### ⚡ High-Speed CoreXY Motion System
- Lightweight CoreXY kinematics.
- Designed around tool-changer mass considerations.
- Focused on acceleration, rigidity, and reliability.

### 🔥 Fully Enclosed Printing Environment
- Polycarbonate enclosure panels.
- Improved thermal stability.
- Engineering filament capable design.

### 📐 Trident-Style Triple-Z System
- Three independently driven Z motors.
- Automatic gantry leveling capability.
- Open upper deck for tool changing and maintenance access.

---

## 🏗️ Core Architecture

| Subsystem | Specification | Notes |
| :--- | :--- | :--- |
| **Build Volume** | < 200 × 200 × 200 mm | Compact chamber design |
| **Frame** | 2020 Aluminum Extrusions | Voron-inspired rigid cube chassis |
| **XY Kinematics** | CoreXY | High-speed motion platform |
| **Z Kinematics** | Triple-Z Moving Bed | Trident-style leveling system |
| **Tool System** | Multi-Head Tool Changer | Automated tool docking |
| **Electronics Bay** | External Side Pack | Thermal isolation architecture |
| **Mounting Method** | Industrial DIN Rails | Modular power distribution |
| **Enclosure** | Polycarbonate Panels | Elevated temperature capability |
| **Firmware** | Klipper (Planned) | High-performance motion control |

---

## 🌟 Design Highlights

### 🧊 Thermally Isolated Electronics

Unlike many enclosed printers where electronics share space with the chamber, all major power and control hardware are relocated into a dedicated Side Pack.

This approach:

- Reduces thermal stress on electronics
- Simplifies servicing
- Allows higher chamber temperatures
- Eliminates the need for oversized lower electronics compartments

---

### 🏭 Industrial Electrical Design

The Side Pack is designed around industrial control-panel principles:

- DIN rail hardware mounting
- Structured cable routing
- Modular terminal blocks
- Expandable power distribution
- Simplified troubleshooting

---

### 🔄 Compact Multi-Material Capability

One of the primary goals of the project is combining:

- Tool-changing functionality
- Compact footprint
- High chamber temperatures
- Trident-style mechanics

without requiring the physical size of large-format tool-changing machines.

---

## 📂 Repository Structure

```text
.
├── CAD/
│   ├── STEP Files
│   └── Reference Models
│
├── STLs/
│   └── Printable Components
│
├── Docs/
│   ├── Wiring Diagrams
│   ├── DIN Rail Layouts
│   ├── Assembly Documentation
│   └── BOM
│
├── LICENSE
└── README.md
```

---

## 🛠️ Planned Components

| Component | Status |
| :--- | :--- |
| CoreXY Motion System | 🚧 In Progress |
| Triple-Z Platform | 🚧 In Progress |
| Side Pack Architecture | 🚧 In Progress |
| Tool Changer System | 🚧 In Progress |
| Wiring Documentation | 🚧 In Progress |
| Complete CAD Package | 🚧 In Progress |
| Initial Prototype Build | 🚧 In Progress |

---

## 📸 Project Gallery

### CAD Renders
Coming Soon™

### Mechanical Assembly
Coming Soon™

### Electrical Side Pack
Coming Soon™

### Tool Changer Development
Coming Soon™

---

## 🛣️ Development Roadmap

### Phase 1 – Architecture
- [x] Mechanical concept development
- [x] Motion system selection
- [x] Triple-Z architecture selection
- [x] Side Pack concept development

### Phase 2 – Design Validation
- [ ] CAD finalization
- [ ] Electrical layout validation
- [ ] Tool changer design validation

### Phase 3 – Physical Prototype
- [ ] Initial assembly
- [ ] Motion testing
- [ ] Tool-changing validation
- [ ] First print verification

### Phase 4 – Public Release
- [ ] Documentation package
- [ ] Wiring guides
- [ ] BOM release
- [ ] Source file publication

---

### Current Focus Areas

- CAD Finalization
- Tool Changer Development
- Side Pack Layout Optimization
- Documentation Creation

---

### 🔩 Built for high-speed printing, modular experimentation, and entirely too many future upgrades.

---

## 👨‍💻 Authors

### Anthony Sleck
GitHub: **@3lkgrove**

### Nathan Hochhalter

---

## 📜 License

Licensed under the terms of the **GNU General Public License v3.0 (GPL-3.0)**.

See the LICENSE file for complete details.

© 2026 @3lkgrove
