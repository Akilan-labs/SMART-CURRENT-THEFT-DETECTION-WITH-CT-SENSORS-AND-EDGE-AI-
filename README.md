# ⚡ Smart Electricity Theft Detection using Edge AI (STM32)

## 📖 Overview

Electricity theft is a critical challenge that leads to major financial losses and affects the efficiency and reliability of power distribution systems. This project presents a smart embedded solution capable of detecting unauthorized electricity usage in real time using current sensing and Edge AI.

The system utilizes CT (Current Transformer) sensors along with the ACS712 current sensor to measure current flow in power lines. An STM32 microcontroller processes this data and applies a lightweight Edge AI model to identify anomalies that may indicate electricity theft.

---

## 🚀 Features

* Real-time current monitoring
* Detection of illegal tapping and abnormal load usage
* Edge AI-based anomaly detection
* Low-cost and energy-efficient design
* Fully embedded system (no continuous internet required)

---

## 🛠️ Hardware Components

* STM32 Microcontroller
* CT Sensor (Current Transformer)
* ACS712 Current Sensor Module
* Power Supply Unit
* Breadboard / PCB setup

---

## 💻 Software & Tools

* Embedded C
* STM32CubeIDE
* Edge AI / TinyML
* Serial communication interface

---

## ⚙️ Working Principle

1. CT sensor and ACS712 measure real-time current from the power line
2. STM32 microcontroller collects and processes sensor data
3. Edge AI model analyzes current patterns continuously
4. Any abnormal deviation is detected and flagged as potential electricity theft

---

## 🧩 System Architecture

Power Line → CT Sensor / ACS712 → STM32 → Edge AI Model → Detection Output

---

## 🔧 Setup Instructions

### 1. Clone the Repository

### 2. Open in STM32CubeIDE

Import the project into STM32CubeIDE.

### 3. Hardware Setup

* Connect CT sensor to the main current line
* Connect ACS712 to STM32 analog input
* Ensure proper power supply and grounding

### 4. Upload Firmware

Flash the code to the STM32 microcontroller.

### 5. Monitor Output

Use a serial monitor to observe real-time data and detection alerts.

---

## 📊 Results

The system successfully detects abnormal current variations that indicate possible electricity theft. It provides fast and reliable detection without requiring cloud processing, making it suitable for real-time applications.

---

## 📈 Future Enhancements

* IoT integration for remote monitoring
* Mobile application for alerts
* GPS-based theft localization
* Advanced AI models for improved accuracy

---

## 🎯 Applications

* Smart grid systems
* Power distribution monitoring
* Industrial energy auditing
* Rural electrification systems

---

## 👨‍💻 Author

**Akilan M**
Final Year - Electronics and Communication Engineering,
Kongu Engineering College

