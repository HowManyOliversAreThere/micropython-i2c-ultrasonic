# MicroPython I2C Ultrasonic

This is a [MicroPython](https://micropython.org) driver for the [M5 Ultrasonic Distance Unit I2C (RCWL-9620)](https://shop.m5stack.com/products/ultrasonic-distance-unit-i2c-rcwl-9620).

The only feature is to read the distance, which is returned in milimetres. Note that the maximum read distance of the sensor is 4500 mm, and so a reading of this maximum value can be assumed to be incorrect.

See the `examples` folder for examples for MicroPython versions 1.11 and 1.19.
