🚗 Smart Car Parking System (4 Slots)
This project is a Smart Car Parking system built using Arduino and ultrasonic sensors. It monitors the availability of 4 parking slots and automatically manages access: if all slots are full, the system displays “Full”; otherwise, it opens the parking gate.

🎯 Project Overview
Detects car presence using ultrasonic sensors at each of the 4 slots.

If any slot is available, the gate opens (via servo motor or relay).

If all 4 slots are occupied, the system displays "Parking Full" and keeps the gate closed.

Ideal for small smart parking or automation demos.

🛠️ Tech Stack
Component	Description
Microcontroller	Arduino Uno
Sensors	4x HC-SR04 Ultrasonic Sensors
Actuator	Servo Motor (for gate) or Relay
Display (Optional)	LCD or Serial Monitor
Logic	Arduino C++

🔧 How It Works
Each of the 4 slots has an ultrasonic sensor to detect if a car is parked.

If even one slot is empty, the gate opens automatically.

If all slots are full, a message is displayed and the gate remains closed.

The system updates status in real-time.

📁 Files Included
Aurdino.cpp – Arduino code for full parking detection and gate control

🚀 Setup Instructions
Connect 4 ultrasonic sensors to Arduino (one for each slot).

Connect a servo motor to control the gate.

Upload the smart_parking.ino sketch using Arduino IDE.

Power the Arduino and monitor slot status in real-time.

📌 Use Cases
Smart parking solutions for malls, offices, or homes

Educational IoT or automation projects

Prototype for larger parking systems
