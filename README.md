<h1 align="center">🦖 Voron Rex</h1>
<p align="center"><strong>A High-Rigidity 4040 "Flying Gantry" Toolchanger Conversion</strong></p>

---

## 📝 Project Overview

**Voron Rex** is a heavy-duty conversion project that transforms a **Formbot T-Rex V1** into a high-performance CoreXY machine. By marrying the massive 4040 frame of the T-Rex with the sophisticated kinematics of the Voron ecosystem, this build achieves a unique balance of industrial rigidity and modern tool-changing capabilities.

This project is a high-rigidity **Flying Gantry CoreXY** 3D printer utilizing 4040 aluminum extrusions and a stressed-skin enclosure. The motion system features a **Quad-NEMA17 independent Z-axis** driven by leadscrews with top pillow blocks, enabling **Quad Gantry Leveling (QGL)** with superior mechanical positioning.

---

## ⚙️ Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Donor Chassis** | Salvaged 4040 Aluminum (Formbot T-Rex V1) |
| **Gantry Architecture** | Flying Gantry with Quad-Z Lead-screw Drive |
| **X-Axis** | Ultra-lightweight 2020 Carbon Fiber w/ MGN9H Rail |
| **Y-Axis** | 2040 Aluminum Extrusions w/ MGN9H Rails (Voron Arrangement) |
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
* **Self-Locking Kinematics:** By utilizing low-start (1 or 2-start) lead screws, the gantry remains stationary upon power-loss, preventing accidental drops onto the bed without the need for electromagnetic brakes.

### 🌡️ Thermal Management & Engineering Materials
The **Voron Rex** is engineered for high-ambient chamber temperatures required for Nylon, Polycarbonate, and ASA:
* **Structural Heat-Sinking:** All Z-axis and A/B motors are directly coupled to the 4040/2040 aluminum frame, utilizing the chassis as a massive passive heat sink.
* **High-Torque 9mm Drive:** The 9mm belt system allows for lower motor currents while maintaining high holding torque, reducing the thermal load on the A/B motors.
* **Active Cooling Ready:** The rear gantry geometry is designed to support active cooling fans for the A/B motors during long-duration, high-temp prints.
* 
### 🧪 Material & Construction Standards
* **ASA Primary Components:** All structural elements—including the custom 4040 XY joints and Z-carriages—are printed in **ASA**. This provides superior dimensional stability and heat resistance for the internal "stressed-skin" environment.
* **Stressed-Skin Enclosure:** The enclosure panels are integrated as structural members, significantly increasing the torsional rigidity of the 4040 aluminum frame.

### 🔧 Stealthchanger Integration
Designed for seamless multi-material printing, the **Stealthchanger** "Garage" is mounted to the top of the frame. The **9mm belt path** and integrated end-shaft bearing supports for the NEMA17 motors were specifically chosen to handle the extra mass of the toolchanger shuttle and the high-tension requirements of rapid tool swaps.

### ⚡ Advanced Motion & Electronics
*   **Carbon Fiber X-Beam:** Minimizes moving mass on the X-axis to allow for higher accelerations despite the beefier 9mm hardware.
*   **Stressed-Skin Enclosure:** The panels are integrated into the frame design to maximize structural rigidity.
*   **Custom Top-Hat:** A specialized enclosure extension provides the necessary clearance for toolhead umbilicals at maximum Z-travel.

---

## 📂 Repository Structure
*   **/STL:** Modified Voron-spec parts for 4040/2040 frame mounting and 9mm belt clearance.
*   **/Config:** Klipper configuration files for the BTT Manta M8P V2.0.
*   **/CAD:** Source files for custom XY joints and Stealthchanger modifications.

---

## 🤝 Acknowledgments
*   The **Voron Design** team for the foundational kinematics and documentation.
*   The **Stealthchanger** community for the tool-changing ecosystem.
*   **Formbot** for the "Heavy Metal" T-Rex donor frame that made this tank of a printer possible.
