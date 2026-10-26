# 5-Transistor CMOS Operational Transconductance Amplifier (5T OTA)
**5-Transistor CMOS Operational Transconductance Amplifier (OTA)** designed in **250 nm CMOS technology** using **Tanner T-Spice**. Transistor sizing was performed using the **gm/ID methodology** with **gm/ID lookup tables**, followed by schematic-level optimization and validation through DC, AC, and transient simulations.

---

## Design Specifications

| Parameter | Value |
|-----------|-------|
| Technology | 250 nm CMOS (BSIM3) |
| Supply Voltage | 2.5 V |
| Load Capacitance | 2 pF |
| Bias Current | 20 µA |
| Bias Circuit | NMOS diode-connected current mirror |
| Reference Resistor | 95.1 kΩ |

---

## Transistor Dimensions

| Device | Function | W/L (µm/µm) |
|--------|----------|-------------|
| M1, M2 | NMOS Differential Pair | 4 / 0.5 |
| M3, M4 | PMOS Active Load | 8.5 / 0.5 |
| M5 | NMOS Tail Current Source | 3 / 0.5 |
| M6 | NMOS Bias Transistor | 3 / 0.5 |

---

## Performance Summary

| Parameter | Measured Value |
|-----------|----------------|
| Differential Gain (Ad) | 34 dB |
| Common Mode Gain (Acm) | -37.7 dB |
| CMRR | 71.8 dB |
| Unity Gain Bandwidth | 12 MHz |
| Phase Margin | 90.51° |
| Slew Rate | 0.6 V/µs |
| ICMR | 0.44 V – 2.20 V |
| Output Swing | 0.75 V – 2.35 V |

---

## Simulations Performed

- DC Operating Point
- DC Transfer Characteristics
- AC Frequency Response
- Phase Margin Analysis
- Slew Rate Analysis
- CMRR Analysis
- ICMR Analysis
- Output Swing Analysis


## Tools Used

- Tanner EDA
- T-Spice
- gm/ID Lookup 

---

## Author
Suraj Kumar Mondal
