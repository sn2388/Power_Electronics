# Power_Electronics

# EE 506 – Advanced Power Electronics

Graduate coursework covering simulation, modeling, and literature review of modern power electronic converters, completed for EE 506 (Advanced Power Electronics) at Northern Arizona University.

## Contents

### Graduate Work 2 – DC-DC Converter Simulation (PLECS)
Simulation and performance analysis of five DC-DC converter topologies using 
PLECS:
- **Buck (step-down)** — CCM operation, inductor/capacitor ripple analysis, inductance sizing for target ripple specs
- **Boost with PFC** — power factor correction, average vs. switching model comparison
- **Flyback** — transformer isolation, turns-ratio and critical resistance (CCM/DCM boundary) analysis
- **Forward** — core reset/demagnetization, switch voltage stress
- **Full-bridge** — high-power isolated topology, ripple current verification

Each topology includes theoretical derivations (ripple equations, critical inductance/resistance) cross-checked against PLECS simulation results.

### Graduate Work 3 – PWM Techniques for Inverters (MATLAB/Simulink)
Implementation and comparison of modulation strategies:
- **SPWM** for a two-level inverter (baseline sinusoidal PWM)
- **IPD (In-Phase Disposition)** modulation for a four-level inverter
- **APOD (Alternative Phase Opposition Disposition)** modulation for a four-level inverter

Includes FFT-based THD analysis and harmonic spectrum comparison across all three modulation schemes.

### Advanced Power Electronic Conversion Technologies (Review Paper)
A literature review covering:
- Wide-bandgap (SiC, GaN) semiconductor devices for high-frequency/high-voltage converters
- DC/AC, DC/DC, AC/DC, and AC/AC (matrix) converter topologies
- Multilevel voltage/current source converters (NPC, CHB, ANPC, MMC)
- Application-specific topology selection (wind, PV, EV/HEV charging, ship propulsion)
- Modulation and predictive control techniques (PWM, SVM, SHE/SHM, FS-MPC)

## Tools
PLECS, MATLAB/Simulink
