## Adafruit ISM330DHCX + LIS3MDL FeatherWing - High Precision 9-DoF IMU PCB

<a href="http://www.adafruit.com/products/4569"><img src="assets/4569.jpg?raw=true" width="500px"><br/>
Click here to purchase one from the Adafruit shop</a>

PCB files for the Adafruit ISM330DHCX + LIS3MDL FeatherWing - High Precision 9-DoF IMU.

Format is EagleCAD schematic and board layout
* https://www.adafruit.com/product/4569

### Description

Upgrade any Feather board with precision motion sensing with the ST 9-DoF IMU, an all-in-one sensing 'Wing. It sports two fantastic sensors from ST to provide 9 degrees of full-motion data.

The ST ISM330DHCX is an industrial quality Accelerometer+Gyroscope 6-DOF IMUs (inertial measurement unit). This IMU sensor has 6 degrees of freedom - 3 degrees each of linear acceleration and angular velocity at varying rates within a respectable range. For the accelerometer: ±2/±4/±8/±16 g at 1.6 Hz to 6.7KHz update rate. For the gyroscope: ±125/±250/±500/±1000/±2000/±4000 dps at 12.5 Hz to 6.7 KHz. In particular, this is one of the few gyro's we stock with 4000 dps range, usually they top out at 2000. This sensor has extra calibration and compensation circuits to give it excellent performance in a wide environmental range from -40 to +105°C. Most other IMU sensors don't have industrial temperature ranges or have wide accuracy variation as the temperature changes. The accelerometer and gyroscope also are on the same silicon die, which will keep the 6 measurements synchronized better than when the two sensors are on separate dies.

There are also some nice extras, such as built-in tap detection, activity detection, pedometer/step counter and a programmable finite state machine / machine learning core that can perform some basic gesture recognition.

It also includes a LIS3MDL 3-axis magnetometer that can sense where the strongest magnetic force is coming from, generally used to detect magnetic north. The three triple-axis sensors add up to 9 degrees of freedom, by combining this data you can orient the board. Check out our guide on how to do that!

Both sensors are connected over the shared I2C bus, so you can use it with any and all Feathers! We also break out the interrupt pins and address-selection jumpers in case you want multiple Feathers or have I2C address conflicts. We've got both Arduino (C/C++) and CircuitPython libraries available so you can use it with any Feather board and get data readings in under 5 minutes. Four mounting holes make for a secure connection.

Additionally, since it speaks I2C you can easily connect it up with two wires (plus power and ground!).  We've even included SparkFun qwiic compatible STEMMA QT connectors for the I2C bus so you don't even need to solder! Just wire up to your favorite micro like the STM32F405 Feather with a plug-and-play cable to get 9 DoF data ASAP. You can change the I2C addresses on the back using the solder jumpers, to have two of these sensor boards on one bus.

We also wrote libraries to help you get these sensors integrated with your Arduino/C++. This library covers the accel/gyro and this library is for the magnetometer.

Check out the learning guide here for more information like schematics, wiring diagrams and code libraries.

### License

Adafruit invests time and resources providing this open source design, please support Adafruit and open-source hardware by purchasing products from [Adafruit](https://www.adafruit.com)!

Designed by Limor Fried/Ladyada for Adafruit Industries.

Creative Commons Attribution/Share-Alike, all text above must be included in any redistribution.
See license.txt for additional details.
