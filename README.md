# PID Line Following Robot

## Overview
This project is a high-speed PID controlled line-following robot designed using a custom chassis in Fusion 360.

## Features
- PID control algorithm
- 8-sensor reflectance array
- encoder motors
- custom chassis
- high-speed control loop

## Hardware
Arduino Uno
TB6612 Motor Driver
QTR-8RC sensor array
Pololu micro metal gearmotors

## Robot Architecture
Sensors → PID Controller → Motor Driver → Motors

## CAD Design
The chassis was designed in Fusion 360 to optimize sensor placement and center of gravity.

## Results
Top speed: ~1.5 m/s  
Control loop: ~300 Hz

## Future Improvements
Add wheel odometry
Integrate ROS
Implement adaptive speed control
