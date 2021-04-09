# AltimeterFio
A SparkFun BME280 board backpack for Arduino Fio

This board adapts the [SparkFun BME280](https://github.com/sparkfun/SparkFun_BME280_Breakout_Board) to an [Arduino Fio](https://github.com/sparkfun/Arduino_Fio).
The board is intended to be mounted to the back of the Arduino Fio, at the same side where the XBee is mounted.

The board allows the Fio to become an Altimeter with downlink. A microcontroller on the ground will be able to get the sensor data wirelessly through XBee, and calculate the altitude.
The entire system will be used on my future rocketry projects, but can be easily adapted with model aircraft and other UAV.

## Libraries
Since this board is basically an extension of the SparkFun BME280, it should work with the same library as the original.
* [SparkFun BME280 Library](https://github.com/sparkfun/SparkFun_BME280_Arduino_Library)

## Thanks
Big thanks to [SparkFun](https://github.com/sparkfun) for providing Open Source documentation to their BME280 board.
I added a SparkFun logo on the board as a token of gratitude.

## License
This work is licensed under the Creative Commons Attribution-ShareAlike 4.0 International License. To view a copy of this license, visit http://creativecommons.org/licenses/by-sa/4.0/ or send a letter to Creative Commons, PO Box 1866, Mountain View, CA 94042, USA.
