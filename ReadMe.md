# Watering Plants with Arduino

Set up arduino to water your Plants once a day!


## Hardware components


* Arduino Uno
* 128x64 OLED display
* Relay module
* Submersible Pump
* keypad


### Wiring to the first arduino

* OLED screen:
  * OLED GND pin to ground
  * OLED VCC to 5V
  * OLED SCL pin to A5
  * OLED SDA pin to A4
  * Check this nice To learn how to setup an OLED display and install useful libraries: [OLED tutorial](http://www.instructables.com/id/Monochrome-096-i2c-OLED-display-with-arduino-SSD13/ )

* Relay:
  * relay pin to digital pin 11
  * the power supply of the submersible pump must be connected to this relay

* DS3231 Clock
  * GND to ground
  * Vcc to 5V
  * SCL to SCL in arduino
  * SDA to SDA in arduino

  * Keypad
    * pin from 2 to 9


* Python 2.7
  * datetime
  * time
  * bluetooth
  * apscheduler
  * json
  * flask
  * psutil
  * os
  * json
  * time


## Instructions

A: set watering time (E.g. If you want to water plants at 8 am press A+0+8 )
B: set watering duration (E.g. if you want to water plants for 6 seconds press B+6)
C: set time and date(E.g. if it is 9:56 of the 28th June 2018 press: C+0+9+5+6+2+8+0+6+1+8)
*: water now
‘D’ and ‘#’: push them if you dare!


## License


## Acknowledgments

The project was inspired by this post in [hackster.io](https://www.hackster.io/ben-eagan/raspberry-pi-automated-plant-watering-with-website-8af2dc)
