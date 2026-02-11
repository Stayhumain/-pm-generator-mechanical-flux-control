Permanent Magnet Generator with Mechanical Flux Regulation and Winding Switching

Open-Source Electromechanical Generator Architecture

This project presents an open-source design for a permanent magnet (PM) electric generator featuring:
	•	Mechanical magnetic flux regulation through a radially movable stator
	•	Selectable stator winding configurations to adjust output voltage
	•	A control system coordinating both mechanical and electrical adjustments

This concept enables power and voltage regulation without relying on power electronics, improving robustness and reliability in harsh environments.

⸻

🌍 Motivation

Most PM generators regulate output using electronic converters (inverters, rectifiers, choppers). These add:
	•	Cost
	•	Complexity
	•	Thermal stress
	•	Reduced reliability in marine, wind, and remote installations

This project explores a purely electromechanical regulation strategy designed to be:

✔ Robust
✔ Simple
✔ Repairable
✔ Suitable for open engineering development

⸻

⚙️ Core Innovations

1️⃣ Mechanical Flux Control (Variable Airgap)

The stator is mounted on a radial guidance system allowing controlled movement relative to the rotor.

Changing the airgap:
	•	Modifies magnetic flux through the windings
	•	Adjusts generated voltage and power
	•	Acts as a mechanical field-weakening/field-strengthening system

📷 Figure 1 – Variable Airgap Generator
Selectable Winding Configuration

Each phase includes multiple coil groups. A switching system allows:
	•	Low-voltage mode: 2 coils in series per phase
	•	High-voltage mode: 4 coils in series per phase

Switching is performed off-load using contactors controlled by the system controller.

📷 Figure 2 – Winding Commutation Diagram
System Architecture

The system includes:
	•	Permanent magnet rotor
	•	Three-phase stator with multiple coil groups
	•	Radial stator movement mechanism (screw actuator or hydraulic system)
	•	Winding commutation contactors
	•	Position sensors and mechanical stops
	•	Control unit (PLC or microcontroller)

The controller manages:
	•	Stator position
	•	Coil configuration
	•	Load connection

⸻

🏭 Applications

This architecture is suitable for:
	•	Wind turbines
	•	Hydropower generators
	•	Marine and offshore energy systems
	•	Remote industrial generation
	•	Any application where electronic power converters are undesirable
Technical Documentation

A detailed technical and functional description is available here:
➡️ TECHNICAL_DESCRIPTION.md￼
Open Source Philosophy

This invention is released as open hardware.

Anyone is free to:
	•	Study
	•	Build
	•	Modify
	•	Improve

This project is shared to encourage collaborative engineering, not exclusive commercial control.
Safety Notice

This design involves rotating machinery and electrical generation.
Proper mechanical design, electrical protection, and professional validation are required before real-world use.
