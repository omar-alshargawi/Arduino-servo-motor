🔧 Arduino Servo Motor Controller with Potentiometers
This project demonstrates how to control four servo motors using potentiometers with an Arduino UNO. It’s a simple and effective way to understand analog-to-digital control in embedded systems using real hardware.

🎥 Project Preview


https://github.com/user-attachments/assets/7136a330-3b11-4cd2-b1c6-56ba8bc93984


🎯 Overview
This setup allows each servo motor to respond to the rotation of a corresponding potentiometer. As you turn a potentiometer, its analog signal is read by the Arduino and converted into an angle between 0° and 180°, which directly controls the attached servo.

🧰 Components
1 × Arduino UNO

4 × Servo Motors (e.g., SG90)

4 × 10kΩ Potentiometers

1 × Breadboard

Jumper Wires

USB Cable for Arduino

⚙️ How It Works
Potentiometers are connected to analog pins A0–A3 on the Arduino.

Servo motors are connected to digital PWM pins 5, 6, 9, and 10.

The Arduino reads the analog voltage from each potentiometer and maps it to a servo angle.

Real-time control is achieved through this direct analog-to-angle mapping.

🧠 Key Concepts
Analog-to-digital conversion

PWM control of servos

Mapping analog ranges to angle values

Real-time embedded control

👤 Author

Omar Alshargawi

🔗 LinkedIn Profile
