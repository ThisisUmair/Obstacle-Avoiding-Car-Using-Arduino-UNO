🚗 Obstacle Avoiding Car Using Arduino UNO
🤖 Project Overview
The Obstacle Avoiding Car is an autonomous robotic vehicle designed to detect and avoid obstacles using ultrasonic sensors and servo motors. This project showcases the integration of sensors, actuators, and microcontrollers to create a self-driving vehicle capable of real-time navigation without human intervention.

🧠 Key Idea
The car continuously scans its surroundings using an ultrasonic sensor mounted on a servo motor. The servo rotates the sensor to check for obstacles in different directions. Based on the measured distances, the Arduino decides the safest route (forward, left, or right) and moves accordingly using DC motors.

🧩 Components Used
Component	Description
🔹 Arduino UNO	The main microcontroller controlling the entire system.
🔹 Ultrasonic Sensor (HC-SR04)	Measures distance to detect obstacles ahead.
🔹 Servo Motor (SG90 or MG995)	Rotates the ultrasonic sensor for multi-directional scanning.
🔹 DC Motors (x2 or x4)	Drives the wheels for motion.
🔹 Motor Driver Module (L298N / L293D)	Controls motor direction and speed via Arduino signals.
🔹 Wheels & Chassis	Provide physical structure and movement.
🔹 Battery Pack	Supplies power to motors and Arduino.
🔹 Jumper Wires & Breadboard	For circuit connections and prototyping.


⚙️ Working Principle
The servo motor sweeps the ultrasonic sensor left, center, and right.
The Arduino UNO calculates the distance of objects in each direction.
If an obstacle is detected within a certain distance (e.g., 15 cm):
The car stops.
The Arduino compares left and right distances.
The car turns toward the side with more free space.
When the path is clear, it moves forward again.
This continuous loop enables the car to move autonomously while avoiding collisions.



💡 Code Highlights
Distance measurement using HC-SR04 ultrasonic sensor.
Servo sweep control using PWM signals.
Logic for directional movement (forward, left, right, stop).
Motor driver control for speed and rotation.
Modular, beginner-friendly Arduino code.


🚀 How to Run
Assemble all components as shown in the circuit diagram.
Connect Arduino UNO to your computer.
Open the .ino file in Arduino IDE.
Select the correct Board → Arduino UNO and Port.
Upload the code.
Power the circuit using a 9V or 12V battery and watch your car navigate obstacles!


📚 Learnings
Sensor integration and real-time data processing.
Working with servo motors and DC motor drivers.
Basics of autonomous robotics and motion control.
Hands-on experience with Arduino programming and electronics.
