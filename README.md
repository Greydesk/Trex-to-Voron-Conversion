# Trex-to-Voron-Conversion
Voron Rex
A High-Rigidity 4040 "Flying Gantry" Toolchanger Conversion
Voron Rex is a heavy-duty conversion project that transforms a Formbot T-Rex V1 into a high-performance CoreXY machine. By combining the massive 4040/2040 frame of the T-Rex with the sophisticated kinematics of the Voron ecosystem, this build achieves a unique balance of industrial rigidity and modern tool-changing capabilities.
🛠 Project Architecture
The core of the Voron Rex is a 350mm³ Flying Gantry system. Unlike the standard Voron 2.4 (belt-driven Z) or the Trident (moving bed), the Rex utilizes a quad-lead-screw driven gantry to achieve Quad Gantry Leveling (QGL) with the superior mechanical positioning and "stay-put" reliability of lead screws.
Technical Specifications
ComponentSpecification
Donor ChassisSalvaged 4040/4080 Aluminum (Formbot T-Rex V1)
EnclosureStressed-skin panels for maximum frame rigidity
Z-AxisQuad-NEMA17 Independent Lead-Screws w/ Top Pillow Blocks
X-AxisUltra-lightweight 2020 Carbon Fiber w/ MGN9H Rail
Y-Axis2040 Aluminum Extrusions w/ MGN9H Rails
Drive Train9mm GT2 Belts + High-Torque Long-Shaft NEMA17s
Tool SystemStealthchanger Ecosystem w/ Top-Mounted "Garage"
ToolheadStealthburner (or compatible)
ControllerBTT Manta M8P (V2.0) + CB1/CM4
CommunicationFull CANbus (Nitehawk-Hexa / EBB36)
🚀 Key Design Features
Quad-Z Lead Screw Gantry
By using four independent lead screws, the Voron Rex eliminates gantry sag and provides a rock-solid foundation for the tool-changing process. The top-mounted pillow blocks ensure the screws remain constrained and aligned under load.
Stealthchanger Integration
Designed for multi-material and multi-functional printing, the "Garage" is mounted to the top of the frame. The 9mm belt path was specifically chosen to compensate for the additional mass of the toolchanger shuttle and the high-tension requirements of rapid tool swaps.
Advanced Motion & Electronics
Carbon Fiber X-Beam: Minimizes moving mass on the X-axis to allow for higher accelerations despite the 9mm hardware.
Integrated Bearing Supports: Custom XY joints feature end-shaft bearing support for the long-shaft NEMA17 motors, preventing shaft flex under high belt tension.
Custom Top-Hat: A specialized enclosure extension provides the necessary clearance for toolhead umbilicals at maximum Z-travel.
📂 Repository Structure
/STL: Modified Voron-spec parts for 4040/2040 frame mounting and 9mm belt clearance.
/Config: Klipper configuration files for the BTT Manta M8P V2.0.
/CAD: Source files for custom XY joints and Stealthchanger modifications.
🤝 Acknowledgments
The Voron Design team for the foundational kinematics and documentation.
The Stealthchanger community for the tool-changing ecosystem.
Formbot for providing the "Heavy Metal" T-Rex donor frame.
