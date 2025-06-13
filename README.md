# Smart_Parking_System_Using_Arduino
🚗 Smart Parking System using Arduino Build an intelligent parking gate controller using IR sensors, a servo motor, and an LCD display – all powered by an Arduino! This system helps manage vehicle entry and exit and shows real-time slot availability.



🛠️ Features

✅ Detects car entry and exit using IR sensors.
✅ Controls entry gate via servo motor.
✅ Displays available parking slots on an LCD.
✅ Displays a "Parking Full" message when slots are full.


🧰 Hardware Requirements

🖥️ Arduino Uno (https://amzn.to/3mhamzG)
👁️‍🗨️ Sensors - IR or ultrasonic for entry & exit (https://amzn.to/3Kjn6P6)
⚙️ Servo Motor (https://amzn.to/3PqtfMt)
📟 LCD Display (https://amzn.to/41tQkCG)
🔌 Jumper wires and breadboard (https://amzn.to/3GvV1SW)

🛒 Optional: You can also add a buzzer 🔊 or LEDs 💡 for alerts and indicators!



💻 Software Requirements

🧠 1. Arduino IDE
📥 Download: https://www.arduino.cc/en/software
✅ Use it to write, compile, and upload code to the Arduino board.
💡 Make sure to install the correct board drivers (e.g., Arduino Uno)

📚 2. Required Arduino Libraries
Install these libraries via Sketch > Include Library > Manage Libraries...
👉LiquidCrystal_I2C - I2C	For controlling the 16x2 LCD with I2C module.
👉Servo - To control the servo motor for gate operation.


🔁 Flow of project

🚗 Car approaches → IR1 triggered.
✅ If space → Servo opens gate, car enters, slots decrease.
📟 LCD updates slot count.
🚙 Car leaves → IR2 triggered.
🔄 Servo opens again, slot count increases.
🔒 Gate closes after every action.


🎯 Project Outcomes

🚗 Efficient Parking Management.
🛡️ Automation & Security.
⚡ Energy Efficient.
🧠 Hands-On Embedded System Skills.



#Arduino #SmartParking #IoT #EmbeddedSystems #Automation #ParkingSolution #SmartCity #EngineeringProject #TechInnovation
