<h1 align="center">🦖 Voron Rex</h1>
<p align="center"><strong>A High-Rigidity 4040 "Flying Gantry" Toolchanger Conversion</strong></p>

---

## 📝 Project Overview

**Voron Rex** is a heavy-duty conversion project that transforms a **Formbot T-Rex V1** into a high-performance CoreXY machine. By marrying the massive 4040/2040 frame of the T-Rex with the sophisticated kinematics of the Voron ecosystem, this build achieves a unique balance of industrial rigidity and modern tool-changing capabilities.

This project is a high-rigidity **Flying Gantry CoreXY** 3D printer utilizing 4040 aluminum extrusions and a stressed-skin enclosure. The motion system features a **Quad-NEMA17 independent Z-axis** driven by leadscrews with top pillow blocks, enabling **Quad Gantry Leveling (QGL)** with superior mechanical positioning.

---

## ⚙️ Technical Specifications

| Component | Specification |
| :--- | :--- |
| **Donor Chassis** | Salvaged 4040/4080 Aluminum (Formbot T-Rex V1) |
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
By using four independent lead screws instead of the traditional Voron 2.4 belts, the **Voron Rex** eliminates gantry sag and provides a rock-solid foundation for the tool-changing process. The top-mounted pillow blocks ensure the screws remain constrained and aligned under load, even with a heavy toolchanger payload.

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
