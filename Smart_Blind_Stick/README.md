# Smart Assistive Blind Stick
Smart Assistive Blind Stick with Voice Assistance

📌 Project Overview

The Smart Assistive Blind Stick is an IoT-based assistive system designed to help visually impaired individuals navigate safely and independently. The system uses sensors and embedded technologies to detect obstacles and environmental hazards in real time and provides voice-based feedback to the user.

The project integrates an ESP32 microcontroller, ultrasonic sensors, a water detection sensor, and a GPS module to create a portable and user-friendly assistive solution.

🎯 Features
- Real-time obstacle detection using ultrasonic sensors
- Water hazard detection for wet surfaces and puddles
- Voice-based alerts such as: “Object is ahead”, “Water is detected”
- GPS-based location tracking
- Web dashboard for monitoring and navigation
- Portable and rechargeable system
- Cost-effective IoT solution

🛠️ Hardware Components
| Component | Quantity |
|---|---:|
| ESP32 Microcontroller | 1 |
| HC-SR04 Ultrasonic Sensor | 1–2 |
| Water Detection Sensor | 1 |
| NEO-6M GPS Module | 1 |
| Speaker / Audio Module | 1 |
| Buzzer (Optional) | 1 |
| 18650 Battery | 1 |
| Jumper Wires | As required |
| Breadboard / Perfboard | 1 |

💻 Software Requirements
- Arduino IDE
- ESP32 Board Package
- TinyGPS++ library
- WiFi library
- HTML/CSS/JavaScript (for dashboard)

🔌 ESP32 Connections (Example)
| Component | ESP32 Pin |
|---|---:|
| Ultrasonic TRIG | GPIO 5 |
| Ultrasonic ECHO | GPIO 18 |
| Water Sensor | GPIO 15 |
| GPS TX | GPIO 16 |
| GPS RX | GPIO 17 |
| Buzzer | GPIO 4 |
| Speaker Module | GPIO 2 |
| VCC | 3.3V / 5V |
| GND | GND |

⚙️ Working Principle
1. Sensors continuously monitor the surroundings.
2. Ultrasonic sensors detect nearby obstacles.
3. Water sensor detects wet surfaces or puddles.
4. GPS module provides real-time location data.
5. ESP32 processes all sensor inputs.
6. Based on detected conditions, the system generates voice alerts.
7. The process repeats continuously in real time.

🌐 Dashboard Features
- Live obstacle monitoring
- Water detection status
- GPS location tracking
- Voice session summary
- Route navigation support

🚀 Installation & Setup
Step 1: Install Arduino IDE

Download and install Arduino IDE from the official website.

Step 2: Install ESP32 Board
1. Open Arduino IDE
2. Go to: File → Preferences
3. Add the following URL to "Additional Boards Manager URLs":
	- https://dl.espressif.com/dl/package_esp32_index.json
4. Install the ESP32 board package from Boards Manager.

Step 3: Install Libraries
Install the following libraries via Library Manager or ZIP:
- TinyGPS++
- WiFi

Step 4: Upload Code
1. Connect ESP32 via USB
2. Select the correct board and COM port in Arduino IDE
3. Open the main sketch and upload

🧪 Testing
- Verify ultrasonic sensor distance readings
- Test water detection by exposing the sensor to moisture
- Check GPS connectivity outdoors
- Verify voice output messages
- Monitor data on the dashboard

⚠️ Limitations
- GPS accuracy may reduce indoors
- Ultrasonic sensors have limited range
- Battery requires periodic charging

👥 Team
- Chetana Nehete
- Harshali Patil


🌍 Sustainable Development Goals (SDGs)

This project supports:
- SDG 3 – Good Health and Well-being
- SDG 10 – Reduced Inequalities
- SDG 9 – Industry, Innovation and Infrastructure
- SDG 11 – Sustainable Cities and Communities

🔮 Future Enhancements
- AI-based object recognition
- Mobile application integration
- Advanced voice navigation
- Cloud-based analytics
- Improved battery optimization

📚 Technologies Used
- ESP32
- Arduino IDE
- IoT
- GPS Technology
- Embedded Systems
- HTML/CSS/JavaScript

👨‍💻 Project Description

Developed an IoT-based Smart Assistive Blind Stick using ESP32 with obstacle detection, water sensing, GPS tracking, and voice-based alerts for enhanced navigation and safety.

📌 Conclusion

The Smart Assistive Blind Stick demonstrates how IoT and embedded systems can be used to improve the safety, independence, and confidence of visually impaired individuals. By integrating sensors, GPS tracking, and voice-based feedback into a portable device, the project provides a practical and cost-effective assistive solution.

---
