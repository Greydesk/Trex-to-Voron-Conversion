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
| **Y-Axis** | 2040 Aluminum Extrusions w/ Dual MGN9H Rails |
| **Drive Train** | **10mm GT2 Belts** + High-Torque Long-Shaft NEMA17s |
| **Shaft Support** | **KFL05 Outboard Flange Bearings** (Bridged Axle Design) |
| **Tool System** | **Stealthchanger** Ecosystem w/ Top-Mounted "Garage" |
| **Toolhead / Cooling** | **Burninator** (Compact 4010 Blower Design) |
| **Extruder** | **LDO Orbiter 2.0** (Planetary 7.5:1 Dual-Drive) |
| **Hotend** | **Phaetus Rapido UHF** (Extended Melt Zone / Ceramic) |
| **Controller** | BTT Manta M8P (V2.0) + CB1/CM4 |
| **Communication** | Full CANbus (Nitehawk-Hexa / EBB36) |

---

## 🚀 Key Design Features

### 🏗️ Quad-Z Lead Screw Gantry
The **Voron Rex** utilizes a specialized Z-axis motion system designed for stability and "stay-put" reliability:
* **Bottom-Seated NEMA17s:** Motors are securely mounted atop the base 4040 extrusions for a lower center of gravity.
* **Anti-Lash Top Pillow Blocks:** High-precision 8mm lead screws are constrained by top-mounted pillow blocks, eliminating vibration and "whip."
* **Self-Locking Kinematics:** By utilizing low-start lead screws, the gantry remains stationary upon power-loss, preventing accidental drops.

### 🌉 The "Omega Drive" Outboard Support
To handle the extreme tension of the **10mm belt system**, the A/B motors utilize a structural "cage" or bridged-axle arrangement:
* **Bridged-Axle Support:** The long motor shafts are captured by **KFL05 flange bearings** mounted to the bottom 4mm aluminum plate. This prevents shaft deflection and protects the motor's internal bearings from axial load.
* **Locked Vertical Alignment:** Shaft collars (or KFL05 set screws) lock the vertical position of the drive pulley, ensuring the belt path never "wanders" or climbs pulley flanges during high-acceleration moves.

### 💎 High-Flow Toolhead Configuration
The Rex is optimized for industrial-speed printing of engineering materials:
* **Burninator Toolhead:** A high-efficiency, lightweight toolhead that fits into the Stealthchanger linkage while supporting ultra-high-flow hotends.
* **Rapido UHF Integration:** Utilizing a ceramic heater and volcano-style melt zone, the system supports volumetric flows up to **75mm³/s**, matching the high-speed potential of the 10mm gantry.
* **Orbiter 2.0 Precision:** The LDO Orbiter 2.0 provides the necessary pushing force (20kg+) to maintain consistent extrusion pressure through the UHF melt zone without skipping.

---

## 🔧 Assembly Notes: The "Cradle & Gravity" Workflow
The **Voron Rex** utilizes a specific assembly sequence to ensure squareness without specialized jigs:
* **Bottom-Up Cradle:** The lower XY brackets and motor plates are installed first. This creates a "cradle" that supports the weight of the X-axis during installation.
* **Gravity-Assist Rail Mount:** The internal X-rail nut table is installed by rotating the CF tube 90 degrees vertically, allowing nuts to drop into place and remain seated during screw insertion.
* **Gantry Seating:** The fully-assembled X-axis (CF tube + MGN9H) is lowered into the bottom brackets, using gravity to maintain alignment before the top "cap" brackets are secured.

---

## 📂 Repository & CAD Structure
The full design source is provided as a **Master FreeCAD file**, structured for efficiency:
* **Master Parts:** Base geometry for the 4040/2040 frame.
* **Simplified Mechanicals:** High-performance **Proxies** for linear rails and carriages (simple geometric blocks) to maintain high frame rates during assembly modeling.

---

## 🤝 Acknowledgments
* The **Voron Design** team for the foundational kinematics.
* The **Stealthchanger** community for the tool-changing ecosystem.

---

## 📜 License & Usage
This project is licensed under **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**.
