# SUZUKI INDIAN FCEV — Optimized Vehicle Sizing & Dynamics Model

## Suzuki Igniters Innovation Challenge 2026

A concept-study and engineering analysis of a **Fuel Cell Electric Vehicle (FCEV)** designed for Indian road conditions, focusing on vehicle sizing, hydrogen storage, fuel-cell power requirements, performance, energy efficiency, safety, total cost of ownership, manufacturing feasibility, and hydrogen infrastructure.

The project combines **physics-based MATLAB modelling, vehicle-level calculations, CAD packaging, and techno-economic analysis** to develop a practical hydrogen-powered vehicle concept.

---

## Team

- **Abhik Pal**
- **Arhaan Kocchar**
- **Lakshmanan Ganapath**

**Institution:** BITS Pilani, Rajasthan

---

## Project Overview

The objective of this project is to develop a technically feasible FCEV concept that addresses the major challenges associated with hydrogen mobility:

- Vehicle range
- Hydrogen storage
- Fuel-cell sizing
- Peak power requirements
- Fast refuelling
- Vehicle packaging
- Safety
- Energy efficiency
- Total cost of ownership
- Manufacturing scalability
- Hydrogen refuelling infrastructure

The proposed concept targets approximately **500 km of range** while using a combination of a hydrogen fuel-cell stack and a small high-power buffer battery.

---

## Key Vehicle Specifications

| Parameter | Value |
|---|---:|
| Target Range | ~500 km |
| Total Vehicle Mass | ~1,603 kg |
| Corrected Vehicle Mass | ~1,620 kg |
| Usable Hydrogen | 4.95 kg |
| Hydrogen Consumption | 0.99 kg/100 km |
| Number of H₂ Tanks | 2 |
| Tank Type | Type-IV |
| Total Tank Volume | 128.2 L |
| Fuel Cell Rated Power | 55 kW |
| Fuel Cell Stack Voltage | 300.3 V |
| Fuel Cell Cells | 462 |
| Buffer Battery | 3.36 kWh |
| Buffer Battery Mass | 37.3 kg |
| Traction Motor Peak Power | 126.9 kW |
| Tank-to-Wheel Efficiency | ~40.6% at cruise |

The vehicle sizing and component specifications are generated from the project's physics-based MATLAB sizing model. :chatgpt-content-reference{index="1"}

---

## Vehicle Architecture

The proposed vehicle architecture consists of:

```text
             HYDROGEN
                │
                ▼
        ┌────────────────┐
        │  Type-IV H₂    │
        │     Tanks      │
        └───────┬────────┘
                │
                ▼
        ┌────────────────┐
        │ Fuel Cell Stack│
        │     55 kW      │
        └───────┬────────┘
                │
                ▼
        ┌────────────────┐
        │ DC-DC Converter│
        └───────┬────────┘
                │
        ┌───────┴────────┐
        │                │
        ▼                ▼
 Buffer Battery      Traction System
  3.36 kWh          Motor + Inverter
                         │
                         ▼
                       Wheels
