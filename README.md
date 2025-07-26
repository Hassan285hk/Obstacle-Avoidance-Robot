🤖 **Obstacle Avoidance Robot Car**

📌 **Project Overview**

This project is an autonomous obstacle avoidance robot car designed to navigate its environment without human intervention. Using distance sensors, it detects obstacles in its path and changes direction to avoid collisions.

🚗**Key Features**

✅ Autonomous Navigation: Moves forward until an obstacle is detected.

✅ Obstacle Detection: Uses ultrasonic/IR sensors to detect objects.

✅ Automatic Steering: Changes direction to avoid obstacles.

✅ Microcontroller Controlled: Built using Arduino or a similar microcontroller.

✅ Reusable Code: Easily adaptable for different robot car setups.

✅ Compact Design: Designed for small-scale robotics projects.

🛠️ **Technologies & Components**

**Microcontroller:** Arduino UNO / Nano (or compatible)

**Sensors:** Ultrasonic sensor (e.g., HC-SR04) or IR sensors

**Motor Driver:** L298N / L293D motor driver module

**Chassis:** 2 or 4-wheel robot chassis kit

**Motors:** DC geared motors

**Power Supply:** Battery pack (Li-ion or AA)

**Programming Language:** Arduino C/C++

📂 **Repository Structure**

**Obstacle-Avoidance-Robot/**

│
├── /code/           # Arduino sketches (.ino files)

├── /schematics/     # Circuit diagrams or Fritzing files

├── /images/         # Photos of the robot

├── README.md        # Project documentation

🚦 **How It Works**

The ultrasonic sensor measures the distance to obstacles.

If an obstacle is closer than a set threshold, the robot stops and decides to turn left or right.

Once clear, the robot moves forward again automatically.

⚙️ **How to Use**

Clone this repo:

Open the .ino file in the Arduino IDE.

Connect the Arduino to your computer.

Upload the code to your Arduino board.

Power the robot with a battery pack.

Place it on the floor — watch it avoid obstacles!

✨ **Possible Improvements**

-Add Bluetooth or Wi-Fi remote control.

-Use multiple sensors for 360° obstacle detection.

-Implement path planning for smarter navigation.

=Add a camera module for computer vision.
