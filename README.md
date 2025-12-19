# Gesture-Based Touchless IoT Control

An AI-powered gesture recognition system using **ESP32-CAM** for **touchless control of IoT devices**.  
The system enables users to control appliances using hand gestures without physical contact.

---

## Overview

This project demonstrates a touchless IoT control mechanism where hand gestures are captured using an ESP32-CAM module, processed in real time, and mapped to control commands for IoT devices such as lights or fans.  
It is designed for smart homes, healthcare environments, and assistive technologies.

---

## Key Features

- Touchless control of IoT devices using hand gestures  
- ESP32-CAM based vision sensing  
- Real-time gesture recognition  
- Lightweight and low-cost embedded implementation  
- Suitable for smart homes and assistive environments  

---

## System Architecture

The system consists of:
- ESP32-CAM for image capture  
- Gesture recognition logic  
- IoT control module (relay / cloud / MQTT)  
- End device (appliance)  

> The system architecture diagram is available in the `assets/` folder.

---

## How It Works

1. ESP32-CAM captures live video frames  
2. Frames are processed to detect hand gestures  
3. Recognized gestures are mapped to predefined actions  
4. Control signals are sent to IoT devices wirelessly  
5. Devices respond instantly without physical contact  

---

## Project Structure

```text
gesture-based-touchless-iot-control/
├── src/
│   ├── esp32_cam_gesture.ino
│   ├── gesture_inference.py
│   └── mqtt_control.py
├── assets/
│   └── architecture.png
├── README.md
└── requirements.txt
