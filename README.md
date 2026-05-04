<h1 align="center">IoT Gesture & Voice Controlled Car</h1>

<p align="center">
  <b>Arduino-based smart vehicle controlled via accelerometer gestures and voice commands</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white"/>
  <img src="https://img.shields.io/badge/Embedded%20C-00599C?style=for-the-badge&logo=c&logoColor=white"/>
  <img src="https://img.shields.io/badge/IoT-000000?style=for-the-badge&logo=internetofthings&logoColor=white"/>
  <img src="https://img.shields.io/badge/Bluetooth-0082FC?style=for-the-badge&logo=bluetooth&logoColor=white"/>
  <img src="https://img.shields.io/badge/Sensors-MPU6050-informational?style=for-the-badge"/>
</p>

---

## Overview
This project implements an IoT-based smart vehicle that can be controlled using **hand gestures (accelerometer)** and **voice commands**. It integrates hardware sensors with real-time software control to enable seamless physical interaction with a digital system.

---

## Tech Stack
- Arduino  
- Accelerometer (MPU6050)  
- Bluetooth Module (HC-05)  
- Embedded C  

---

## Features
- Gesture-based movement using accelerometer input  
- Voice command control via Bluetooth interface  
- Real-time wireless communication  
- Integration of hardware sensors with software logic  

---

## How It Works
- Accelerometer captures hand tilt (X/Y axis values)  
- Arduino processes sensor data and maps it to movement directions  
- Commands are sent wirelessly via Bluetooth (HC-05)  
- Motor driver executes movement (forward, backward, left, right)  
- Voice commands are received via mobile app and transmitted over Bluetooth  

---

## Demo
Basic working demonstration of the system:

[Watch Demo Video](https://drive.google.com/file/d/1pvvLkXKhZsDPaUif28rP9EINUDBoUvBN/view?usp=drivesdk)

> Note: This is an early demo. The full project included both gesture and voice control modules.

---

## Project Structure
```
IoT-Gesture-Voice-Car/
├── main.ino                 # Main Arduino code
└── README.md
```

---

## Key Highlights
- Implemented real-time gesture recognition using accelerometer data  
- Established wireless communication via Bluetooth (HC-05)  
- Designed a system combining embedded hardware and control logic  

---

## Future Improvements
- Add obstacle detection using ultrasonic sensors  
- Improve gesture accuracy with filtering algorithms  
- Develop a dedicated mobile app for enhanced control  

---

## Author
**Agniva Chatterjee**
