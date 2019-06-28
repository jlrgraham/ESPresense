See the full documentation at [https://jptrsn.github.io/ESP32-mqtt-room/](https://jptrsn.github.io/ESP32-mqtt-room/)

# ESP32-mqtt-room
An ESP32 based presence detection node for use with the [Home Assistant](https://www.home-assistant.io/) [`mqtt_room` component](https://www.home-assistant.io/components/sensor.mqtt_room/) for localized device presence detection.

## Credits
This project would not have been possible without the help of a variety of [folks on GitHub and YouTube.](https://jptrsn.github.io/ESP32-mqtt-room/index.md#credits)

## Getting Started
A full list of instructions is available in the [documentation](https://jptrsn.github.io/ESP32-mqtt-room/index.md#getting-started).

## Home Assistant Configuration
See the [documentation for configuring Home Assistant.](https://jptrsn.github.io/ESP32-mqtt-room/home_assistant.md)

## Trackable Devices
* [Beacon Hardware](https://jptrsn.github.io/ESP32-mqtt-room/beacons.md)
* [Android devices](https://jptrsn.github.io/ESP32-mqtt-room/android.md)
* [iOS devices](https://jptrsn.github.io/ESP32-mqtt-room/index.md#tracking-iphone)
* [Other devices](https://jptrsn.github.io/ESP32-mqtt-room/beacons.md#non-beacon-hardware)

## Development Tasks

### To do
- [ ] Implement Mi Flora data parsing and reporting
- [ ] Save config to SPIFFS
- [ ] Update configuration via MQTT

### Completed
- [x] Implement basic BLE packet discovery
- [x] Implement iBeacon data packet parsing
- [x] Setup instructions in README.md
- [x] Address watchdog issue
- [x] Maximum distance limit (rounded to two decimal places)
- [x] Scan interval Settings
- [x] Implement Over-The-Air (OTA) updates
- [x] Build and upload via [PlatformIO](platformio.org)
