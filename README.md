# Smart-parking-system
# 🚗 IR-Based Smart Parking System

## 📌 Project Overview
The IR-Based Smart Parking System is an IoT project developed using ESP32 and an IR sensor to monitor parking slot occupancy in real time. The system detects whether a parking slot is occupied or available and displays the status on a 16×2 I2C LCD. A Node-RED dashboard is used for live monitoring.

## 🎯 Objectives
- Detect vehicle presence using an IR sensor.
- Display parking slot status on an LCD.
- Indicate slot status using LEDs.
- Monitor parking status in real time.

## 🛠️ Hardware Components
- ESP32 Development Board
- IR Sensor
- 16×2 LCD with I2C Module
- Red LED
- Green LED
- Breadboard
- Jumper Wires
- USB Cable

## 💻 Software Used
- Arduino IDE
- Node-RED
- Serial Monitor

## ⚙️ Working
1. The IR sensor detects whether a vehicle is present.
2. ESP32 reads the sensor value.
3. If a vehicle is detected:
   - LCD displays "Occupied"
   - Red LED turns ON
   - Green LED turns OFF
4. If no vehicle is detected:
   - LCD displays "Available"
   - Green LED turns ON
   - Red LED turns OFF
5. The parking status is also monitored through the Node-RED dashboard.

## ✨ Features
- Real-time parking detection
- LCD status display
- LED indication
- ESP32-based IoT system
- Simple and low-cost implementation

## 📸 Project Images
Prototype and dashboard screenshots are available in the `images` folder.

## 📂 Project Structure

IR-Based-Smart-Parking-System/
├── Arduino_Code/
├── images/
├── PPT/
└── README.md

## 🚀 Future Improvements
- Multiple parking slots
- Mobile application
- Cloud database integration
- Online slot reservation
- Automatic payment system

## 👨‍💻 Developed By
Rithish D
