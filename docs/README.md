# HydroWatch - IoT-Based Water Quality and Motor Automation System

## Overview

HydroWatch is an innovative IoT-based solution for monitoring water quality and controlling water-related devices (such as motors and solenoids). It uses sensors like water flow, turbidity, and water level sensors to collect real-time data, which is sent to the Blynk cloud for remote monitoring and control.

The project includes an **ESP8266** microcontroller and integrates sensors with the **Blynk platform** to enable cloud-based control. This system can help automate water-related processes for households, industries, and agriculture.

## Features:
- **Water Quality Monitoring**: Measure water flow, turbidity, and water level.
- **Motor and Solenoid Control**: Remotely control water-related devices.
- **Cloud Integration**: Monitor and control devices via the Blynk app.

## Hardware Required:
- **ESP8266 (NodeMCU)** or **ESP32**
- **Turbidity Sensor**
- **Water Flow Sensor**
- **Water Level Sensor**
- **Relay Module** (for motor/solenoid control)
- **Buzzer and LEDs** (for water quality indication)
- **Jumper wires and breadboard**

## Software:
- **Arduino IDE** (for code upload)
- **Blynk App** (for mobile control)

## Setup Instructions:

1. **Install the necessary libraries**: 
   - Blynk library in Arduino IDE.
   - ESP8266 board support in Arduino IDE.

2. **Upload the code**:
   - Open `blynk_esp8266.ino` in the Arduino IDE.
   - Set your WiFi credentials and Blynk Auth Token.
   - Upload the code to your ESP8266.

3. **Configure Blynk App**:
   - Create a new project in the Blynk app.
   - Add Virtual Pins for sensors and devices.
   - Set up the control widgets (buttons for motor/solenoid, gauge for sensor data).

4. **Connect sensors and modules**: Follow the circuit diagram to correctly connect sensors, relays, and LEDs to the ESP8266.

5. **Run the Project**: After uploading the code, monitor and control devices via the Blynk app.


