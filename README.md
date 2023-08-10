ESPHome RD-01 mmWave Radar Sensor Custom Component

## Installation
Set wifi_ssid and wifi_password in your esphome's secrets.yaml first

1. Place rd01_uart.h into the components of your esphome configuration folder
2. Create new device with the yaml in this repository

## Wiring
ESP8266  | | RD-01
---------|-|-------|
3.3V    |<->| 3.3V
GND     |<->| GND
TX      |<->| GPIO7_RX
RX      |<->| GPIO16_TX
RTS     |<->| GHIP_EN
