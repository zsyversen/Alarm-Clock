# Alarm-Clock
This project integrates a real-time clock (RTC), LCD display, sensor module, and buzzer to create a smart monitoring system. The device continuously displays the current day, time, and date while responding to sensor input with audible alerts.
# Arduino Smart Clock & Sensor Alert System

## Features
- Displays day, time, and date using an RTC module
- 16x2 LCD display (parallel)
- Sensor input for detecting a condition (gas/light/etc.)
- Buzzer alert when threshold is reached
- Simple and expandable setup

## Components
- Arduino Uno R3  
- 16x2 LCD Display  
- RTC Module (DS1307 or DS3231)  
- Sensor module  
- Active buzzer  
- Breadboard and jumper wires  

## How it works
- The RTC keeps track of time
- Arduino reads the time and updates the LCD
- The sensor continuously sends input
- If the sensor value passes a threshold, the buzzer turns on

## Wiring (general)
- LCD → digital pins  
- RTC → SDA (A4), SCL (A5)  
- Sensor → analog/digital pin  
- Buzzer → digital pin  

## Possible improvements
- Add buttons to set time or alarms  
- Use I2C LCD to reduce wiring  
- Add multiple alerts  
- Store data or logs  

## Image
Add your project image here
