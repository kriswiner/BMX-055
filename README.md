BMX-055
=======
!(https://d3s5r33r268y59.cloudfront.net/44691/products/thumbs/2014-09-22T05:04:54.122Z-BMX055.1.jpg.2560x2560_q85.jpg)

 Demonstrate basic BMX-055 functionality including parameterizing the register addresses, initializing the sensor, 
 getting properly scaled accelerometer, gyroscope, and magnetometer data out. Added display functions to 
 allow display to on breadboard monitor. Addition of 9 DoF sensor fusion using open source Madgwick and 
 Mahony filter algorithms. Sketch runs on the Teensy 3.1.
 
 This sketch is intended specifically for the [BMX055+MS5637](https://www.tindie.com/products/onehorse/bmx-055-9-axis-motion-sensor-add-on-for-teensy-31/) mini add-on shield for the Teensy 3.1.
 It uses SDA/SCL on pins 17/16, respectively, and it uses the Teensy 3.1-specific Wire library i2c_t3.h.
 The MS5637 is a simple but high resolution pressure sensor, which can be used in its high resolution
 mode with power consumption of 20 microAmp, or in a lower resolution mode with power consumption of
 only 1 microAmp. The choice will depend on the application.
 
 This sketch is a work in progress...
