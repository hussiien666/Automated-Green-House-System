# 🌿 Automated Greenhouse System using NI LabVIEW and Arduino

This repository contains the source code and documentation for our **Automated Greenhouse System**, developed as part of our coursework at the **Arab Academy for Science, Technology and Maritime Transport**. The project integrates **NI LabVIEW** and **Arduino** to create a smart, sensor-driven greenhouse that monitors and adjusts environmental conditions to optimize plant growth.

---

## 📌 Project Summary

The system is designed to help farmers **monitor and control** critical environmental factors in a greenhouse setting. It automates responses to changes in **light, temperature, humidity, soil moisture**, and **safety conditions** using a variety of sensors and actuators. The system is **scalable**, **remotely controllable**, and aims to make modern farming **smarter and more sustainable**.

---

## 🚀 Features

- Real-time monitoring of:
  - Ambient light
  - Temperature
  - Humidity
  - Soil moisture
  - Smoke/fire
  - Bird presence (via ultrasonic sensor)

- Automated actions based on sensor readings:
  - Activates UV lights
  - Turns on AC for cooling
  - Triggers sprinklers or water pump
  - Activates fire safety systems
  - Scares away birds with buzzer

- User-friendly interface via **NI LabVIEW**
- Arduino-based sensor integration
- Scalable for different greenhouse sizes and plant types

---

## 🛠️ Technologies Used

- **NI LabVIEW** – For GUI and system control logic
- **Arduino UNO** – Microcontroller for sensor interfacing
- **Sensors:**
  - LDR (Light Dependent Resistor)
  - DHT11/DHT22 (Temperature & Humidity)
  - Soil Moisture Sensor
  - Smoke Sensor (e.g., MQ-2)
  - Ultrasonic Sensor (HC-SR04)

---

## 🧠 Sensor Functions

| Sensor           | Purpose                                                                 |
|------------------|-------------------------------------------------------------------------|
| LDR              | Measures sunlight; activates UV lights if insufficient                  |
| Temperature      | Maintains optimal air temperature via AC                                |
| Humidity         | Activates sprinklers if humidity is too low                             |
| Soil Moisture    | Activates water pump if soil is too dry                                 |
| Smoke            | Detects fire/smoke; activates extinguishing mechanism                   |
| Ultrasonic       | Detects birds near crops; activates buzzer to scare them away           |

---
