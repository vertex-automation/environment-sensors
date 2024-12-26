# Environment Sensors Lite

## Overview
The **Environment Sensors Lite** is a smart IoT device for monitoring ambient light, infrared light, full-spectrum light, and WiFi signal strength. It is fully integrated with Home Assistant and supports OTA updates for seamless firmware management.

## Features
- **I2C Sensor:** VEML7700 for detailed ambient light, infrared, and full-spectrum light monitoring.
- **WiFi Signal Strength Monitoring:** Tracks the device's connectivity strength.
- **OTA Updates:** Easily manage firmware updates via GitHub Pages or Home Assistant.
- **ESP32 Integration:** Powered by the ESP32-C3 DevKitM-1 platform, ensuring reliable performance.
- **Bluetooth Proxy:** Extend Home Assistant's Bluetooth range with built-in proxy support.

## Installation
1. Clone this repository or download the latest firmware from [Releases](https://github.com/vertex-automation/environment-sensors/releases).
2. Flash the firmware using ESPHome or an ESP32 flashing tool.
3. Add the device to Home Assistant for seamless integration.

## Supported Sensors
- **Ambient Light (lx):** Measures the illuminance of visible light.
- **Infrared Light (lx):** Tracks the intensity of infrared light.
- **Full Spectrum Light (lx):** Captures light across the full spectrum.
- **Ambient Light Counts (#):** Raw counts from the light sensor.
- **WiFi Signal Strength (dBm):** Diagnostics for wireless connectivity.
