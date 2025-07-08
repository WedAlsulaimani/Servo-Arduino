# Servo-Arduino

Dual Servo Motor Movement with Arduino Uno:
This  project demonstrates how to control two servo motors in a mirrored motion using the Servo.h library. The setup makes one servo rotate from 0° to 180°, while the other moves in the opposite direction (180° to 0°) simultaneously.

Components Used:
Arduino Uno
2x Servo Motors (SG90 or similar)
Jumper wires
USB cable for programming/powering Arduino

Circuit Connections:
Servo Motor	Signal Pin	VCC (Red)	GND (Brown/Black)
Servo 1	D2	5V	GND
Servo 2	D12	5V	GND


How It Works:
The two servos move in opposite directions.
One loop rotates them from 0→180 and 180→0 respectively.
The second loop brings them back.
This creates a back-and-forth mirrored motion.
