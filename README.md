# DRC & LVS check

**Objectives:**
-Design a schematic of a CMOS inverter using FreePDK45 PMOS and NMOS devices.
-Simulate the inverter for both DC and transient responses to validate switching behavior.
-Verify layout correctness using DRC and LVS checks via Calibre.

**Procedure Summary:**

1. Schematic Design
   
-PMOS and NMOS transistors were selected from the FreePDK45 library.

-Proper transistor sizing was used: PMOS width = 300nm, NMOS width = 150nm.


2. Simulation
   
-DC Sweep: Verified the inverter’s voltage transfer characteristic (VTC).

-Transient Analysis: Used a pulse waveform to validate clean switching behavior.


3. Layout Design
   
-Constructed layout using required layers (active, poly, metal1, etc.).

-Added n-well and threshold implants as required.


4. Verification
   
-DRC: Ensured all layout rules (minimum spacing, enclosure, extension) were satisfied.

-LVS: Used Calibre to confirm that the layout was per the schematic.


**Conclusion:**

The project successfully demonstrates the process of designing and verifying a CMOS inverter. Through schematic design, simulation, layout, and verification, key VLSI design skills were reinforced.

**References:**

-EE 332 Lab 4 Reference Sheet, Spring 2025

-Cadence Tutorial: ENGN1600, Brown University
