# Window Cleaning Robot

## Project Overview

This repository contains the project report and related documentation for the **Smart Window Cleaning Robot**, developed as a final year project for the Bachelor of Technology in Electronics & Telecommunication Engineering at Yeshwantrao Chavan College of Engineering, Nagpur, during the academic year 2023-2024. The project aims to design an autonomous robot capable of cleaning windows, including hard-to-reach areas and sliding window channels, with enhanced efficiency, safety, and environmental sustainability.

The robot integrates advanced robotics, including a high-power BLDC motor for adhesion, wheeled locomotion, and a microfiber cloth for wet and dry cleaning. It features smart power management, a user-friendly interface for remote control via mobile devices, and environmentally friendly cleaning solutions.

## Team

- **Students**:
  - Anushka Gupta
  - Chirag Deshbhratar
  - Jay Charde
  - Lalit Deshbhratar
  - Yash Pimparade
- **Guide**: Dr. Sachin S. Khade
- **Institution**: Yeshwantrao Chavan College of Engineering, Nagpur

## Features

- **Climbing Mechanism**: Utilizes a BLDC motor (2200kV, 24000 RPM) with a propeller or Electric Duct Fan (EDF) to create suction for adhesion to vertical glass surfaces.
- **Locomotion**: Four N20 micro gear motors (20 RPM, high torque) with rubber-grip wheels for stable movement.
- **Cleaning Functions**: Supports both wet and dry cleaning with a microfiber cloth, addressing dust accumulation in sliding window channels.
- **Power Management**: Powered by a 7.4V LiPo battery (2200mAh, 30C) with a 40A ESC for efficient energy usage.
- **Control System**: Arduino Uno as the main controller, with an ESP32 for wireless control and a servo tester for manual motor testing.
- **Structure**: Lightweight chassis and components made of PLA filament via 3D printing, with an approximate weight of 1.5 kg.
- **User Interface**: Mobile app integration for scheduling and remote monitoring.
- **Environmental Benefits**: Reduces reliance on chemical cleaning agents, promoting eco-friendly operations.

## Repository Contents

- **Report.pdf**: The complete project report, including:
  - Title page, certificate, declaration, and acknowledgments
  - Table of contents, list of tables, and figures
  - Abstract and detailed chapters on introduction, construction, working mechanism, work done, results, discussions, conclusions, and references
- **README.md**: This file, providing an overview of the project and repository.

## Project Structure

The project report is organized as follows:

1. **Introduction**: Discusses the need for automated window cleaning, challenges with traditional methods, and the objectives of the Smart Window Cleaning Robot.
2. **Construction & Working**:
   - Design and construction details, including the climbing mechanism and locomotion.
   - Working mechanism, featuring advanced algorithms and Wi-Fi connectivity.
   - Testing, validation, benefits, and technological features.
3. **Work Done**: Describes the development process, including two prototype models:
   - **Model 1**: Used a 2000kV BLDC motor with a 22-blade EDF for suction, powered by an 11.1V LiPo battery.
   - **Model 2**: Improved with a 3-blade propeller, 7.4V LiPo battery, and 20 RPM N20 motors for enhanced torque and adhesion.
4. **Results, Discussions & Conclusions**:
   - Experimental results showing the robot’s ability to maneuver on vertical and inclined surfaces (up to 45°).
   - Specifications: 1.5 kg weight, 20 cm x 13 cm dimensions, 45-minute runtime, and 7.4V operation.
   - Discussions on efficiency, cost savings, safety, and environmental benefits.
   - Future improvements, including enhanced sensors and obstacle navigation.
5. **Literature Cited**: References to relevant research on window-cleaning robots and climbing mechanisms.

## Specifications

| Component | Details |
|-----------|---------|
| **Weight** | ~1.5 kg |
| **Dimensions** | 20 cm (L) x  13 cm (W) |
| **Battery** | 7.4V LiPo, 2200mAh, 30C |
| **Motors** | 1x BLDC (2200kV, 24000 RPM), 4x N20 (20 RPM, 1.5 kg-cm torque) |
| **ESC** | ReadyToSky 40A, supports 2-4S LiPo |
| **Chassis** | PLA filament (3D printed) |
| **Cleaning Material** | Microfiber cloth |
| **Control** | Arduino Uno, ESP32 (Wi-Fi), Servo Tester |
| **Runtime** | ~45 minutes |
| **Current Consumption** | Motors: 3A max, Control System: 2A |

## Installation and Usage

This repository primarily contains the project report. To replicate or further develop the robot:

1. **Hardware**:
   - Procure components listed in the specifications (BLDC motor, N20 motors, LiPo battery, ESC, Arduino Uno, ESP32, etc.).
   - Assemble the chassis using 3D-printed PLA parts based on the designs in the report.
   - Connect motors, ESC, and battery as described in the "Work Done" section.

2. **Software**:
   - Program the Arduino Uno for motor control and movement logic (refer to the report for basic programming details).
   - Configure the ESP32 for Wi-Fi-based remote control.
   - Use a servo tester for manual testing of motors and ESC.

3. **Testing**:
   - Test the robot on smooth vertical glass surfaces and inclined surfaces (up to 45°).
   - Validate adhesion, locomotion, and cleaning efficiency as outlined in the report.

## Future Work

- **Enhanced Adhesion**: Optimize the gripping mechanism to reduce noise and improve efficiency on multi-level windows.
- **Sensor Integration**: Add touch or light sensors for obstacle detection (e.g., window grills).
- **Autonomous Navigation**: Upgrade path-planning algorithms for fully autonomous operation.
- **Performance Testing**: Evaluate maximum speed, load capacity, and current consumption under varying conditions.

## Acknowledgments

We express our gratitude to:
- **Dr. Sachin S. Khade** for his guidance and expertise.
- **Dr. M.S. Narlawar**, Head of the Electronics & Telecommunication Engineering Department, for providing facilities.
- Faculty members, friends, and peers for their support and suggestions.

## License

This project is for academic purposes and is not licensed for commercial use. Please contact the authors or Yeshwantrao Chavan College of Engineering for permissions related to usage or modification.

## Contact

For inquiries, please contact the project team via Yeshwantrao Chavan College of Engineering, Nagpur.
