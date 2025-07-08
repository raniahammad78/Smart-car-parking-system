🚗 Smart Car Parking System
📌 Overview
The Smart Car Parking System is an automated solution designed to manage and monitor parking spaces efficiently. It leverages hardware components such as Arduino, IR sensors, servo motors, and LCD displays to detect the availability of parking spots and guide vehicles accordingly. This project aims to reduce traffic congestion, save time, and optimize parking in real-time.

🎯 Features
🔍 Real-time Detection of parking space availability using IR sensors.

📟 LCD Display to show the number of available and occupied slots.

🚦 Automated Barrier Gate using a servo motor to control vehicle entry.

💡 LED Indicators for visual guidance (Green: Available, Red: Occupied).

🔋 Low Power Consumption and cost-effective components.

⚙️ Modular Design – easily expandable to larger parking systems.

🔧 Hardware Used
🧠 Arduino Uno / Nano

📍 IR Sensors for car detection

🧲 Servo Motor to act as an entry gate

💡 LEDs (Red & Green) for status indication

📺 16x2 LCD Display to show real-time slot availability

🔌 Power Supply (Battery or Adapter)

🧵 Jumper Wires, Breadboard, Resistors

📐 System Design
The system is divided into the following components:

Entrance Monitoring:
IR sensor detects incoming cars → Arduino checks slot availability → If available, opens gate via servo.

Slot Monitoring:
Each parking slot is equipped with an IR sensor to detect car presence and update the display.

Display Unit:
The number of available and occupied slots is shown on the LCD display at the entrance.

🧠 How It Works
A car arrives at the parking entrance.

The entrance IR sensor detects the car.

The Arduino checks if any slot is available:

✅ If available: the gate opens automatically.

❌ If full: gate remains closed, and display shows "Parking Full".

As the car enters and parks, slot sensors update the availability status in real-time.

LEDs and LCD display provide visual feedback.

