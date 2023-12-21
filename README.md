# Line-Following-Robot

# Line Following Robot

This project is about building a line following robot using Arduino and IR sensors. The robot can detect and follow a black line on a white surface, or vice versa, by adjusting the speed and direction of its motors.

## Project Architecture

![alt text](https://github.com/yashhh16/Line-Following-Robot/blob/main/Project%20Architecture.png)

## Components

The main components of the project are:

- Arduino Uno: The microcontroller board that controls the logic and behavior of the robot.
- IR Sensors: Two infrared sensors that emit and receive IR signals to detect the presence or absence of a line.
- Motor Driver: A module that drives the current and voltage of the motors based on the signals from the Arduino.
- DC Motors: Two motors that rotate the wheels of the robot and enable its movement.
- Power Supply: A battery or adapter that provides 7-12 V DC to power the Arduino and the motor driver.

## Connections

The schematic diagram of the electrical connections is shown in the image below. The connections are as follows:

- The power supply is connected to the switch, which is then connected to the Arduino's VIN and GND pins, and the motor driver's VCC and GND pins.
- The IR sensors are connected to the Arduino's digital pins 2 and 3, for the right and left sensors respectively.
- The motor driver's IN1, IN2, IN3, and IN4 pins are connected to the Arduino's digital pins 4, 5, 6, and 7 respectively.
- The motor driver's OUT1, OUT2, OUT3, and OUT4 pins are connected to the right and left motors respectively.
