Health Monitoring with M5 Stack

Overview

This project implements a health monitoring system using the M5 Stack, a versatile and compact IoT development kit. The system is designed to monitor various health metrics such as heart rate, temperature, and oxygen levels. It provides a user-friendly interface for real-time monitoring and logs data for further analysis.

Features

Real-time Monitoring: Displays health metrics such as heart rate, temperature, and SpO2 in real time.

Data Logging: Logs health data for later analysis or sharing with healthcare providers.

Alerts: Configurable alerts for abnormal readings.

Portability: Compact and easy to carry.

Customizable Interface: Easy to modify UI to display desired metrics.

Hardware Requirements

M5 Stack Core: ESP32-based IoT development kit.

Sensors:

Pulse Oximeter (e.g., MAX30100 or MAX30102)

Temperature Sensor (e.g., DS18B20 or DHT22)

Optional: Additional sensors as needed.

Accessories:

USB-C cable for power and programming.

Battery pack (optional for portability).

Software Requirements

Development Environment:

Arduino IDE (preferred) or PlatformIO.

M5 Stack libraries installed in the IDE.

Additional sensor libraries (e.g., Adafruit MAX30102 library).

Dependencies:

M5Stack.h

Wire.h

Sensor-specific libraries.

Usage

Power on the M5 Stack.

The system initializes and starts displaying real-time health metrics.

Use the physical buttons on the M5 Stack to navigate through options (e.g., start/stop monitoring, view logs).

Data is saved locally or transmitted to a connected server/cloud if configured.

Acknowledgements

M5 Stack Documentation

Adafruit Sensor Libraries

Contact

For any questions or support, please contact:

shantanuundepatil@gmail.com

GitHub: subtlemortal
