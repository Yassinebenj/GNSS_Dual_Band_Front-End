# Dual-Band (L1/L5) GNSS Patch Antenna System
**Western University Electrical Engineering Capstone Project** *Awarded Honorable Mention at the 2026 EE Capstone Showcase*

## 🛰️ Project Overview
This project involves the end-to-end design, EM simulation, and hardware-readiness of a high-precision GNSS antenna system. Designed for the **L1 (1575.42 MHz)** and **L5 (1176.45 MHz)** bands, this system provides sub-meter positioning accuracy and robust multipath rejection, optimized for autonomous vehicle navigation.

## 🛠️ Technical Specifications
- **Frequencies:** L1 (1575.42 MHz) and L5 (1176.45 MHz)
- **Architecture:** - Wilkinson Combiners and dividers
    - Integrated Low-Noise Amplifier (LNA) for signal sensitivity.
    - Cascaded Bandpass Filters (BPF) for interference rejection.
- **Impedance Matching:** Inset-fed PCB Antennas and Wilkinson Power Dividers designed for dual-feed optimization.

## 💻 Simulation & Design
- **Software:** Keysight Advanced Design System (ADS).
- **EM Analysis:** Conducted full-wave electromagnetic simulations to optimize radiation patterns and gain.
- **PCB Stackup:** 2-layer FR-4 PCB to minimize costs.

## 🧪 Hardware Validation (Test Engineering Focus)
*Designed with "Design for Test" (DFT) principles in mind:*
- **S-Parameter Analysis:** Validated Return Loss ($S_{11}$) to be < -25 dB at both center frequencies.
- **Prototype Readiness:** Defined test points for DC bias verification of the LNA and signal integrity checks across the RF chain.

## 📂 Repository Structure
```text
├── Schematics/         # Signal chain and power management PDFs
├── Simulation_Results/    # ADS data displays, Smith Charts, and Gain plots
├── Gerber Files/        # For manufacturing
├── Layout/             # Gerber files and 3D PCB renders
└── Documentation/               # Final Technical Report and Showcase Presentation
