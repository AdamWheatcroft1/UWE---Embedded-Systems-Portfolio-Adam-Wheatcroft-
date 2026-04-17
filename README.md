# Embedded Systems Portfolio – Adam Wheatcroft

This repository contains all code developed for the Embedded Systems module at UWE Bristol.
The work covers Labs 1–8 and demonstrates the development of a Smart Home System using an STM32 NUCLEO board.

## Overview

The portfolio progresses from simple LED control to a fully integrated embedded system including:

* Digital I/O control
* Serial communication
* Sensor interfacing
* LCD display via I2C
* DC motor control using relays
* SD card data logging

Each lab builds on previous work, forming a complete embedded system.

## Repository Structure

```
Lab 1 – Blinky LED
Lab 2 – Smart Home System (Initial Implementation)
Lab 3 – Serial Communication
Lab 4 – Sensors, Potentiometer and Buzzer
Lab 5 – Matrix Keypad and RTC
Lab 6 – LCD Display (I2C Communication)
Lab 7 – DC Motor Control using Relays
Lab 8 – SD Card Storage and File Handling
```

Each folder contains:

* Source code (`main.cpp` and modules)

## Key Features

* Real-time monitoring via serial communication
* Sensor-based decision making (temperature, gas, PIR)
* User interaction through keypad and LCD
* Automated and manual control modes
* Data logging using FAT file system on SD card

## Notes

All code was developed using Mbed Studio and tested on the STM32 NUCLEO platform.
