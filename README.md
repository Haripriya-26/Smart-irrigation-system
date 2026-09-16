# 🌱 Smart Irrigation System

## 📌 Overview

The Smart Irrigation System is an IoT-based agriculture project designed to monitor soil and environmental conditions and automate irrigation.

The system uses sensors to determine the condition of the field and controls the water supply based on the collected data.

## 🎯 Objective

The main objective is to reduce water wastage and provide efficient irrigation by supplying water when required by the crops.

## ⚙️ How It Works

1. Sensors collect soil and environmental data.
2. The controller reads the sensor values.
3. Soil moisture is checked to determine whether irrigation is required.
4. If the soil is dry, the water pump is activated.
5. When sufficient moisture is detected, the pump is turned off.
6. Sensor data can be monitored through an IoT dashboard.
7. Alerts can be provided when required.

## 🛠️ Technologies Used

- Arduino / ESP32
- Soil Moisture Sensor
- Temperature Sensor
- Humidity Sensor
- Water Level Sensor
- Water Pump
- Relay Module
- IoT Dashboard

## 🔄 System Flow

```text
Sensors
   ↓
Collect Soil & Environmental Data
   ↓
Controller
   ↓
Check Soil Moisture
   ↓
Is Soil Dry?
 ↙          ↘
Yes          No
 ↓            ↓
Pump ON     Pump OFF
 ↓
Irrigation
 ↓
Monitor Again
✨ Features
Soil moisture monitoring
Automatic irrigation
Water level monitoring
Temperature and humidity monitoring
Reduced water wastage
IoT-based monitoring                                                                                 
🚀 Future Improvements
Weather-based irrigation
Mobile application
Crop-specific recommendations
Cloud data storage
SMS / notification alerts

## 📄 Project Presentation

[View ArgoSmart Project Presentation](./ArgoSmart-Project-Presentation.pptx)
