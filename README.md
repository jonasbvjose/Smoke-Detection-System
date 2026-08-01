# Automated Smoking Zone Monitoring and Alerting System

An Arduino-based system designed to detect smoke in restricted or non-smoking areas and provide real-time visual and audible alerts.

## Project Overview
The system continuously monitors smoke levels using an MQ-2 gas sensor. An Arduino UNO processes the sensor readings and compares them with a predefined threshold.

When smoke exceeds the threshold:
- The buzzer is activated
- The LCD displays a smoke alert
- The smoke level is displayed through the Serial Monitor

## Hardware Used
- Arduino UNO
- MQ-2 Smoke and Gas Sensor
- 16x2 I2C LCD Display
- Buzzer
- 9V Battery / Power Supply
- Breadboard
- Jumper Wires

## Software & Technologies
- Arduino IDE
- C/C++
- Embedded Systems
- Sensor Interfacing
- I2C Communication
- Serial Communication

## Working
1. The MQ-2 sensor continuously measures smoke levels.
2. Arduino UNO reads the analog sensor value.
3. The reading is compared with a predefined threshold.
4. Under normal conditions, the LCD displays the normal status.
5. When smoke crosses the threshold, the buzzer activates and the LCD displays a smoke alert.

## Results
- Successfully detected smoke in real time
- Displayed real-time smoke readings
- Activated the buzzer when smoke exceeded the threshold
- Alert response was observed within a few seconds
- Portable battery-powered prototype

## Future Scope
- IoT-based remote monitoring
- Wi-Fi/GSM alerts
- Mobile notifications
- Cloud data logging
- Multi-zone monitoring
- Integration with security systems

## Project Files
- `Smoke_Detection.ino` – Arduino source code
- Project report
- Prototype image
- Circuit/block diagrams

## Author
Jonas Benedict V Jose
Electronics and Telecommunication Engineering
Sir M. Visvesvaraya Institute of Technology, Bengaluru

