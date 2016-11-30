# ESP-WROOM-32-Eagle-Breakout
A breadboard compatible Eagle breakout board for Espressif's ESP32 module ESP-WROOM-32. The ESP32 is a powerful and low-cost Wifi/Bluetooth chip that enables great Internet-Of-Things applications. Studio Sophisti is using this chip in several projects, including a work-in-progress redesign of Ping (http://www.studiosophisti.nl/ping)

The ESP-WROOM-32 can be purchased directly from Espressif or from a distributor like Adafruit: https://www.adafruit.com/product/3320

6 Programmer pins at the bottom of the board are compatible with this FTDI Serial USB Cable: https://www.adafruit.com/products/70

The board contains reverse-voltage protections, 2 buttons (1 for reset and 1 for activating programming mode), and a diode on the RX line so the IC is 5V serial port compatible.

### Partlist

- 2 SPST switches: Farnell 2468741
- 2 10k resistors: Farnell 2130939
- 1 10uF capacitor: Farnell 2494230
- 1 1N4148 diode: Farnell 1466524
- 1 2N2007E mosfet: Farnell 1894721

### Warning
This PCB is currently untested. I will update this repo in a few weeks when I have tested it with a real PCB.

### PCB Preview
![Preview](ESP-WROOM-32-Breakout_Top.png)

Generated with GerberTools from ThisIsNotRocketScience (https://github.com/ThisIsNotRocketScience/GerberTools), thanks Stijn!
