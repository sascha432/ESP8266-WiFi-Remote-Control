# ESP8266-WiFi-Remote-Control

## Features

- <15µA stand-by current / up to 4 years stand-by time - or 1 year stand-by, used 10-20 times per day
- Integrated 1A USB charger
- Optional battery protection (<17µA total)
- 4 LED indicators (Charging, charging finished, button pressed, MCU controlled LED)
- Buffered buttons and no noticeable delay when waking up from deep sleep using quick connect
- Battery charging and discharging curves

## Functions

- 27 functions with 4 hardware buttons
- Short press, long press, repeat
- 2 button combo - hold one button, second button - short press, long press, repeat
- Configurable long press and repeat time
- Hold button 4 > 7 seconds, button 1-3 - disable auto sleep, reset device, restore factory settings
- Switch to disconnect the battery - device can still be used when USB powered
- Auto sleep timer 1 - 255 seconds
- Auto wake up to report battery state

## Firmware

Any Arduino sketch is supported. The basic functionality can be implemented with a few dozends lines of code.

Alternativly the KFC Firmware is available with Web interface, MQTT and Home Assistant integration, OTA updates etc...

[KFC Firmware @ Github](https://github.com/sascha432/esp8266-kfc-fw)

![Remote Control](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/images/remote2.jpg)

![Home Assistant](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/images/hass2.jpg)

## Schematics

### Rev 1.3

[EasyEDA](https://easyeda.com/sascha23095123423/iot_4ch_remote)

![Schematics Thumbnail](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/schematics/Schematic_IoT_4_button_WiFi_Remote_Control_4_button_WiFi_remote_control_20200223151726.png)
[Schematics](https://github.com/sascha432/ESP8266-WiFi-Remote-Control/blob/master/schematics/Schematic_IoT_4_button_WiFi_Remote_Control_4_button_WiFi_remote_control_20200223151726.svg)

## Some images

![Remote Control PCB Rev1.1](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/images/remote_control_pcb_rev1.1.jpg)

![First Prototype](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/images/IMG_0125.JPG)

## 3D printable enclosure

33.33x88.88x14.0mm, 2 parts, ~11gram, 4 screws, 0.15mm layer height recommended

![Housing](https://raw.githubusercontent.com/sascha432/ESP8266-WiFi-Remote-Control/master/images/housing.jpg)

Coming soon...
