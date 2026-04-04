<h1 align="center">🦖 Voron Rex</h1>
<p align="center"><strong>A High-Rigidity 4040 "Flying Gantry" Toolchanger Conversion</strong></p>

---

## 📝 Project Overview
**Voron Rex** is a heavy-duty conversion project that transforms a **Formbot T-Rex V1** into a high-performance CoreXY machine. By marrying the massive 4040 frame of the T-Rex with the sophisticated kinematics of the Voron ecosystem, this build achieves a unique balance of industrial rigidity and modern tool-changing capabilities.

This project replaces the original T-Rex "bed-slinger" Y-axis with a high-rigidity **Flying Gantry CoreXY** system utilizing 4040 aluminum extrusions and a structural stressed-skin enclosure. The motion system features a **Quad-NEMA17 independent Z-axis** driven by leadscrews with top pillow blocks, enabling **Quad Gantry Leveling (QGL)** with superior mechanical positioning.

---

## ⚙️ Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Donor Chassis** | Salvaged 4040 Aluminum (Formbot T-Rex V1) |
| **Gantry Architecture** | Flying Gantry with Quad-Z Lead-screw Drive |
| **X-Axis** | 20mm x 20mm Square Carbon Fiber Tube w/ MGN9H Rail |
| **Y-Axis** | 2040 Aluminum Extrusions w/ Dual MGN9H Rails in compressed spine arrangement |
| **Print Surface** | T-Rex V1 Glass/Sheet-Metal (Converted to Fixed-Mount) |
| **Drive Train** | 9mm GT2 Belts + High-Torque Long-Shaft NEMA17s |
| **XY Joints** | Custom Voron-spec ASA-printed joints (Modified for 9mm) |
| **Tool System** | **Stealthchanger** Ecosystem w/ Top-Mounted "Garage" |
| **Controller** | BTT Manta M8P (V2.0) + CB1/CM4 |
| **Communication** | Full CANbus (Nitehawk-Hexa / EBB36) |

---

## 🚀 Key Design Features

### 🏗️ Quad-Z Lead Screw Gantry
The **Voron Rex** utilizes a specialized Z-axis motion system designed for stability and "stay-put" reliability:
* **Bottom-Seated NEMA17s:** Motors are securely mounted atop the base 4040 extrusions for easy maintenance and a lower center of gravity.
* **Anti-Lash Top Pillow Blocks:** High-precision 8mm lead screws are constrained by top-mounted pillow blocks, eliminating vibration and "whip."
* **Self-Locking Kinematics:** By utilizing low-start lead screws, the gantry remains stationary upon power-loss, preventing accidental drops.

### 🌉 The "Super Bracket" Interface
The gantry's structural integrity is anchored by 10mm thick ASA "Super Brackets" that act as the primary junction for the motion system:
* **Triple-Point Connection:** Each bracket serves as the monolithic mounting point for the MGN12H Z-axis carriage, the Y-axis 2040 gantry beam, and the lead-screw POM nut.
* **Precision Offset:** The 10mm thickness is standardized across all Z-axis components, creating a constant mechanical offset that simplifies frame squaring.
* **Integrated Alignment:** Built-in 2mm alignment ribs lock into the 4040/2040 extrusion channels, ensuring the Z-rails and Y-gantry remain perfectly perpendicular.

### 💎 Engineering-Grade Build Standards
Designed for high-duty cycle operation in heated environments:
* **Z-Axis Thermal Coupling:** Z-motors are mounted in direct contact with the 4040 base frame using ASA "L-Brackets" and M8 hardware, utilizing the chassis as a primary heat sink.
* **High-Temp A/B Configuration:** XY motors are **Class H rated (180°C)** and top-mounted on the 2040 Y-rails to isolate motion components from the highest heat zones.
* **Long-Shaft Support:** A/B motor shafts are supported by secondary outboard bearings within the XY joints to counteract the lateral tension of the 9mm belt system.

### 🌡️ Thermal Management & Chamber
* **Forced Convection Heating:** Integrated under-bed cooling fans act as a heat exchanger, actively moving energy from the bed heater into the chamber air.
* **Reflective Insulation:** Rear and bottom panels feature foil-faced insulating barriers (Reflectix) to minimize radiant heat loss.
* **Thermal Break Construction:** A 4mm air gap is maintained between the primary 4040 frame and the stressed-skin enclosure, providing an integrated thermal buffer.

---

## 🔧 Assembly Notes: The "Gravity-Stack" Logic
The **Voron Rex** utilizes custom internal geometry to simplify the assembly of complex composite-to-metal joins:
* **Gravity-Optimized X-Axis:** The internal X-rail nut carrier is designed as a "table" profile. This allows M3 square nuts and the aluminum load-spreader to be gravity-set during sub-assembly before being slid into the carbon fiber tube.
* **Crush-Proof Clamping:** Internal ASA "plugs" are integrated into the rail carriers to provide internal support for the carbon fiber tube, preventing delamination from the high-tension 9mm belt clamps.

---

## 📂 Repository & CAD Structure
The full design source is provided as a **Master FreeCAD file**, structured for easy modification:
* **Master Parts:** Contains the base geometry for the 4040/2040 frame and gantry.
* **Part Pieces:** Discrete components ready for export to STL/STEP.
* **Simplified Mechanicals:** Low-poly models of rails, motors, and screws for checking clearances and interference without heavy compute overhead.

---

## 🤝 Acknowledgments
* The **Voron Design** team for the foundational kinematics.
* The **Stealthchanger** community for the tool-changing ecosystem.
* **Formbot** for the "Heavy Metal" T-Rex donor frame.

---

## 📜 License & Usage
This project is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.

### 🛑 Commercial Use
The "Non-Commercial" clause is strictly enforced. **Commercial sale of the "Voron Rex" as a kit, pre-built machine, or commercial upgrade package is prohibited without an explicit commercial licensing agreement from the author.** If you are a commercial entity interested in a retail venture involving this design, please contact the repository owner.

[![License: CC BY-NC-SA 4.0](https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by-nc-sa/4.0/)

This work is licensed under a [Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International License](https://creativecommons.org/licenses/by-nc-sa/4.0/).

### 🤝 Community Use
* **Personal Builds:** You are free (and encouraged!) to build, modify, and improve this design for your own use.
* **Pay It Forward (PIF):** Providing printed ASA components to other hobbyists at the cost of materials and machine time is permitted. We support the community helping the community.
* **ShareAlike:** Any remixes or modifications to these files must be shared under this same license.
