# WiDrive EV Prototype v1 🚗⚡

## 📌 Overview

WiDrive EV Prototype v1 is a compact electric vehicle prototype designed using CATIA and 3D printed at the CDAC lab. The system is controlled wirelessly using an ESP32 module.

It uses a 4S lithium-ion battery pack, a gear-based transmission system, and a motor driver for speed and direction control.

---

## 🚀 Features

* 🔋Lithium-Ion Battery (Rechargeable with BMS)
* 📶 WiFi Control using ESP32
* 🔄 Forward & Backward Motion
* 🎚 PWM-based Speed Control
* ⚙️ Gear System (10T driver, 40T driven → high torque)
* 💡 LED Status Indicator

---

## ⚙️ Mechanical Design

* Designed in CATIA (3D modeling and assembly)
* 3D printed chassis, gear, and wheels
* Gear ratio: 1:4 (torque increased, speed reduced)

---

## 🔌 Electronics Used

* ESP32 WiFi Module
* 12V DC Motor
* Motor Driver
* 4  Li-ion Cells
* 4S BMS
* 2 × XL4015 Buck Converter
* Diode (1N4007)
* Switches, LED, wires

---

## 🔋 Power Flow

Battery → BMS → Buck Converter → ESP32 + Motor Driver → Motor

---

## 💻 Code

ESP32 is used for:

* WiFi-based control
* Motor direction control
* Motor Driver control

(Code available in `/code/esp32/`)

---

## 📸 Prototype Images

(Add images from `/images/`)

---

## 📊 Results

* Successful forward and backward motion
* Stable WiFi-based control
* Increased torque using 1:4 gear ratio

---

## 🔮 Future Improvements

* Mobile app interface
* Battery Charging Percentage
intregate gps
* Improved chassis design
* Protective enclosure
* Sensor integration

---

## 📂 Project Structure

```
WiDrive-EV-v1/
├── design/
├── electronics/
├── code/
├── images/
└── README.md
```

---

## 👥 Team

* Tushar Roy – Mechanical design (CATIA), system integration
* Debasis Dutta – Electronic circuit design, assembly

## 🤝 Additional Support

* Arpon Burnwal –  (EE)
* Ishika Mridha –  (EE)
* Soham Bhattacharjee –  (EE)
* Md. Zeeshan – (Mechanical)
* Md. Farukh Ansari –  (Mechanical)
* Chitradip Mahato – (Mechanical)
* Raj Gupta – (Mechanical)
* Rana Chattopadhyay – (Mechanical)
