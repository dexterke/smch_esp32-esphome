# smch_esp32
Fun demo project for Central Heating Temperature Controller using ESP32 and ESPHome

<p float="left">
  <img height="400" width="350" alt="image" src="https://github.com/user-attachments/assets/7e5af7fa-647e-46b6-993c-fb896e5108e0" /> 
  <img height="400" width="350"  alt="image" src="https://github.com/user-attachments/assets/20f38304-417b-40b9-9dba-a1a6d9f94853" />
</p>

<br>


## Features

This is a fun DIY project for a central heating temperature controller using an ESP32. It integrates multiple temperature sensors - including a Dallas 1-Wire sensor and Xiaomi BLE sensors to monitor different zones (such as Living Room, Kitchen, and Entry Hall). It displays the info and provides a rich on-device user interface via an LCD display with a rotary encoder and menu system. The device can run on its own using its built‑in clock, but it also talks to Home Assistant so can be controlled remotely, it only requires Wifi/Internet at boot time (for [NTP](https://en.wikipedia.org/wiki/Network_Time_Protocol)).


### ESP32Dev

* [doc/esp32dev](doc/esp32dev.md)


### ESPHome

In a nuthsell: a software solution capable to “translate” yaml configurations into firmware that can be flashed onto ESP32 chips. Once running, the firmware automatically exposes sensors, switches, and other components as entities in Home Assistant.
 
* https://esphome.io


### HomeAssistant

A very popular, open-source, home automation platform that can discover and control ESPHome (and many other) devices with minimal configuration (thanks to native API support and auto‑discovery).

* https://www.home-assistant.io

<img width="405" alt="image" src="https://github.com/user-attachments/assets/0372c3ef-679e-45b0-bf2f-06b6585f88fc" />
  


### Xiaomi Mija temperature and humidity sensors (Bluetooth Low Energy)

* [doc/ble_temperature-sensors.md](doc/ble_temperature-sensors.md)


### Dallas 1-Wire temperature sensor

* [DS18S20](doc/ds18s20.md)


### LCD

* [doc/lcd](doc/lcd.md)


### Rotary Encoder with push button switch

* [doc/rotary_encoder](doc/rotary_encoder.md)


### EM Relay board (CH Output)

* [doc/em_relay](doc/em_relay.md)


### OOB PCB

* [doc/breakout_pcb](doc/breakout_pcb.md)


## Code (yml/C++)

* [esp32dev.yaml](esphome/esp32dev.yaml)


## Gallery

* [HomeAssistant](doc/homeassistant.md)
* [smch_esp32](gallery/gallery.md)


## Special thanks

* [Aaron Christophel](https://www.youtube.com/channel/UCY0kJ-Z-811fqTddJ72w-WA)
* [Intermittent technology](https://www.youtube.com/watch?v=K-HG7qs9hK0)

