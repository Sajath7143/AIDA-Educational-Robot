# 🚀 ESP8266 WiFi BLDC Motor Control

Control two BLDC motors (via ESCs) wirelessly using an ESP8266 and a simple web interface.  
This project lets you adjust motor speed in real-time using sliders in your browser.

---

## 📌 Features

- 📡 WiFi-based control (no app needed)
- 🎚️ Real-time motor speed adjustment
- 🌐 Web interface (mobile + desktop friendly)
- ⚡ Supports dual BLDC motors via ESC
- 🔧 Simple and lightweight code

---

## 🧰 Hardware Requirements

- ESP8266 (NodeMCU / Wemos D1 Mini)
- 2 × BLDC Motors
- 2 × ESC (Electronic Speed Controller)
- Power supply (LiPo battery recommended)
- Connecting wires

---

## 🔌 Wiring

| Component        | ESP8266 Pin |
|----------------|------------|
| Left ESC Signal | D5         |
| Right ESC Signal| D6         |
| GND             | GND        |

> ⚠️ Make sure ESCs and ESP8266 share a common ground.

---

## 💻 Software Requirements

- Arduino IDE
- ESP8266 Board Package
- Libraries:
  - `ESP8266WiFi`
  - `ESP8266WebServer`
  - `Servo`

---

## ⚙️ Setup Instructions

1. Install ESP8266 board in Arduino IDE  
2. Install required libraries  
3. Open the `.ino` file  
4. Update WiFi credentials:

```cpp
const char* ssid = "YOUR_SSID";
const char* password = "YOUR_PASSWORD";
