# IoT Based Soil Monitoring System Moisture Fertility

## Overview
This project is an IoT-based soil monitoring system designed to measure and analyze soil moisture and fertility (NPK levels) in real-time.
The system helps farmers and users make better decisions by providing data visualization, alerts, and recommendations to improve agricultural productivity.

## Features
- Real-time soil moisture monitoring
- Soil fertility (NPK) measurement
- Data logging and historical tracking
- Smart notifications (e.g., irrigation recommendation)
- Web/mobile-based monitoring interface
- Offline data storage when connection is lost

## System Architecture
The system follows a client-server architecture:
- Sensors collect soil data
- Microcontroller processes and sends data
- Data is transmitted via WiFi
- Backend server stores and processes data
- User accesses data via web/mobile interface

## Tech Stack
- Microcontroller: ESP32
- Programming: C
- Backend: FastAPI
- Database: MySQL
- Communication: HTTP
- Concepts: IoT, Real-Time Monitoring, System Design

## Hardware Components
- ESP32 Microcontroller
- Soil Moisture Sensor (YL-69)
- Soil Fertility Sensor (NPK Analog)
- Power Supply (Battery / Adapter)

## System Workflow
1. Sensors read soil moisture and nutrient levels
2. ESP32 processes sensor data
3. Data is sent to backend server via WiFi
4. Server stores data in database
5. User interface displays real-time data
6. System sends alerts if values exceed thresholds

## Key Functionalities
- Continuous data acquisition (every 10 minutes)
- Real-time monitoring dashboard
- Threshold-based alerts
- Historical data visualization (graphs)
