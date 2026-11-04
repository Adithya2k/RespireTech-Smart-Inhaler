# RespireTech-Smart-Inhaler
RespireTech Smart Inhaler

IoT-based smart inhaler that tracks usage and sends real-time data to the cloud using ESP32, MQTT and AWS IoT Core.

Final year B.Tech Computer Science project.

Overview

RespireTech is a smart inhaler monitoring system built around an ESP32 microcontroller. It detects inhaler usage events and publishes them over MQTT to AWS IoT Core, where the data is stored and shown on a web dashboard. The goal is to help patients and caregivers track medication adherence in real time.

Features
Detects inhaler usage events using the ESP32
Publishes data securely over MQTT to AWS IoT Core
Real-time monitoring through a web dashboard
Cloud-based data handling for history and tracking

Tech Stack

Microcontroller: ESP32Firmware ; Arduino framework:(C/C++) ; Messaging: MQTT ; Cloud : AWS ; Frontend : Web dashboard (HTML, CSS, JavaScript)

Hardware Required

ESP32 development board; Sensor(s) for detecting inhaler use (DHT-22, MQ-22); Jumper wires and breadboard; USB cable and power source

Screenshot

<img width="966" height="810" alt="image" src="https://github.com/user-attachments/assets/1730c27a-61a3-4340-8bac-db57c97408e8" />


Future Improvements

Mobile app with dose reminders; Alerts to caregivers for missed doses; Analytics on usage trends; Battery optimisation for low-power operation

Author

Adithya B Raj: @Adithya2k

License

This project is licensed under the MIT License. See the LICENSE file for details.
