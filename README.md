[README.md](https://github.com/user-attachments/files/25135968/README.md)
# Smart Gas Leak Detection and Alert System

## Project Overview

This project implements a smart gas leak detection and alert system
using an ESP8266 microcontroller and an MQ-2 gas sensor. The system
continuously monitors gas concentration and alerts users through a
buzzer and LCD display when unsafe levels are detected.

## Components Used

-   ESP8266 (NodeMCU / ESP-12E)
-   MQ-2 Gas Sensor
-   16x2 LCD with I2C Module
-   Buzzer
-   Jumper Wires
-   Breadboard
-   Power Supply (5V)

## System Features

-   Real-time gas level monitoring
-   Audible alert using a buzzer
-   Visual status display on LCD
-   Serial Monitor output for debugging and calibration
-   Adjustable gas detection threshold

## Working Principle

The MQ-2 sensor detects flammable gases and outputs an analog signal
proportional to gas concentration. The ESP8266 reads this value,
compares it with a predefined threshold, and triggers alerts when gas
levels exceed safe limits.

## Software Requirements

-   Arduino IDE
-   ESP8266 Board Package
-   Libraries:
    -   LiquidCrystal_I2C
    -   Wire

## How to Run the Project

1.  Install the required libraries in Arduino IDE.
2.  Connect the components according to the wiring diagram.
3.  Upload the provided Arduino sketch to the ESP8266.
4.  Open the Serial Monitor at 115200 baud rate.
5.  Observe gas values and system status in real time.

## Safety Notes

-   Allow the MQ-2 sensor sufficient warm-up time before use.
-   Do not power the MQ-2 sensor directly from the ESP8266 3.3V pin.
-   Use a stable power supply to avoid system resets.

## Future Improvements

-   Wi-Fi-based alerts (SMS / Email / App notifications)
-   Cloud data logging and visualization
-   Battery backup system
-   Mobile application integration

## Author

Smart Gas Leak Detection and Alert System Project
