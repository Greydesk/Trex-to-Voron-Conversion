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
| **Y-Axis** | 2040 Aluminum Extrusions w/ Dual MGN9H Rails (Voron Arrangement) |
| **Print Surface** | **T-Rex V1 Glass/Sheet-Metal** (Converted to Fixed-Mount) |
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
* **Anti-Lash Top Pillow Blocks:** High-precision 8mm lead screws are constrained by top-mounted pillow blocks, eliminating vibration and "whip" at high travel speeds.
* **Self-Locking Kinematics:** By utilizing low-start (1 or 2-start) lead screws, the gantry remains stationary upon power-loss, preventing accidental drops without the need for electromagnetic brakes.

### 💎 Engineering-Grade Build Standards
Designed for high-duty cycle operation in heated environments:
* **Z-Axis Thermal Coupling:** Z-motors are mounted in direct contact with the 4040 base frame using ASA "L-Brackets" and M8 hardware, utilizing the chassis as a primary heat sink.
* **High-Temp A/B Configuration:** XY motors are **Class H rated (180°C)** and top-mounted on the 2040 Y-rails to isolate motion components from the highest heat zones.
* **Long-Shaft Support:** A/B motor shafts are supported by secondary outboard bearings within the XY joints to counteract the lateral tension of the 9mm belt system.

### 🌡️ Thermal Management & Chamber
The **Voron Rex** is engineered for high-ambient temperatures required for Nylon, Polycarbonate, and ASA:
* **Forced Convection Heating:** Integrated under-bed cooling fans act as a heat exchanger, actively moving energy from the bed heater into the chamber air for faster soak times.
* **Structural Heat-Sinking:** All Z-axis and A/B motors are directly coupled to the aluminum frame, utilizing the chassis as a massive passive heat sink.
* **Reflective Insulation:** Rear and bottom panels feature foil-faced insulating barriers (Reflectix) to minimize radiant heat loss.
* **Thermal Break Construction:** A 4mm air gap is maintained between the primary 4040 frame and the stressed-skin enclosure, providing an integrated thermal buffer.

### 🧪 Material & Construction Standards
* **ASA Primary Components:** All structural elements—including the custom 4040 XY joints—are printed in **ASA** for superior dimensional stability and heat resistance.
* **Stressed-Skin Enclosure:** Enclosure panels are integrated as structural members, significantly increasing the torsional rigidity of the 4040 frame.
* **Carbon Fiber X-Beam:** A 20mm square CF tube minimizes moving mass on the X-axis to allow for higher accelerations despite the beefier 9mm hardware.

---

## 🔧 Stealthchanger Integration
Designed for seamless multi-material printing, the **Stealthchanger** "Garage" is mounted to the top of the frame. The **9mm belt path** and integrated end-shaft bearing supports were specifically chosen to handle the extra mass of the toolchanger shuttle and the high-tension requirements of rapid tool swaps.

---

## 📂 Repository Structure
* **/STL:** Modified Voron-spec parts for 4040/2040 frame mounting and 9mm belt clearance.
* **/Config:** Klipper configuration files for the BTT Manta M8P V2.0.
* **/CAD:** Source files for custom XY joints and Stealthchanger modifications.

---

## 🤝 Acknowledgments
* The **Voron Design** team for the foundational kinematics and documentation.
* The **Stealthchanger** community for the tool-changing ecosystem.
* **Formbot** for the "Heavy Metal" T-Rex donor frame that made this tank of a printer possible.
