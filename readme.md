# cc2531-flasher-pi
_Flash CC2531 USB dongle from your Raspberry Pi (or any other single-board computer), without an Arduino nor CC Debugger._

## About

CC2531 is probably the cheapest option to control zigbee devices from your raspberry with open source software like [domoticz](https://www.domoticz.com/) or [Home assistant](https://www.home-assistant.io/hassio/).

**[📖 Read the documentation for more details](https://jmichault.github.io/flash_cc2531-dok/)**

You should also consult the [zigbee2mqtt documentation](https://www.zigbee2mqtt.io/).

This repository was forked from [olipoppin/flash_cc2531-master](https://github.com/olipoppin/flash_cc2531-master) and adds generic SBC support along with some other small fixes.

## Dependencies

* [wiringPi](https://github.com/WiringPi/WiringPi)
  * or [wiringpi-gpiod](https://github.com/leso-kn/wiringpi-gpiod) for non Raspberry-SBCs

---

This project is licensed under the GPL v3 license (see LICENSE).
