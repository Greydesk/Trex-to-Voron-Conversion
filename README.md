# Trex-to-Voron-Conversion
Project Baseline: The 350mm Stealth-Trident

This project is a high-rigidity Flying Gantry CoreXY 3D printer utilizing 4040 aluminum extrusions (salvaged from a Formbot T-Rex V1) and a stressed-skin enclosure. The motion system features a Quad-NEMA17 independent Z-axis driven by leadscrews with top pillow blocks, enabling Quad Gantry Leveling (QGL) with superior mechanical positioning.

Gantry & Motion Architecture:
X-Axis: Ultra-lightweight Carbon Fiber 2020 extrusion with a single MGN9H rail. This minimizes moving mass to compensate for the weight of the toolchanger shuttle and 9mm hardware.

Y-Axis: Standard 2040 aluminum extrusions with MGN9H rails in the official Voron arrangement for thermal stability and alignment.

XY Joints: Custom Voron-spec ASA-printed joints, modified for 9mm belt clearance.

A/B Drive: 9mm belt path with GT2 idlers and integrated end-shaft bearing support for long-shaft NEMA17 motors.

Tooling, Electronics & Expansion:
Tool System: Stealthchanger tool-changing ecosystem with a top-mounted "Garage."

Toolhead: Stealthburner (or compatible).

Communication: Full CANbus architecture (e.g., Nitehawk-Hexa or EBB36) to streamline wiring for multiple toolheads.

Control: BTT Manta M8P (V2.0) with a CB1/CM4, managing quad-Z leadscrews and high-torque XY motion.

Enclosure: A custom Top-Hat will be utilized to provide clearance for toolhead umbilicals at max Z-height.
