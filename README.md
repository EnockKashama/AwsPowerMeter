#Smart Home Energy Monitoring Platform ⚡🏠

A cloud-connected IoT energy monitoring platform built using ESP32 microcontrollers, Modbus RTU communication, Hardware-in-the-Loop (HIL) simulation, MQTT messaging, and AWS cloud services.

This project is focused on building a scalable smart-home energy monitoring ecosystem capable of measuring, processing, transmitting, and visualizing electrical energy usage in real time.

🚀 Project Goals

The main objective of this project is to design a production-style IoT energy management system that can:

Monitor real-time electrical parameters
Simulate power measurement hardware using HIL techniques
Process sensor data locally on embedded devices
Transmit telemetry securely using MQTT
Store and analyze energy data in the cloud
Provide a foundation for smart-home automation and energy optimization

The project is intentionally designed to mimic real-world industrial IoT architectures and workflows.

🧠 Key Features
Current Features
ESP32-based Modbus RTU master implementation
PZEM-004T energy meter protocol emulation
Arduino-based Hardware-in-the-Loop (HIL) power meter simulator
Raw Modbus CRC16 implementation (no external libraries)
UART TX/RX communication between ESP32 and emulator
Real-time voltage/current/power/energy measurement parsing
Planned Features
MQTT telemetry publishing
AWS IoT Core integration
Secure TLS device authentication
Real-time cloud dashboards
Device provisioning system
Historical energy analytics
Remote relay control
Energy cost estimation
Load-shedding-aware automation
Mobile application support

