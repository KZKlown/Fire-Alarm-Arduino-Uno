# Fire-Alarm-Arduino-Uno
# Wokwi Fire Alarm Arduino Uno

## Team Information

**Team Members**
- Kent Zheng (Team Leader)
- Caden Brown
- Nathanael Price

## Project Description

The **Automatic Fire Alarm System** is designed to detect potential fire conditions in enclosed spaces such as classrooms, offices, and other buildings.

The system uses:
- A smoke/gas sensor to detect smoke
- A temperature sensor to detect heat levels

When both sensors reach their programmed threshold values, the Arduino Uno microcontroller will automatically activate the alarm system.

### Features

- Automatic fire detection using smoke/gas and temperature sensors
- Manual alarm activation through a switch
- Audible warning using a buzzer
- Visual alert using a red LED
- Alarm remains active until manually reset

### System Operation

1. The smoke/gas sensor continuously monitors the air for smoke.
2. The temperature sensor continuously measures the air temperature.
3. If both sensor readings exceed their predefined thresholds, the alarm is triggered automatically.
4. A manual switch allows users to activate the alarm regardless of sensor readings.
5. When activated:
   - The buzzer emits an audible warning.
   - The red LED illuminates to provide a visual alert.
6. The alarm remains active until the manual switch is returned to its reset position.

## Platform

- Arduino Uno
- Wokwi Simulator

## Purpose

This project demonstrates a simple and effective fire detection and warning system that combines multiple sensing methods to improve reliability and provide both audible and visual emergency alerts.
