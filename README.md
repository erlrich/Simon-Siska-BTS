# Simon-Siska-BTS
IoT-Based Security Monitoring System for BTS (Base Transceiver Station)

## 📌 Overview
Simon SISKA is an IoT-based security system designed to monitor and detect unauthorized access, theft, and vandalism at BTS sites in real-time.

## 🔧 Technical Specifications
- **Microcontroller:** ESP32 (NodeMCU ESP-32E & ESP32-CAM)
- **Sensors:** Magnetic Switch, Limit Switch, PIR Motion Sensor, Laser + LDR
- **Communication:** Wi-Fi (SIM900A disabled, LTE planned)
- **Outputs:** Siren, LED, DFPlayer Mini (Audio), ESP32-CAM (Image)
- **Database:** MySQL via PHP-MyAdmin (local or online)

## 🚀 How It Works
1. Sensors detect suspicious activity (door open, motion, light cut).
2. System activates alarms (siren, LED, and voice/audio).
3. ESP32-CAM captures an image and saves it.
4. Event data and image logs are sent to a MySQL server.

## 🛠️ Implementation & Results
- **PIR Sensor** detects motion up to 4.5 meters.
- **ESP32-CAM** captures images at 1024 x 768 (XGA) resolution.
- **Magnetic Switch** reliably responds with ≥1 cm spacing.

## ⚡ Challenges & Solutions
- **SIM900A instability** → Replaced with Wi-Fi; LTE planned.
- **ESP32-CAM high power draw** → Optimized for short activation bursts.
- **Multi-sensor integration** → Prioritized event detection.

## 🔮 Future Development
- Face recognition using ESP32-CAM
- Real-time Telegram alert system
- Dual-mode support: Maintenance & Operational (via trigger, no reprogramming)

## 📎 Documentation & Links
- **GitHub Repo:** _[insert GitHub link here]_
- **PDF Documentation:** _[insert Google Drive or other link]_
- **Demo Video:** _[insert YouTube or Drive link]_

## 📂 Project Structure
Simon-SisKa-BTS/
├── firmware/
├── docs/
├── images/
├── database/
├── web/
└── README.md


## 🛡️ License
This project is licensed under the MIT License.

