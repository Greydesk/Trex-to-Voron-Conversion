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
| **Print Surface** | T-Rex V1 Glass/Sheet-Metal (Converted to Fixed-Mount) |
| **Drive Train** | **10mm GT2 Belts** + High-Torque Long-Shaft NEMA17s |
| **Shaft Support** | **KFL05 Outboard Flange Bearings** (Bridged Axle Design) |
| **Tool System** | **Stealthchanger** Ecosystem w/ Top-Mounted "Garage" |
| **Toolhead / Cooling** | **Burninator** (Compact 4010 Blower Design) |
| **Extruder** | **LDO Orbiter 2.0** (Planetary 7.5:1 Dual-Drive) |
| **Hotend** | **Phaetus Rapido UHF** (Extended Melt Zone / Ceramic) |
| **Controller** | BTT Manta M8P (V2.0) + CB1/CM4 |

---

## 🚀 Key Design Features

### 🏗️ Quad-Z Lead Screw Gantry & "Super Brackets"
The **Voron Rex** utilizes a specialized Z-axis motion system designed for stability:
* **Anti-Lash Top Pillow Blocks:** High-precision 8mm lead screws are constrained by top-mounted pillow blocks, eliminating vibration and "whip."
* **Self-Locking Kinematics:** Low-start lead screws ensure the gantry remains stationary upon power-loss, preventing accidental toolhead drops.
* **ASA Super Brackets:** The gantry's structural integrity is anchored by **10mm thick ASA brackets** acting as monolithic junction points for the MGN12H Z-carriages, Y-axis 2040 beams, and lead-screw POM nuts.
* **Integrated Alignment:** Built-in **2mm alignment ribs** lock into extrusion channels, ensuring the Z-rails and Y-gantry remain perfectly perpendicular.

### 🌉 The "Omega Drive" Outboard Support
To handle the extreme tension of the **10mm belt system**, the A/B motors utilize a structural bridged-axle arrangement:
* **Bridged-Axle Support:** Long motor shafts are captured by **KFL05 flange bearings** mounted to the bottom 4mm aluminum plate, preventing shaft deflection.
* **Locked Vertical Alignment:** Shaft collars lock the vertical position of the drive pulley, ensuring the 10mm belt path never "wanders" during high-acceleration moves.

### 🌡️ Thermal Management & Chamber
Engineered for high-ambient temperatures required for Nylon, PC, and ASA:
* **Forced Convection Heating:** Integrated under-bed cooling fans act as a heat exchanger, moving energy from the bed into the chamber air.
* **Reflective Insulation:** Rear and bottom panels feature **foil-faced insulating barriers** (Reflectix) to minimize radiant heat loss.
* **Thermal Break Construction:** A 4mm air gap is maintained between the primary 4040 frame and the stressed-skin enclosure, providing an integrated thermal buffer.

---

## 🔧 Assembly Notes: The "Gravity-Stack" Logic
The assembly sequence ensures squareness and protects composite components:
* **Gravity-Optimized X-Axis:** The internal X-rail nut carrier is designed as a "table" profile. This allows M3 square nuts to be gravity-set during sub-assembly before being slid into the carbon fiber tube.
* **Crush-Proof Clamping:** Internal **ASA "plugs"** are integrated into the rail carriers to provide internal support for the carbon fiber tube, preventing delamination from the high-tension **10mm belt clamps**.
* **Self-Squaring Gantry:** The Super Brackets mate with the 4040/2040 slots, ensuring the gantry stays square during the initial bolt-down phase.

---

## 📂 Repository & CAD Structure
The design is provided as a **Master FreeCAD file**:
* **Master Parts:** Base geometry for the 4040/2040 frame.
* **Simplified Mechanicals:** High-performance proxies for rails and carriages to maintain high frame rates during assembly modeling.

---

## 🤝 Acknowledgments
* The **Voron Design** team for the foundational kinematics.
* The **Stealthchanger** community for the tool-changing ecosystem.
* **Formbot** for the "Heavy Metal" T-Rex donor frame that made this tank of a printer possible.

---

## 📜 License & Usage
This project is licensed under **CC BY-NC-SA 4.0**.
