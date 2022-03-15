## Adafruit VL53L4CD Time of Flight Distance Sensor PCB

<a href="http://www.adafruit.com/products/5396"><img src="assets/5396.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit VL53L4CD Time of Flight Distance Sensor. 

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/5396

### Description

The Adafruit VL53L4CD Time of Flight Sensor is another great Time of Flight distance sensor from ST in the VL5 series of chips, this one is great for shorter distances. The sensor contains a very tiny invisible laser source and a matching sensor. The VL53L4CD can detect the "time of flight", or how long the light has taken to bounce back to the sensor. Since it uses a very narrow light source, it is good for determining distance of only the surface directly in front of it. Unlike sonars that bounce ultrasonic waves, the 'cone' of sensing is very narrow. Unlike IR distance sensors that try to measure the amount of light bounced, the VL53 is much more precise and doesn't have linearity problems or 'double imaging' where you can't tell if an object is very far or very close.

This is another 'big sister' of the VL6180X ToF sensor and can handle about ~1 to 1300mm of range distance: basically it combines the short range of the VL6180X in that it can sense up to the body of the sensor, with the increased range of the VL53L0X, which can handle about 50mm to 1200mm of range distance.

The sensor is small and easy to use in any robotics or interactive project. Since it needs 2.8V power and logic we put the little fellow on a breakout board with a regulator and level shifting. You can use it with any 3-5V power or logic microcontroller with no worries. Works great with the 3.3V logic level of a Feather or Raspberry Pi, or the 5v level of a Metro 328 or Arduino Uno, this breakout is ready to work with most common microcontrollers or SBCs. and since it speaks I2C, you can easily connect it up with two data wires plus power and ground. 

As if that weren't enough, we've also added SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder. Just wire up to your favorite micro with a plug-and-play cable to get ToF data ASAP. For a no-solder experience, just wire up to your favorite micro, like the STM32F405 Feather using a STEMMA QT adapter cable. The Stemma QT connectors also mean the VL53L4CD can be used with our various associated accessories. QT Cable is not included, but we have a variety in the shop

Communicating to the sensor is done over I2C with an API written by ST, they have an Arduino library with an example for communication here.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution. 
See license.txt for additional details.
