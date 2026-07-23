# AI-Powered Driver Fatigue Detection System

![Left View](/images/Glasses-LeftView) ![Front view](/images/Glasses-FrontView) ![Right View](/images/Glasses-RightView) 

## Overview

This project was developed as my final-year Bachelor of Information Technology capstone project at Belgium Campus iTversity.

The goal of the project was to create a wearable driver fatigue detection system that could identify signs of drowsiness and alert the driver before an accident occurs. The solution uses smart glasses fitted with sensors to monitor eye closure and head movement, then provides real-time alerts when fatigue is detected.

The project combines embedded systems, IoT, mobile connectivity, and AI concepts to create a working prototype focused on improving road safety.

---

## The Problem

Driver fatigue is a major cause of road accidents. Many existing solutions are either expensive, vehicle-specific, or rely heavily on camera systems.

The aim of this project was to investigate whether a lightweight and affordable wearable device could monitor signs of drowsiness and provide immediate feedback to the driver.

---

## The Solution

The system uses a combination of sensors mounted on a pair of smart glasses:

- TCRT5000 IR sensor to detect prolonged eye closure
- MPU6050 IMU sensor to detect head movements associated with fatigue
- ESP32-S3 microcontroller to process sensor data
- Piezo buzzer and vibration motor to provide immediate alerts to the driver
- Bluetooth Low Energy (BLE) to communicate with a companion Android application

When signs of drowsiness are detected, the glasses immediately alert the driver through vibration and sound. At the same time, the ESP32 sends a notification via BLE to the Android application. The Android application then connects to the vehicle via Bluetooth and plays audible warning messages through the car's speakers, providing an additional layer of alerting without requiring the driver to look at their phone.

---

## My Role

I served as the project leader for an 8-member team throughout the development of the project.

My responsibilities included:

- Planning project milestones and deliverables
- Coordinating team activities
- Assigning and tracking tasks
- Managing timelines and project progress
- Assisting with hardware and software integration
- Supporting testing and troubleshooting

Alongside the leadership responsibilities, I also contributed to the technical development of the solution.

---

## Technologies Used

### Hardware
- ESP32-S3
- TCRT5000 IR Sensor
- MPU6050 IMU
- Piezo Buzzer
- Vibration Motor
- Lithium-Ion Battery
- TP4056 Charging Module
- Boost Converter

### Software
- PlatformIO
- Arduino Framework
- C++
- Android
- Bluetooth Low Energy (BLE)
- TensorFlow Lite Micro (Research and Experimentation)

---

## Repository Contents

This repository contains:

- Project planning documentation
- System architecture and design information
- Project reports
- Demonstration video
- Supporting project resources

> **Note:** The original source code for this project was unfortunately lost after the project was completed. This repository has been created to preserve the project's documentation, design decisions, system architecture, and a full demonstration of the completed prototype.

---

## Project Walkthrough

The walkthrough video included in this repository provides a complete overview of the project, including:

- The overall project architecture and system design
- A walkthrough of the codebase and how each component was implemented
- Hardware architecture diagrams explaining how the sensors, ESP32, Android application, and vehicle communicate with one another
- Software architecture diagrams covering the technology stack and the purpose of each software component
- A live demonstration of the completed prototype detecting driver fatigue and triggering alerts through the smart glasses, Android application, and the vehicle's speakers

---

## Key Features

- Real-time eye closure detection
- Head movement monitoring
- Wearable smart glasses design
- Immediate vibration and audible alerts
- Bluetooth Low Energy communication
- Android companion application
- Vehicle speaker integration via Bluetooth
- Modular hardware and software architecture

---

## Key Skills Demonstrated

- Project Leadership
- Team Coordination
- Embedded Systems Development
- Internet of Things (IoT)
- Mobile Application Integration
- Bluetooth Low Energy (BLE)
- Hardware and Software Integration
- Artificial Intelligence Concepts
- Problem Solving
- Testing and Troubleshooting

---

## Future Improvements

If I were to continue developing the project, I would explore:

- More advanced AI models for fatigue detection
- Improved sensor accuracy and calibration
- Cloud-based monitoring and analytics
- Integration with vehicle infotainment systems
- Enhanced Android application features
- Data logging for long-term driver behaviour analysis

---

## Project Status

✅ Completed as a final-year Bachelor of Information Technology capstone project at Belgium Campus iTversity.
