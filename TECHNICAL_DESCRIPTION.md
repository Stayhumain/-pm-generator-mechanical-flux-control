Technical Description

Permanent Magnet Generator with Mechanical Flux and Winding Regulation

1. Technical Field

This invention relates to permanent magnet electrical machines, particularly three-phase generators, and more specifically to power regulation systems that do not rely on power electronics.

⸻

2. Background

In conventional permanent magnet generators, power regulation is typically achieved using electronic converters such as inverters, rectifiers, or DC choppers. These systems increase:
	•	System complexity
	•	Cost
	•	Failure points
	•	Thermal stress

Mechanical regulation systems exist but are often complex or poorly adapted to standard three-phase PM machines.

⸻

3. Technical Problem

The objective is to provide a simple, robust, and reliable solution for regulating the output power and voltage of a PM generator without using power electronics, while maintaining a conventional machine architecture.

⸻

4. Proposed Solution

The solution combines:
	1.	Mechanical flux regulation through radial stator displacement (airgap variation)
	2.	Winding commutation, allowing different coil groups per phase to be selected

⸻

5. Detailed Embodiments

5.1 Generator with Movable Stator
The generator comprises:
	•	A rotor equipped with permanent magnets
	•	A stator with three-phase windings

The stator is mounted radially movable on guides or bearings. An actuator (motorized lead screw or hydraulic system) moves the stator inward or outward, adjusting the airgap.

This modifies magnetic flux and thus generated voltage.

Mechanical stops and position sensors prevent rotor–stator contact.

⸻

5.2 Winding Commutation
Each phase contains four coils (A1–A4, B1–B4, C1–C4).

Two configurations are selectable:
	•	Low-voltage mode: two coils in series per phase
	•	High-voltage mode: four coils in series per phase

Switching is performed off-load using contactors controlled by the control unit.

⸻

5.3 Control System
A controller (PLC or microcontroller) monitors:
	•	Voltage
	•	Current
	•	Speed
	•	Stator position

It controls:
	•	Stator actuator
	•	Winding contactors
	•	Load connection/disconnection

⸻

6. Claims (Functional Definition)
7. Functional Claims

Claim 1 (Independent)

A permanent magnet (PM) electric generator comprising:
	•	a rotor including permanent magnets;
	•	a stator including three-phase windings;
	•	a guiding mechanism configured to allow radial displacement of the stator relative to the rotor in order to vary the air gap and regulate the magnetic flux passing through the windings;
	•	a switching device configured to select different groups of windings per phase in order to adjust the output voltage;
	•	a control system configured to control the stator displacement and the winding switching.

⸻

Claim 2

The generator according to Claim 1, wherein the stator is mounted on guides or bearings allowing uniform radial displacement.

⸻

Claim 3

The generator according to Claim 1, wherein the actuator for radial displacement is a motorized lead screw.

⸻

Claim 4

The generator according to Claim 1, wherein the actuator for radial displacement is a hydraulic system.

⸻

Claim 5

The generator according to Claim 1, wherein each phase includes four coils, and the switching device is configured to select either two coils in series or four coils in series per phase.

⸻

Claim 6

The generator according to Claim 5, wherein the switching is performed off-load using contactors.

⸻

Claim 7

The generator according to any of the preceding claims, further comprising mechanical stops limiting the radial displacement of the stator.

⸻

Claim 8

The generator according to any of the preceding claims, further comprising a stator position sensor and a controller configured to prevent any collision between the stator and the rotor.
