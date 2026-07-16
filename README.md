# 🚢 Multi-Purpose Sea Surveillance & Search and Rescue Boat

## 📋 About The Project
A semi-autonomous surface vehicle engineered for intelligent waterborne 
operations including coastal surveillance, flood rescue missions, and 
environmental monitoring. The system combines GPS-based real-time tracking, 
ultrasonic obstacle avoidance, and embedded microcontroller logic to 
deliver a reliable and affordable marine safety solution.

Built as part of **Product Development Lab I** at RMK College of 
Engineering and Technology, Chennai (October 2025).

## 🎬 Project Demo
👉 [Click Here to Watch Demo](add-your-video-link-here)

## 🖼️ Hardware Build
  <img src="prototype1.jpeg" width="400" />
  <img src="prototype2.jpeg" width="400" />

## ⚙️ Technology Used
| Part | Specification |
|---|---|
| Main Controller | Arduino UNO |
| Obstacle Sensor | HC-SR04 Ultrasonic Sensor |
| Rotation Mechanism | SG90 Servo Motor |
| Navigation | NEO-6M GPS Module |
| Warning System | Passive Buzzer |
| Energy Source | 12V Rechargeable Battery |
| Code Environment | Arduino IDE (Embedded C) |

## 🔑 Key Features
- ✅ Autonomous 360° obstacle scanning using servo-mounted ultrasonic sensor
- ✅ Real-time GPS coordinate logging (latitude, longitude, altitude)
- ✅ Instant buzzer alert triggered when obstacle detected within 35–40 cm
- ✅ Serial monitor display of live location data for remote tracking
- ✅ Compact, lightweight and water-resistant design
- ✅ Applicable for flood rescue, coastal patrol and environmental surveys
- ✅ Expandable architecture — supports IoT, camera and AI add-ons

## 🧩 Component Details
| Component | Function |
|---|---|
| Arduino UNO | Core processing unit — reads sensors, triggers outputs |
| HC-SR04 | Measures distance to obstacles using sound waves |
| SG90 Servo | Rotates ultrasonic sensor for 360° area coverage |
| NEO-6M GPS | Captures real-time position via satellite signals |
| Passive Buzzer | Sounds alert when obstacle enters critical range |
| 12V Battery | Powers all electronic modules on board |

## 🔄 How It Works
```
Power ON
    ↓
System Initialization
(Arduino, GPS, Servo, Ultrasonic, Buzzer)
    ↓
Servo rotates continuously → 360° scan
    ↓
Ultrasonic reads distance every cycle
    ↓
Obstacle within 35cm?
    YES → Buzzer ON + GPS coordinates logged
    NO  → Continue scanning
    ↓
Loop repeats
```

## 📈 Test Results
| Test Parameter | Observed Result |
|---|---|
| Obstacle Detection Distance | 35–40 cm |
| GPS Position Accuracy | ±3 metres |
| Servo Scan Coverage | 360° continuous |
| Alert Response Time | Near-instantaneous |
| Battery Performance | Extended operation ✅ |

## 🔭 Scope for Improvement
- 📸 Add camera module for live video feed
- ☁️ Cloud integration via IoT for remote GPS monitoring
- 🤖 AI-based path planning and obstacle avoidance
- ☀️ Solar panel integration for extended battery life
- 📡 LoRa or GSM wireless communication

## 👩‍💻 Project Team
- **Hanis Mariam A** (111624104028) — Hardware Assembly + Circuit Design
- **Abenayaa B** (111624104001) — System Integration & Documentation
- **Jashiraa Shabrein S** (111624104037) — Embedded Programming & Testing

## 🏫 Institution Details
**Product Development Lab I | Course Code: 24EC311**
Department of Electronics and Communication Engineering
RMK College of Engineering and Technology
RSM Nagar, Puduvoyal – 601206 | October 2025

Faculty Supervisor: **Dr. V Dyana ChristiIda**

## 📬 Contact
**Hanis Mariam A** — 3rd Year ECE Student, RMKCET Chennai

[![LinkedIn](https://www.linkedin.com/in/hanis-mariam-a-a8861132a/)
[![GitHub](https://img.shields.io/badge/GitHub-Follow-black)](https://github.com/hanis1721)
