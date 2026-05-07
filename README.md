# Rope Climbing Robot

A robotic system designed to autonomously climb ropes using 3D-printed components and motorized mechanisms.

## Overview

This project features a rope climbing robot with a modular body assembly, utilizing 3D printing technology with PLA or PETG materials for structural components. The robot is powered by 12V motors with H-bridge motor driver control.

## Assembly Instructions

### 3D Printed Components

Print the following STL files (without circuit cover):

| Component | Quantity | Infill |
|-----------|----------|--------|
| Back Body 1 Motor Placement | 1 | 15% |
| Front Body 1 Motor Placement | 1 | 15% |
| Front Body 2 Groove Wheel | 1 | 15% |
| Back Body 2 Groove Wheel | 1 | 15% |
| Motorised Pulley Wheel | 1 | 10% |
| Top Flat | 1 | 10% |
| Groove Wheel | 2 | 10% |
| M3 Body Pin Longer | 8 | 15% |
| Motor extension V3 | 8 | 25% |


#### Screws and Fasteners
- **2x** M3 Screw (10-20 mm) - Body assembly
- **4x** M3 Screw (50 mm) with nuts - Copper pipe connections
- **2x** M4 Screw (70 mm) - Front 2 and Back 2 body connections

#### Motors and Electronics
- **Motor:** 12V 107 RPM or 12V 200RPM
- **Motor Driver:** BTS7960 H-Bridge Motor Driver
- **Battery:** 12V 2400mAh NI-MH Rechargeable Battery with KET 2P Connection
- **LED:** 2 x (Red, Green) 
- **Passive Buzzer** 
- **Microcontroller:** Arduino nano 
- **Fuse:** L-12 Fuse Lamp 8V 250mA light Bulb or 10mA Fuse 
- **Switch:** 2 Push bottoms that can change the task of robot 


*See the BOM (Bill of Materials) file for complete electronic components and specifications and link to the UK components*

## Assembly Steps

1. **Prepare 3D Printed Parts**
   - Ensure all printed components are clean
   - Verify proper fit of all mating surfaces

2. **Body Assembly**
   - Connect Front body 1 and Back body 1 using M3 screw of 20mm length 
   - Connect Front Body 2 and Back Body 2 using the M4 (50mm/70mm length). Make sure to put 2 big groove wheel in Body 2 before adding the scews. 

3. **Cross Body Connection**
   - Connect front and back body sections using 4x M4 70mm screws

5. **Motor and Pulley Assembly**
   - Mount the 12V 107 RPM motor on back Body 1. 
   - Install the motorised pulley wheel with the motor extension V3 inside
   - Cover all the wheels with non-slip mat cut off for better grip

6. **Electronics Integration**
   - Install BTS7960 H-Bridge Motor Driver
   - Connect motor power and control circuits per BOM specifications
   - Mount circuit components as specified in electronic assembly guide

## Bill of Materials (BOM)

Refer to the BOM document for a complete list of all electronic components and specifications.

## Design Features

- **Lightweight Construction:** 3D-printed PLA/PETG components reduce overall weight
- **Modular Assembly:** Separate front and back body sections allow for easy maintenance and customization
- **Efficient Drive System:** Motorised pulley with groove wheels for secure rope grip

## Project Structure

```
Rope_Climbing_Robot/
├── STL_Files/           # 3D printable model files
├── Electronics/         # Motor driver and control schematics
├── BOM.md              # Bill of materials
├── Assembly_Guide/     # Detailed assembly documentation
└── README.md           # This file
```

## Getting Started

1. Review and prepare all STL files for 3D printing
2. Print components 
3. Gather all hardware components listed in the BOM
4. Follow the assembly steps sequentially
5. Test motor operation before full deployment on rope

## Notes

- Ensure M3 and M4 fasteners are properly torqued but not over-tightened
- Verify motor rotation direction after assembly
- Test rope climbing functionality on a secured test rope before deployment

---

For questions or contributions, please refer to the project documentation or create an issue in the repository.
