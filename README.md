Bluetooth Car
Project Overview

The Bluetooth Car is an Arduino-based robotic vehicle that can be controlled wirelessly via a mobile device using Bluetooth. It demonstrates basic robotics concepts, motor control, and wireless communication. Users can drive the car forward, backward, turn left, or turn right through a smartphone app.

Features

Wireless control via Bluetooth

Forward, backward, left, and right movement

LED indicators for status

PWM-based speed control for smooth motion

Ideal for learning Arduino, motor control, and wireless robotics

Hardware Components

Arduino Uno or compatible board

L298N motor driver module

2 DC motors with wheels

HC-05 Bluetooth module

Battery pack (7.4V recommended)

Jumper wires and chassis

Optional LEDs for indicators

Circuit Connections / Pin Mapping
Component	Arduino Pin
Left Motor PWM	5
Right Motor PWM	6
Left Motor Forward	8 (e1)
Left Motor Reverse	9 (e2)
Right Motor Forward	12 (d1)
Right Motor Reverse	7 (d2)
LED Indicator	9
Bluetooth RX/TX	Connect as per module (e.g., 10/11 or 0/1)
Software Requirements

Arduino IDE

Arduino Libraries: SoftwareSerial (for Bluetooth communication)

Installation / Usage

Connect all components as per the circuit connections.

Open BluetoothCar.ino in Arduino IDE.

Upload the sketch to the Arduino board.

Pair your Bluetooth module with a smartphone app (e.g., Arduino Bluetooth Controller).

Use the app buttons to control the car:

Forward

Backward

Left

Right

LED on/off (if implemented)

Code Overview

Motor movement functions: Forward(), Backward(), Left(), Right()

PWM pins control motor speed for smoother motion

Bluetooth serial commands trigger movements from the smartphone app

LED indicates power or activity status

Contributing

Contributions, improvements, and bug fixes are welcome! Fork the repository, make changes, and submit a pull request.
