# Smart-Car-Parking-Sensor-ATmega32
This project implements a car parking sensor system using the ATmega32 microcontroller. It helps drivers detect nearby obstacles and avoid collisions by measuring distance using an ultrasonic sensor and providing visual and audio feedback.


---

## Features

- Distance measurement using HC-SR04 ultrasonic sensor
- Real-time display on 16x2 LCD
- LED indicators (Red, Green, Blue) based on distance
- Buzzer alert for close obstacles
- Real-time processing using ICU (Input Capture Unit)

---

## How It Works

- The ultrasonic sensor sends a signal and waits for the echo.
- The ATmega32 calculates the distance based on time.
- The result is displayed on the LCD.
-  LEDs and buzzer respond based on distance:


### Distance	and Behavior:
- ≤ 5 cm	LEDs blinking + Buzzer ON + "STOP"
- 6–10 cm	All LEDs ON
- 11–15 cm	Red & Green ON
- 16–20 cm	Red ON
- > 20 cm	All OFF


---

## Hardware Components
- ATmega32 Microcontroller
- HC-SR04 Ultrasonic Sensor
- 16x2 LCD Display
- LEDs (Red, Green, Blue)
- Buzzer


---

## System Architecture
- The system follows a layered architecture:
- Application Layer
- Drivers Layer (LCD, Ultrasonic, Buzzer, LED)
- MCU Layer (GPIO, ICU)
 

---

## Technologies Used
- Embedded C
- ATmega32
- GPIO & ICU Drivers
- LCD 4-bit Mode


---

## Objective

To design a simple and efficient parking assist system that improves driver safety using embedded systems.


---
## Demo simulation
