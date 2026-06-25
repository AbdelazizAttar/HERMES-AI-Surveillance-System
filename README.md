# HERMES – Intelligent Mobile Robot for Smart Home Surveillance and Environmental Monitoring

HERMES is a final-year engineering project focused on the design and development of an autonomous mobile robot for smart home environments. The system combines robotics, embedded systems, computer vision, artificial intelligence, and IoT technologies to provide active surveillance, environmental monitoring, and intelligent user interaction.

Unlike traditional fixed surveillance systems, HERMES is capable of moving autonomously within the home, avoiding obstacles, detecting and tracking users through computer vision, monitoring environmental conditions such as temperature, humidity, and gas levels, and providing real-time alerts and remote supervision through a web interface.

The project is based on a distributed architecture combining a Raspberry Pi 4 for high-level processing tasks and ESP32 microcontrollers for real-time control, resulting in a modular, scalable, and cost-effective smart home robotic platform.

<p align="center">
  <img width="450" alt="HERMES Robot" src="https://github.com/user-attachments/assets/a9cf7db8-3c15-4916-9bbe-e9ee9b468207" />
</p>

---

## Project Overview

HERMES is an autonomous intelligent robot designed to enhance smart home security, environmental monitoring, and human-robot interaction. The platform integrates Artificial Intelligence, Computer Vision, Robotics, and IoT technologies to provide a complete mobile surveillance solution capable of autonomous navigation, facial tracking, environmental sensing, and real-time alert generation.

The system was developed using a distributed architecture where a Raspberry Pi 4 performs high-level processing tasks such as computer vision, facial tracking, and decision-making, while multiple ESP32 microcontrollers manage real-time operations including locomotion, sensor acquisition, robotic head control, and communication.

---

## Key Features

- Autonomous 4WD mobile navigation
- Obstacle detection and avoidance
- Real-time face detection and tracking
- Pan/Tilt robotic head movement
- Environmental monitoring
- Gas and smoke detection
- Temperature and humidity monitoring
- Live video surveillance
- Smart home supervision
- Real-time Telegram notifications and alerts
- Remote monitoring through a web dashboard
- Distributed Raspberry Pi and ESP32 architecture
- Modular and scalable embedded system design

---

## System Architecture

HERMES adopts a modular and distributed architecture designed to maximize performance, scalability, reliability, and maintainability.

### Raspberry Pi 4

The Raspberry Pi 4 acts as the central processing unit of the robot and is responsible for:

- Computer Vision processing
- Face detection and tracking
- Artificial Intelligence algorithms
- System supervision
- Communication management
- Data processing and decision-making

### ESP32 Master Controller

Responsible for:

- Locomotion control
- Motor management
- Obstacle avoidance
- Embedded web server
- Wi-Fi communication

### ESP32 Head Controller

Responsible for:

- Pan/Tilt movement
- Camera orientation
- Visual target tracking
- Head positioning control

### ESP32 Security Controller

Responsible for:

- Environmental monitoring
- Gas and smoke detection
- Temperature and humidity acquisition
- Safety monitoring
- Alert generation

### ESP32-CAM Module

Responsible for:

- Secondary video surveillance
- Remote visual monitoring
- Image acquisition

---

## Hardware Components

| Component | Function |
|------------|----------|
| Raspberry Pi 4 (4GB RAM) | Main processing unit |
| ESP32-WROOM-32D | Motor and locomotion control |
| ESP32-CAM | Secondary video surveillance |
| MQ-2 Sensor | Gas and smoke detection |
| DHT11 Sensor | Temperature and humidity monitoring |
| HC-SR04 Ultrasonic Sensor | Obstacle detection |
| L298N Motor Driver | Motor control |
| JGB37-550 Motors | Robot locomotion |
| USB 8MP Camera | Computer vision and facial tracking |
| 7-Inch Touchscreen Display | Human-machine interface |
| MG996R Servo Motors | Pan/Tilt head movement |
| 3S Li-Ion Battery Pack | Autonomous power supply |
| LM2596 Buck Converter | Voltage regulation |
| BMS Protection Module | Battery protection and management |

---

## Software Stack

### Programming Languages

- Python
- C++
- HTML
- CSS
- JavaScript

### Frameworks and Libraries

- OpenCV
- Flask
- Arduino Framework
- Telegram Bot API

### Development Tools

- Raspberry Pi OS
- Arduino IDE
- Draw.io
- Git
- GitHub

---

## Communication Architecture

The robot relies on multiple communication protocols to ensure reliable and secure data exchange between all system components.

| Communication Link | Protocol |
|-------------------|-----------|
| Raspberry Pi ↔ ESP32 | UART Serial Communication |
| User ↔ Web Dashboard | HTTP |
| ESP32 ↔ Sensors | I2C / Analog Signals |
| Robot ↔ Telegram API | HTTPS |
| Internal Communication | Wi-Fi |

This hybrid communication architecture guarantees low-latency control, secure notifications, and reliable interactions between embedded devices and external services.

---

## Core Functionalities

### Intelligent Surveillance

The robot continuously monitors its environment using onboard cameras and computer vision algorithms, enabling real-time observation and intelligent scene analysis.

### Face Detection and Tracking

Using OpenCV-based computer vision techniques, HERMES can detect human faces and dynamically orient its robotic head to track users in real time.

### Autonomous Navigation

The robot navigates independently using ultrasonic sensors for obstacle detection and avoidance, ensuring safe movement within indoor environments.

### Environmental Monitoring

Dedicated sensors continuously monitor:

- Temperature
- Humidity
- Gas concentration
- Smoke presence

Collected data is analyzed and displayed through the supervision interface.

### Smart Alert System

When dangerous conditions are detected, HERMES automatically sends notifications through Telegram, allowing immediate user intervention.

### Remote Monitoring Dashboard

A web-based dashboard enables users to:

- Monitor sensor values
- View video streams
- Supervise robot status
- Control specific robot functions remotely

---

## Engineering Highlights

- Designed a distributed embedded architecture using Raspberry Pi and multiple ESP32 microcontrollers.
- Implemented autonomous navigation with obstacle avoidance capabilities.
- Developed real-time face detection and tracking functionality.
- Integrated environmental monitoring sensors for smart home safety.
- Built a responsive web dashboard for remote supervision.
- Implemented Telegram-based real-time alert notifications.
- Designed a robust power management system using Li-Ion batteries and BMS protection.
- Developed modular communication interfaces between hardware and software layers.

---

## Project Objectives

The primary goal of HERMES is to develop an intelligent robotic platform capable of assisting users in smart home environments through:

- Autonomous surveillance
- Environmental supervision
- Human-robot interaction
- Real-time monitoring
- Safety enhancement
- Intelligent alert generation

The project demonstrates the integration of Artificial Intelligence, Robotics, Embedded Systems, Computer Vision, and IoT technologies within a unified autonomous platform.

---

## Repository Notice

This repository showcases the architecture, design, hardware integration, documentation, and implementation methodology of the HERMES project.

The complete source code is not publicly available due to project confidentiality and intellectual property considerations.

This repository is intended to present the project's engineering achievements, technical architecture, hardware design, and development process.
