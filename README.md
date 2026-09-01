# BEMT-Based Design, Fabrication and Flight Testing of a Quadrotor UAV

<p align="center">
  <img src="images/final_assembly.jpg" width="750">
</p>

<p align="center">
  <b>Computational Design → Component Selection → Fabrication → Bench Testing → Flight Testing</b>
</p>

---

**Course Project — Computational Aeromechanics of UAVs (AE630)**  
**Department of Aerospace Engineering, IIT Kanpur**  
**Instructor:** Dr. Navrose  
**January 2026 – April 2026**

[📄 Full Project Report](./AE630_Final_Report.pdf)

## 1. Overview

This project involved the complete computational and experimental development of a small quadrotor UAV, from preliminary sizing and propulsion analysis through fabrication, ground testing, and flight testing.

The primary design requirement was to carry a **300 g payload while achieving 20 minutes of hover endurance**. A Blade Element Momentum Theory (BEMT)-based weight-optimisation tool was developed in MATLAB to determine a feasible combination of rotor geometry, motor, battery, and other vehicle parameters. :contentReference[oaicite:1]{index=1}

A parametric search was then performed over rotor radius, blade count, blade chord, root pitch, battery cell count, and motor Kv. The optimisation evaluated **47,040 design combinations**, subject to a disc-loading constraint of 40–90 N/m², and selected the feasible configuration with minimum converged Gross Take-Off Weight (GTOW). :contentReference[oaicite:2]{index=2}

The computational design was subsequently translated into a physical vehicle. Components were selected based on the optimisation results, a custom PETG frame was designed and fabricated, and the assembled vehicle was characterised through motor-propeller bench testing before being taken through flight testing.

The project therefore provided a complete design loop:

**BEMT-based sizing → optimisation → component selection → CAD → fabrication → propulsion characterisation → flight testing → flight-log analysis and refinement.**
