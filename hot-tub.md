---
layout: default
---

# Hot Tub Thermostat

See: [MikkoTervala/hot-tub-thermostat](https://github.com/MikkoTervala/hot-tub-thermostat)

Digital temperature controller for an outdoor hot tub with wireless bluetooth temperature sensor.

# Specifications

* ESP-32 microcontroller
* LCD display
* Waterproof buttons for outdoor installation
* Wireless Bluetooth LE temperature sensor
    * Inkbird IBS-TH1 with external temperature sensor
* Software written using esphome
    * A new feature was implemented to esphome for the temperature sensor. See: https://github.com/esphome/esphome/pull/1983

# Functionality

The system acts as a thermostat controlling temperature of an outdoor hot tub. The hot tub is heated with a natural gas instant lake water heater. As temperature goes down, the thermostat will let more hot water in. The thermostat will be installed near the water heater, so a wireless temperature sensor is used to avoid wires.

![Complete device](https://raw.githubusercontent.com/MikkoTervala/hot-tub-thermostat/main/images/complete_device.jpeg)
![Electronics](https://raw.githubusercontent.com/MikkoTervala/hot-tub-thermostat/main/images/electronics.jpeg)