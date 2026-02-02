# ESP32 Soil Moisture MQTT Publisher

This repository contains an ESP32 Arduino sketch that publishes soil moisture
data to an MQTT broker.

# Features
- Connects ESP32 to WiFi (2.4 GHz)
- Publishes soil moisture values every 5 seconds
- Uses MQTT broker: broker.mqttdashboard.com
- Topic: ESP32/SOIL/DATA
- Verified using Node-RED before hardware deployment

## Files
- `ESP32_soil_MQTT_Publisher.ino` – Main ESP32 Arduino sketch

## How it works
- The ESP32 connects to WiFi
- Generates simulated soil moisture values (30–80)
- Publishes values via MQTT
- Output confirmed using Serial Monitor and Node-RED

## Future Work
- Replace simulated values with real soil sensor
- Add solenoid control via MQTT subscribe

## Tested
- Arduino IDE 2.3.7
- ESP32 Dev Module
- Node-RED MQTT flow

