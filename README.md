# Design-and-Development-of-a-Height-Adjustable-Washbasin-for-Wheelchair-Users
- Bachelor’s Thesis (B.Eng. in Mechatronics)

- Height-Adjustable Washbasin for Wheelchair Users
* Project Overview

- This mechatronic system was designed to enhance the quality of life for people with physical disabilities, children, and the elderly.
- The project solves the problem of standard, fixed-height washbasins, which are often inaccessible to wheelchair users.
- A key feature is the vertical adjustability, allowing the basin to be lowered for tasks like foot washing or raised for standard use.
- This project was my Bachelor’s Thesis (B.Eng. in Mechatronics) at Al-Azhar University, which served as a foundation for my current M.Sc. in Mechatronics and Robotics at Frankfurt University of Applied Sciences.

* Key Features

- Vertical Motion Mechanism: Converts rotary motor motion into precise linear displacement.
- Automated Control: PIR sensor-based user detection for touchless valve operation.
- Dual Operation: Manual override via pushbutton and DPDT switches.
- Safety Integrated: Physical isolation of water and electronic systems to prevent electrical hazards.
- Cost-Effective Design: Built using affordable components like fiberglass for the basin and standard DC actuators.

* Technical Specifications

** Electronics & Control_

- Microcontroller: Arduino UNO.
- Actuation Logic:
- Water Valve: Controlled via an Arduino digital pin (12) driving a TIP120 Darlington Transistor to actuate a 24V Solenoid Valve.
- Vertical Movement: Powered by a 24V DC Motor.
- Sensor Suite:
- PIR Motion Sensor for hands-free water activation.
- Limit Switches (SW2, SW3) integrated into the circuit to safely bound the vertical movement and prevent mechanical overtravel.
- Manual Control: A DPDT Switch allows the user to manually control the direction of the vertical movement.

* Mechanical Design

- Power Transmission: A Lead Screw mechanism is used to achieve smooth linear vertical motion.
- CAD Modeling: The structure and assembly were designed and analyzed in SolidWorks.

* Software

- Environment: Arduino IDE (C++).
- Simulation: The entire circuit logic was validated using Proteus before physical assembly.

# Repository Structure
- /src: Contains the Arduino source code.
- /hardware: Proteus circuit diagrams and component schematics.
- /design: Screenshots of the SolidWorks 3D models and mechanical assembly.
- /docs: The original project poster.

# Results
- The final prototype successfully demonstrated a functional, automated, and adjustable basin. It provides a reliable solution for household accessibility, ensuring comfort and dignity for users with limited mobility.
