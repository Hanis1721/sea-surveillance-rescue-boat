# 🚤 Multi-Purpose Sea Surveillance + Search and Rescue Boat

A low-cost, Arduino-based unmanned surface vehicle (USV) designed for coastal monitoring, flood rescue, and environmental surveillance. The system combines GPS tracking, 360° ultrasonic obstacle detection, and buzzer-based alerts to enable safe, intelligent waterborne operations.

---

## 📖 Abstract

The Multipurpose Sea Surveillance + Search and Rescue Boat is designed to support intelligent waterborne operations such as coastal monitoring, flood rescue, and environmental surveillance. It integrates GPS tracking, ultrasonic obstacle detection, and beep alert systems, controlled through an Arduino microcontroller. The system ensures real-time navigation awareness, collision prevention, and efficient remote tracking.

With an emphasis on low-cost implementation and autonomous functionality, this project demonstrates how embedded systems and sensors can enhance marine safety. The prototype operates automatically, detects obstacles through ultrasonic ranging, triggers buzzer alerts, and sends GPS coordinates for continuous tracking. The design can be further expanded for camera integration, IoT-based monitoring, and solar power usage.

---

## ✨ Features

- 🔄 **360° Obstacle Scanning** — Ultrasonic sensor mounted on a servo motor for full environmental coverage
- 📍 **Real-Time GPS Tracking** — Continuous location monitoring via NEO-6M GPS module
- 🔔 **Buzzer Alert System** — Instant audible warning when obstacles are detected within range
- 🔋 **Low-Cost & Power Efficient** — Runs on a rechargeable 12V battery, regulated to 5V for sensors
- 🧩 **Scalable Design** — Built for future upgrades: camera integration, IoT monitoring, solar power, AI-based navigation

---

## 🛠️ Hardware Components


|
 Component 
|
 Model 
|
 Purpose 
|
|
---
|
---
|
---
|
|
 Microcontroller 
|
 Arduino UNO 
|
 Central processing unit 
|
|
 Ultrasonic Sensor 
|
 HC-SR04 
|
 Obstacle detection (2–400 cm range) 
|
|
 Servo Motor 
|
 SG90 
|
 360° rotation of ultrasonic sensor 
|
|
 GPS Module 
|
 NEO-6M 
|
 Real-time latitude/longitude tracking 
|
|
 Buzzer 
|
 Passive Buzzer 
|
 Audible obstacle alerts 
|
|
 Power Supply 
|
 12V Rechargeable Battery 
|
 Powers entire system 
|

## 💻 Software Components

- **Arduino IDE** — Programming and uploading control logic
- **Serial Monitor** — Real-time GPS data display

---

## ⚙️ How It Works

1. Arduino initializes all modules and starts servo motor rotation.
2. The ultrasonic sensor continuously scans the environment through 360°.
3. When an obstacle is detected within the threshold distance, the buzzer is triggered.
4. Simultaneously, the GPS module records the current location coordinates.
5. Coordinates are displayed via serial monitor / can be logged or transmitted.
6. The system loops continuously for real-time monitoring.

---

## 📊 Results

- **Obstacle Detection:** Reliable detection within 35–40 cm range with prompt buzzer response
- **GPS Accuracy:** Average positional accuracy of ±3 meters
- **Power Efficiency:** Stable extended operation on a single 12V battery charge

---

## 📸 Prototype

<p align="center">
  <img src="prototype1.jpeg" width="45%" />
  <img src="prototype2.jpeg" width="45%" />
</p>

---

## 🎥 Working Demo

Watch the full working demonstration of the Multi-Purpose Sea Surveillance + Search and Rescue Boat here:

▶️ **[Watch Demo Video (Google Drive)](https://drive.google.com/file/d/1r1S2o0x3szSD4WtT97CK4LEUoAB8d1fA/view?usp=sharing)*

---

## 🚀 Future Enhancements

- 📷 Camera module integration for live visual monitoring
- ☁️ IoT-based data transmission to cloud/mobile apps
- 🤖 AI-based autonomous navigation and decision-making
- ☀️ Solar charging for extended field operation
- 📡 Long-range wireless communication (GSM/LoRa)

---

## 📄 Documentation

The full project report, including literature review, system design, and results, is available here:
📘 [`docs/project-report.pdf`](project-report.pdf)

---

## 👥 Team

- **Hanis Mariam A (111624104028)** — Hardware Assembly and Circuit Design
- **Abenayaa B (111624104001)** — System Integration and Documentation
- **Jashiraa Shabrein S (111624104037)** — Embedded Programming and Testing

**Department of Electronics and Communication Engineering**
R.M.K. College of Engineering and Technology
Course: Product Development Lab – I (24EC311)
October 2025

---

## 📜 License

This project is open for academic and educational use. Feel free to fork and build upon it.
