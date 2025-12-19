# Gesture-Based Touchless IoT Control

## Overview
This project implements an AI-powered gesture recognition system for **touchless control of IoT devices** using an **ESP32-CAM**.  
The system enables users to control appliances without physical contact, improving hygiene, accessibility, and user convenience.

Hand gestures are captured using the ESP32-CAM, processed using lightweight computer vision techniques, and mapped to IoT control actions via wireless communication.

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

> System architecture diagram will be available in the `assets/` folder.

---

## Technologies Used
- ESP32-CAM  
- Embedded C / Arduino  
- Python (for model training / preprocessing, if applicable)  
- Computer Vision  
- IoT & Wireless Communication  

---

## Project Structure

## How It Works
1. ESP32-CAM captures live video frames.
2. Frames are processed to detect hand gestures.
3. Recognized gestures are mapped to predefined actions.
4. Control signals are sent to IoT devices wirelessly.
5. Devices respond instantly without physical contact.

## Hardware Components
- ESP32-CAM module  
- Relay module (for appliance control)  
- Power supply  
- Connecting wires  
- Controlled appliance (bulb / fan / device)

## Software Components
- Arduino IDE  
- ESP32 board package  
- Embedded C / Arduino  
- Python (optional, for gesture model training)

## Applications
- Smart home automation  
- Touchless switches  
- Assistive technology for elderly and disabled users  
- Healthcare and hygienic environments  
- Industrial automation

## Limitations
- Performance depends on lighting conditions  
- Limited gesture set in current version  
- Camera-based system requires clear visibility

## Future Enhancements
- Integration with deep learning models  
- Support for complex gestures  
- Mobile or web-based dashboard  
- Edge AI optimization using TensorFlow Lite

## Author
**Varri Sneha**  
B.Tech – Electronics and Communication Engineering  
IIIT Manipur
