# LED Interfacing and Control using Raspberry Pi

## Description
This project demonstrates how to interface and control an LED using Python on a Raspberry Pi 4. It is a beginner-friendly Edge AI/Embedded systems project that introduces GPIO control.

## Objective
To understand how to use GPIO pins of Raspberry Pi for controlling external hardware components like LEDs.

## Hardware Required
* Raspberry Pi 4
* LED
* Resistor (220Ω)
* Breadboard
* Jumper wires

## Software Required
* Python 3
* RPi.GPIO library

## Circuit Connection
* Connect LED positive (long leg) → GPIO pin (e.g., GPIO17)
* Connect LED negative → Resistor → GND

## Installation Steps
```bash
sudo apt update
sudo apt upgrade
sudo apt install python3-pip
pip3 install RPi.GPIO
```

## How to Run
```bash
python3 led_control.py
```

## Working
The Python script uses the RPi.GPIO library to control the GPIO pin. The LED blinks at a fixed interval by setting the pin HIGH and LOW.

## Future Improvements
* Control LED using a web interface
* Add button input for control
* Integrate with IoT platforms
* Voice-controlled LED using Edge AI



