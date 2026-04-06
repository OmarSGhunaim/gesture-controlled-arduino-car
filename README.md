# Gesture-Controlled Robot Car

## Objective
Control a robotic car using hand gestures through motion sensing and wireless communication.

## What this project does
- Detects hand movement using MPU6050
- Transmits motion data wirelessly using nRF24L01
- Controls car movement based on gestures
- Enables real-time interaction with the robot

## Steps performed
1. Captured motion data using MPU6050
2. Processed gesture input on Arduino (transmitter)
3. Sent data wirelessly via nRF24L01
4. Received signals on Arduino (receiver)
5. Controlled motors using motor driver

## Example
Input: Hand tilt forward  
Output: Car moves forward  

## Components used
- Arduino Uno (Transmitter)
- Arduino Mini Nano (Receiver)
- MPU6050 Sensor
- nRF24L01 Modules
- L298N Motor Driver
- DC Motors (4x)

## Tools used
- Arduino IDE
- Embedded C/C++

## Demo
Project Demo Video:  
file:///C:/Users/Gamer/Downloads/Gesture-Controlled-Car.mp4
