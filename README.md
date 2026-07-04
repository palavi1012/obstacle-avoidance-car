🤖Obstacle Avoidance Car

An autonomous obstacle avoidance robot built using **Arduino UNO SMD**, designed to detect and avoid obstacles without human intervention. This project combines embedded systems, sensor integration, and motor control to demonstrate the fundamentals of autonomous robotics.

📌Project Overview

The robot continuously scans its surroundings using an **HC-SR04 Ultrasonic Sensor** mounted on a **Servo Motor**. When an obstacle is detected within a predefined distance, the servo rotates to scan both the left and right sides. Based on the measured distances, the robot chooses the clearer path and continues moving autonomously.

✨ Features

- Autonomous obstacle detection and avoidance
- Distance measurement using an HC-SR04 Ultrasonic Sensor
- Servo-based environmental scanning
- Differential drive using DC motors
- Intelligent left/right path selection
- Arduino-based embedded programming

🛠️ Components Used

- Arduino UNO SMD
- HC-SR04 Ultrasonic Sensor
- SG90 Servo Motor
- L298N Motor Driver
- 4 × BO DC Motors
- Cardboard
- Wheels
- Battery Pack
- Jumper Wires

⚙️Working Principle

1. The robot moves forward continuously.
2. The ultrasonic sensor measures the distance ahead.
3. If an obstacle is detected within the mentioned distance, the robot stops.
4. The servo rotates the ultrasonic sensor to scan the left and right sides.
5. The Arduino compares both distances.
6. The robot turns toward the side with more free space.
7. It resumes forward movement and repeats the process.
   
💡Skills Learned

- Arduino Programming
- Embedded Systems
- Sensor Integration
- Motor Control
- Robotics Fundamentals
- Debugging Hardware & Software
- Problem Solving



