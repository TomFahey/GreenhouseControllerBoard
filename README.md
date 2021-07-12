# GreenhouseControllerBoard
Greenhouse irrigation control and sensor board, based on the ESP32 microcontroller

A simple 2-layer PCB design for an irrigation controller, designed to control up to four 12V solenoid valve water valves, 
based on temperature, humidity and other arbitrary parameters.

Based on the Espressif's popular ESP32 microncontroller, this controller board incorporates a number of features, including:

- Flexible Wi-Fi/Bluetooth control, tracking and automation of plants through open-source Arduino libraries (also compatible with ESPHome)
- Individual control for up to four DC solenoid valves via 2.1mm x 5.5mm barrel jack, with LED status indicators
- 12V DC power input, built-in 3.3V voltage regulation for microcontroller and peripherals, up to 4A load
- High precision temperature, pressure and humidity sensing, using Bosch's BME280 MEMS sensor
- Up to 8 individual 12-bit ADC channels for additional environmental monitoring, such as soil moisture sensors
- An additional 4 GPIO channels, and two I2C connectors for further expansion e.g LED strips (separate power supply required)





