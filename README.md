# Smart-Dual-Axis-Solar-Tracker
# Smart Dual-Axis Solar Tracker with IoT ☀️📡

This repository contains the source code for an IoT-based Dual-Axis Solar Tracking System. The system maximizes solar panel efficiency by tracking the sun's position and monitors environmental factors like dust accumulation.

## Features 🚀
* **Dual-Axis Tracking:** Uses Mini Solar Cells as radiation sensors to track the sun accurately.
* **IoT Monitoring:** Real-time data logging to ThingSpeak.
* **Efficiency Comparison:** Compares tracking panel output vs. a fixed reference cell.
* **Dust Detection:** Uses a Sharp Dust Sensor to warn about panel soiling.

## Hardware Components 🛠️
* ESP32-WROVER-E
* 2x MG996R Servo Motors
* INA219 Power Sensor
* Sharp Dust Sensor
* GPS Module (NEO-6M)

## Software & Libraries 💻
* Arduino IDE
* ThingSpeak Library
* WiFi Library

## Cloud Dashboard (Simulation) ☁️
Currently, the code includes a full simulation sending mock data to ThingSpeak to test the IoT Dashboard before final hardware assembly.
