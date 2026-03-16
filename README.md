# Twin-Spool Turboprop Engine: Design & Performance Analysis

This repository contains a comprehensive thermodynamic and performance study of a twin-spool turboprop engine. The project is divided into two major analytical phases: **Design Point Selection** and **Off-Design Operational Mapping**.

The study uses technology levels consistent with 2005 standards and focuses on optimizing specific thrust and fuel efficiency for military transport applications.

---

## Table of Contents
- [Project Overview](#project-overview)
- [Part 1: Design Point Operation](#part-1-design-point-operation)
- [Part 2: Off-Design Operation](#part-2-off-design-operation)
- [Key Engineering Skills Demonstrated](#key-engineering-skills-demonstrated)
- [Authors](#authors)

---

## Project Overview
The goal of this project was to design a robust propulsion system for a **CASA CN-235** class aircraft. We modeled a twin-spool architecture where a High-Pressure Turbine (HPT) drives the High-Pressure Compressor (HPC), and a Low-Pressure Turbine (LPT) drives both the Low-Pressure Compressor (LPC) and the propeller via a gearbox.

### Technical Constraints:
- **Flight Conditions:** Mach 0.65 at 35,000 ft (ISA).
- **Architecture:** Twin-spool axial compressors and turbines, convergent propulsive nozzle.

---

## 🛠 Part 1: Design Point Operation
In this phase, we implemented a thermodynamic cycle model to identify the optimal "Design Point" based on sensitivity analyses of compression ratios and heating degrees.

### Selected Design Parameters:
| Parameter | Symbol | Selected Value |
| :--- | :--- | :--- |
| Heating Degree | $\theta$ | 5.827 |
| Enthalpy Drop Fraction | $\alpha$ | 0.85 |
| Total Pressure Ratio | $\pi_c$ | 14 |

### Design Results:
- **Specific Thrust ($E_e$):** 1126.05 Ns/kg
- **TSFC:** 45.12 (kg/h)/kN
- **Cycle Efficiency:** Optimized for a balance between high power output and fuel economy.

---

## Part 2: Off-Design Operation
Once the design point was frozen, the engine was "sized" to meet the real-world thrust requirements of the **CASA CN-235**. We then simulated the engine's behavior across its entire flight envelope using scaled compressor and turbine maps.

### Engine Sizing Results:
- **Required Design Thrust:** 6,553 N per engine.
- **Air Mass Flow ($\dot{m}_a$):** 5.8536 kg/s.
- **Nozzle Exit Area ($A_8$):** 0.1495 m².

### Critical Validations:
- **Surge Margins:** All operational points were verified to maintain at least a **20% surge margin** for safety.
- **Take-off Capability:** The engine provides **23% surplus thrust** at sea level compared to the design requirement, ensuring safe take-off performance.
- **Flight Envelope:** Performance was mapped for various altitudes: Sea Level, 21,000 ft, and 35,000 ft.

---

## Key Engineering Skills Demonstrated
* **Thermodynamic Cycle Analysis:** Real gas modeling and entropy/enthalpy (h-s) diagrams.
* **Performance Engineering:** Scaling component maps and calculating off-design equilibrium.
* **Sizing & Integration:** Matching engine performance to aircraft-specific aerodynamic requirements.
* **Software Proficiency:** Numerical simulation and data visualization (MATLAB/Python).

---

## Authors
* **Luis Fernando Valladares Sifuentes**
* **Mikel Segovia Díaz**
* **Alberto Yúfera Daza**

---
*Developed as part of the "Jet Engine Design" curriculum (MIA).*
