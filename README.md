# Robot Rabbit (Simple two joint mechanical arm)

A beginner-friendly robotic arm with rabbit-ear-inspired grippers, designed to introduce students to mechanical design and mechatronics through hands-on learning.

## Robot Rabbit in Action

![Robot Rabbit Demo](media/Robot%20Rabbot.gif)

## Overview

Robot Rabbit is a compact robotic arm designed to pick up objects of different sizes and move them from one location to another.

The robot combines custom 3D-printed components, two servo motors, an ESP32 development board, and a Raspberry Pi. The project explores mechanical design, embedded systems, and robotic manipulation through a practical, hands-on approach.

## Key Features

- Two-joint mechanical arm for object manipulation.
- Rabbit-ear-inspired gripper designed to handle objects of different sizes.
- Custom 3D-printed mechanical components.
- Servo-based actuation.
- Raspberry Pi and ESP32-based control system.
- Educational design for students interested in robotics and mechatronics.

## 3D Models

The following STL files contain the main 3D-printable components of the robot.

| Part | STL File | Description |
|---|---|---|
| Base | [base.stl](cad/base.stl) | Supports the main robot structure |
| Arm | [arm.stl](cad/arm.stl) | Main mechanical arm |
| Head | [head.stl](cad/head.stl) | Upper mechanical assembly |

### 3D Printing

- File format: STL
- Material: PLA (Polylactic Acid)
- Printing method: Fused Deposition Modeling (FDM)
- Slicer software: Cura, PrusaSlicer, or another compatible slicer

Import the STL files into a slicer to prepare the components for printing.

## Hardware and Components

| Component | Quantity | Estimated Cost (USD) |
|---|---:|---:|
| 3D-printed parts (PLA) | 4 models | $1 to $3 |
| Micro servo motors | 2 | $10 to $20 |
| ESP32 development board with OLED display | 1 | $10 to $19 |
| Raspberry Pi | 1 | $44 to $140 |
| Screws and bolts | 12 | $1 to $3 |

## Estimated Build Cost

The estimated cost of the main components is approximately **$66 to $185**.

The total depends on the selected hardware models and component suppliers. The estimate excludes the 3D printer, tools, shipping, and additional accessories or power supplies.

## Assembly Guide

1. Print the base, arm, head, and additional component using the provided STL files.
2. Prepare the servo motors, screws, bolts, and electronic components.
3. Assemble the 3D-printed structural components.
4. Install the servo motors in their designated mounts and connect the mechanical linkages.
5. Connect the servo motors to the ESP32 and integrate the Raspberry Pi with the control system.
6. Install the Python scripts on the Raspberry Pi.
7. Test the joint movements and verify that the gripper can pick up and move objects.

## Software and Control

Robot Rabbit uses a Raspberry Pi and an ESP32-based control system. Python scripts run on the Raspberry Pi for high-level control, while the ESP32 handles servo actuation.

### Raspberry Pi Python Scripts

| File | Description |
|---|---|
| [script1.py](raspberry_pi/script1.py) | Main robot control script |
| [script2.py](raspberry_pi/script2.py) | Supporting control functionality |

The Python scripts are located in the `raspberry_pi` directory.

## Future Improvements

- Improve the gripper mechanism and object-handling capabilities.
- Add detailed assembly photographs and wiring instructions.
- Expand the control software and communication features.
- Publish additional mechanical design documentation.

## Additional Projects

Explore more robotics and 3D-printing projects on my [GitHub profile](https://github.com/0xD0M1M0).

## Contact

For questions, suggestions, or project improvements, you may email me: 

## Disclaimer

This project is provided for educational and experimental purposes. Anyone building, modifying, or operating the robot is responsible for ensuring safe mechanical assembly, electrical connections, and operation. The author is not responsible for damage, injury, or losses resulting from the construction or use of this project.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
