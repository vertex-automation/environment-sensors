# Environment Sensors Lite

## Overview
The **Environment Sensors Lite** is a smart IoT device for monitoring ambient light and WiFi signal strength. It supports Home Assistant integration and OTA updates for easy firmware management.

## Features
- **I2C Sensor:** BH1750 for ambient light monitoring.
- **OTA Updates:** Simple firmware management via GitHub Pages.
- **ESP32 Integration:** Built on the ESP32-C3 DevKitM-1 platform.

## Installation
1. Clone this repository or download the latest firmware from [Releases](https://github.com/vertex-automation/environment-sensors/releases).
2. Flash the firmware using ESPHome or an ESP32 flashing tool.
3. Configure the device in Home Assistant.

## Configuration
- You can provide custom values for the device name and friendly name during installation.
- Adjust update intervals or logging levels as needed in the substitutions section.

## License
This project is licensed under the [MIT License](LICENSE).
