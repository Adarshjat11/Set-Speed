# Set-Speed
# 🚌 SetSpeed – School Bus Speed Monitoring System 🚦

> An IoT-based safety solution to monitor and control school bus speeds in real-time using NodeMCU ESP8266, sensors, OLED display, and Blynk IoT platform.

---

## 📌 Project Overview

**SetSpeed** is a smart embedded system designed to ensure **safe driving practices in school buses** by:
- Continuously monitoring speed
- Providing real-time visual and audible alerts to the driver
- Sending live speed data to school authorities using the **Blynk IoT app**

---

## 🎯 Key Features

- ✅ Speed feedback on **OLED Display**
- 🚦 LED indicators based on speed zones
- 🔊 Buzzer alerts for overspeeding
- 📡 **Wi-Fi-enabled** data transmission to Blynk app
- 📱 Real-time speed monitoring for school administrators

---

## ⚙️ How It Works

| Speed Range     | OLED Message                              | LED Color | Buzzer |
|-----------------|--------------------------------------------|-----------|--------|
| 0–30 km/h       | "You are going all well, Speed: __ km/h"  | Green     | ❌     |
| 30–45 km/h      | "Keep constant or slow down, Speed: __ km/h" | Yellow  | ❌     |
| Above 45 km/h   | "⚠ WARNING! Slow Down, Speed: __ km/h"    | Red       | ✅     |

---

## 🛠️ Tech Stack

- 🔌 **NodeMCU ESP8266**
- 📟 OLED Display (I2C)
- 💡 LEDs (Green, Yellow, Red)
- 🔊 Buzzer
- 🧭 Speed Sensor (e.g., rotary encoder or simulated input)
- 🌐 Blynk IoT App
- 🔧 Embedded C / Arduino IDE

---

## 👨‍💻 My Role

- Coded the logic for speed detection and alerts
- Integrated all hardware components with NodeMCU
- Set up Blynk dashboard for live monitoring
- Calibrated speed thresholds and tested output

---

## 🚀 Getting Started

1. Connect components as per the circuit diagram
2. Upload the code to NodeMCU via Arduino IDE
3. Link NodeMCU to Wi-Fi
4. Connect Blynk app to your project and monitor speed live

---

## 📫 Contact

- 🌐 [LinkedIn](https://www.linkedin.com/in/adarsh-jat-39a79a250/)
- ✉️ adarshjat3011@gmail.com 

