# Rope Climbing Robot

A robotic system designed to autonomously climb ropes using 3D-printed components and motorized mechanisms.

## Overview

This project features a rope climbing robot with a modular body assembly, utilizing 3D printing technology with PLA or PETG materials for structural components. The robot is powered by 12V motors with H-bridge motor driver control.

## Assembly Instructions

### 3D Printed Components

Print the following STL files (without circuit cover):

| Component | Quantity | Infill |
|-----------|----------|--------|
| Back Body 1 Motor Placement | 1 | 10% |
| Front Body 1 Motor Placement | 1 | 10% |
| Front Body 2 Groove Wheel | 1 | 10% |
| Back Body 2 Groove Wheel | 1 | 10% |
| Motorised Pulley Wheel | 1 | 10% |
| Top Flat | 1 | 10% |
| Groove Wheel | 2 | 10% |

### Hardware Components

#### M3 Body Pins
- **8x** M3 Body Pin (longer variant)

#### Screws and Fasteners
- **2x** M3 Screw (10-20 mm) - Body assembly
- **4x** M3 Screw (50 mm) with nuts - Copper pipe connections
- **2x** M4 Screw (70 mm) - Front 2 and Back 2 body connections

#### Motors and Electronics
- **Motor:** 12V 107 RPM
- **Motor Driver:** BTS7960 H-Bridge Motor Driver

*See the BOM (Bill of Materials) file for complete electronic components and specifications.*

## Assembly Steps

1. **Prepare 3D Printed Parts**
   - Ensure all printed components are cleaned and deburred
   - Verify proper fit of all mating surfaces

2. **Body Assembly**
   - Connect Back Body 1 and Back Body 2 using the M3 body pins
   - Connect Front Body 1 and Front Body 2 using the M3 body pins

3. **Copper Pipe Connection**
   - Position the two body halves on the copper pipe
   - Secure using 4x M3 50mm screws with nuts

4. **Cross Body Connection**
   - Connect front and back body sections using 2x M4 70mm screws

5. **Motor and Pulley Assembly**
   - Mount the 12V 107 RPM motor
   - Install the motorised pulley wheel
   - Install groove wheels for rope tension and grip

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
- **H-Bridge Control:** Precise motor speed and direction control via BTS7960 driver

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
2. Print components with recommended 10% infill
3. Gather all hardware components listed in the BOM
4. Follow the assembly steps sequentially
5. Test motor operation before full deployment on rope

## Notes

- Ensure M3 and M4 fasteners are properly torqued but not over-tightened
- Verify motor rotation direction after assembly
- Test rope climbing functionality on a secured test rope before deployment

---

For questions or contributions, please refer to the project documentation or create an issue in the repository.
