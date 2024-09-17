👋 Hi, I’m @SuyashSolanke,

This repository contains the design files for a 230V AC to 5V DC, 1A power supply created in EasyEDA. 
The power supply is intended to convert high-voltage mains power (230V AC) to a safe, low-voltage output (5V DC) suitable 
for powering microcontrollers, sensors, and other low-power electronic components.

Features:
Input Voltage: 230V AC (mains power)
Output Voltage: 5V DC
Max Output Current: 1A
Small Form Factor: Compact PCB design for easy integration into various projects
Safety Features: Includes protection circuits such as capacitors to ensure safe operation

Schematic and PCB Design:
The design was created using EasyEDA. The schematic captures the entire circuit, including the AC-DC conversion components, voltage regulation, filtering, and protection elements.

Key Components
Bridge Rectifier: Converts AC input to DC.
Capacitors: For smoothing the DC voltage.
Linear Regulator(7805): Steps down the voltage from high DC to 5V.

PCB Layout
The PCB design has been optimized for minimal size while maintaining proper clearance for high-voltage tracks.
Key components like the transformer, bridge rectifier, and filter capacitors are placed to ensure efficient power delivery.
Tracks handling 230V AC have been spaced according to safety standards to prevent arcing.

How to Use This Project

Download the Files:
1) Clone the repository or download the files using the green "Code" button.
2) All key project files are located in the repository including:
    1. Schematic.json (EasyEDA Schematic)
    2. PCB.json (EasyEDA PCB Layout)
    3. Gerber.zip (Manufacturing files for PCB)
    4.  BOM.csv (Bill of Materials)
    5. Images of the design

3) Open in EasyEDA:
    1. Open EasyEDA in your browser.
    2. Import the schematic and PCB .json files to view, modify, or simulate the design.

4) Fabricate the PCB:
Use the provided Gerber files (Gerber.zip) to manufacture the PCB through a PCB fabrication service like JLCPCB or any PCB manufacturer.
Ensure you select the appropriate PCB specifications during the order, such as material, layer count, and copper thickness.

5) Component Assembly:
Refer to the BOM.csv file for a detailed list of components required to build the power supply.
The BOM includes part numbers, values, and package types for easy sourcing.

6) Test and Validate:
Once assembled, carefully test the output voltage using a multimeter to ensure it provides a stable 5V DC output.
Check for any potential short circuits or misbehavior during the initial power-on test.
