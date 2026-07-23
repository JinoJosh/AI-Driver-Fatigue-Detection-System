# AI-Powered Driver Fatigue Detection System

## Overview

This project was developed as my final-year Bachelor of Information Technology capstone project at Belgium Campus iTversity.

The goal of the project was to create a wearable driver fatigue detection system that could identify signs of drowsiness and alert the driver before an accident occurs. The solution uses smart glasses fitted with sensors to monitor eye closure and head movement, then provides real-time alerts when fatigue is detected.

The project combined embedded systems, IoT, mobile connectivity, and AI concepts to create a working prototype focused on improving road safety.

---

## The Problem

Driver fatigue is a major cause of road accidents. Many existing solutions are either expensive, vehicle-specific, or rely heavily on camera systems.

The aim of this project was to investigate whether a lightweight and affordable wearable device could be used to monitor signs of drowsiness and provide immediate feedback to the driver.

---

## The Solution

The system uses a combination of sensors mounted on a pair of glasses:

- An IR sensor to detect prolonged eye closure
- An MPU6050 IMU sensor to detect head movements associated with fatigue
- An ESP32-S3 microcontroller to process sensor data
- A vibration motor and buzzer to alert the driver
- Bluetooth Low Energy (BLE) to communicate with an Android application

When the system detects signs of drowsiness, it immediately alerts the driver through vibration and sound while also sending a notification to the mobile application.

---

## My Role

I served as the project leader for an 8-member team throughout the development of the project.

My responsibilities included:

- Planning project milestones and deliverables
- Coordinating team activities
- Assigning and tracking tasks
- Managing timelines and project progress
- Assisting with hardware and software integration
- Supporting testing and troubleshooting efforts

Alongside the leadership responsibilities, I also contributed to the technical development of the solution.

---

## Technologies Used

- ESP32-S3
- PlatformIO
- Arduino Framework
- C++
- Bluetooth Low Energy (BLE)
- Android
- MPU6050 IMU
- TCRT5000 IR Sensor
- TensorFlow Lite Micro (Research and Experimentation)

---

## Repository Contents

This repository contains:

- Project planning documentation
- System architecture and design information
- Project reports
- Demonstration videos
- Supporting project resources

> **Note:** The original source code for the project was unfortunately lost after the project was completed. This repository has been created to preserve the project's documentation, design decisions, architecture, and demonstration of the working prototype.

---

## Demonstration

The demonstration video included in this repository showcases:

- The project architecture
- Hardware setup
- Live fatigue detection
- Bluetooth communication with the Android application
- A walkthrough of the implementation
- The working prototype in action

---

## Key Skills Demonstrated

- Project Leadership
- Team Coordination
- Embedded Systems Development
- Internet of Things (IoT)
- Mobile Integration
- Bluetooth Communication
- Hardware and Software Integration
- Problem Solving
- Testing and Troubleshooting

---

## Future Improvements

If I were to continue developing the project, I would explore:

- More advanced fatigue detection models
- Improved sensor accuracy
- Cloud-based monitoring and analytics
- Integration with vehicle infotainment systems
- Enhanced mobile application features
