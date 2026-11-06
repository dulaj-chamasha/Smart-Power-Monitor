# 🔌 IoT Smart Power Monitoring Plug

![Platform](https://img.shields.io/badge/platform-ESP32-blue?logo=espressif)
![License](https://img.shields.io/badge/license-MIT-yellow.svg)
![MQTT](https://img.shields.io/badge/MQTT-supported-purple?logo=eclipse-mosquitto)
![Dashboard](https://img.shields.io/badge/Dashboard-Node--RED-red?logo=nodered)

---

A **smart plug solution** designed for remote appliance control and real-time energy monitoring.
Built with **ESP32** and **ADE9153A energy metering sensor**, this project demonstrates how IoT can empower smart homes with **energy efficiency** and **remote accessibility**.

---

## 📖 Overview

This project delivers a fully functional **IoT-enabled smart plug** capable of:

* 🟢 **Remote Control**: Switch devices on/off over Wi-Fi.
* ⚡ **Energy Monitoring**: Real-time tracking of **voltage, current, power, and frequency**.
* 🌐 **Dashboard Access**: Intuitive **Node-RED + MQTT** dashboard for live monitoring and control.

---

## 🛠️ Tech Stack

### 🔧 Hardware

* **ESP32** microcontroller
* **ADE9153A** energy metering sensor
* Custom PCB designed with **KiCad**
* 3D-printed enclosure modeled in **Onshape**

### 💻 Firmware

* Developed in **PlatformIO** (C++) for optimized ESP32 performance
* Energy data acquisition and remote command handling

### ☁️ IoT Integration

* **MQTT protocol** for secure, scalable communication
* **Node-RED dashboard** for monitoring and control

---

## 🚀 Key Features

* 🟢 **Remote device control** via Wi-Fi
* ⚡ **Live energy metrics** (voltage, current, power, frequency)
* 📊 **Real-time dashboard visualization**
* 🔐 **Secure IoT communication** with MQTT

---

## 📸 Project Preview

(Add images/screenshots of your hardware, PCB, dashboard here)

---

## 📂 Repository Structure

```bash
├── hardware/        # PCB design files (KiCad)  
├── enclosure/       # 3D enclosure models (Onshape/STL)  
├── firmware/        # ESP32 PlatformIO source code  
├── dashboard/       # Node-RED flows and MQTT configs  
└── README.md        # Project documentation  
```

---

## ✅ Result

A **working IoT smart plug prototype**, ready for deployment in **smart home ecosystems**.

---

## 📌 Future Improvements

* 📱 Mobile app integration (Android/iOS)
* 🌍 Cloud-based analytics for long-term energy usage insights
* 🧠 AI-based prediction for energy optimization

---

## 📜 License

This project is licensed under the **MIT License** – feel free to use and modify.

---
