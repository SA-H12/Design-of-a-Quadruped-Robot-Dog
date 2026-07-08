
 Quadruped Robot Dog – Mechanical Design

Project Overview

This project presents the preliminary mechanical design of a simple Quadruped Robot Dog. The robot is designed to achieve stable walking over uneven terrain while maintaining a lightweight and simple mechanical structure suitable for educational and university projects.

⸻
Project Specifications

Parameter	Value
Robot Type	Quadruped Robot Dog
Chassis Length	220 mm
Chassis Width	120 mm
Chassis Height	60 mm
Number of Legs	4
Degrees of Freedom	8 DOF
Leg Length	80 mm + 80 mm
Robot Mass	2 kg
Servo Motors	MG996R / MG995

⸻
 Chassis Design

The robot uses a lightweight rectangular chassis that supports:

* Battery
* Microcontroller
* Servo Motors
* Mechanical Structure

Recommended Materials

* Aluminum
* PLA (3D Printed)

These materials provide a good balance between strength, weight, and ease of manufacturing.

⸻
 Leg Design

Each leg consists of two links:

* Upper Leg: 80 mm
* Lower Leg: 80 mm

The leg includes:

* Hip Joint
* Knee Joint

This simple mechanism provides sufficient flexibility while keeping manufacturing easy.

⸻
Degrees of Freedom (DOF)

Each leg has:

* 1 Hip Joint
* 1 Knee Joint

Therefore:

* 2 DOF per leg
* 4 Legs × 2 DOF = 8 DOF

This configuration offers stable and efficient walking performance.

⸻
Servo Motor Selection

The robot uses MG996R or MG995 servo motors because they offer:

* High torque (10–11 kg·cm)
* Low cost
* Easy Arduino control
* Wide availability
* Suitable for educational projects

⸻
Torque Calculation

Given Data

* Robot Mass = 2 kg
* Load per Leg = 0.5 kg
* Leg Length = 0.08 m

Force

F = m * g

F = 0.5 * 9.81 = 4.9,N

Torque

T = F * L

T = 4.9 * 0.08 = 0.392 N. m

Required Torque ≈ 0.4 N·m

Since the MG996R provides torque greater than this value, it is suitable for this design.

⸻
Stability and Center of Gravity

For maximum stability:

* Place the battery near the center of the chassis.
* Distribute electronic components evenly.
* Keep the center of gravity inside the support polygon during walking.

These considerations reduce the possibility of tipping over.

⸻
 Walking Gait

The selected gait is the Crawl Gait, which provides excellent stability.

Walking Sequence

1. Front Right
2. Rear Left
3. Front Left
4. Rear Right

Only one leg moves at a time while the other three remain in contact with the ground.

⸻

⚠️ Mechanical Challenges

Possible issues include:

* Chassis vibration
* Insufficient motor torque
* Leg slipping
* High power consumption
* Poor weight distribution

Proposed Solutions

* Use lightweight materials.
* Select higher-torque servo motors if needed.
* Add rubber feet for better traction.
* Improve weight distribution.
* Optimize the walking algorithm.

⸻
 Hardware Components

* Arduino
* MG996R / MG995 Servo Motors
* Battery Pack
* Aluminum or PLA Chassis
* Robot Legs
* Fasteners and Bearings

⸻

🎯 Project Objectives

* Design a simple quadruped robot.
* Achieve stable walking.
* Maintain low manufacturing cost.
* Provide a platform for future improvements.

⸻

🚀 Future Improvements

Future versions may include:

* IMU sensor
* Ultrasonic sensor
* Camera module
* Advanced gait planning
* PID control
* ROS integration
* Autonomous navigation

⸻

📄 Conclusion

The proposed design provides a lightweight, stable, and low-cost quadruped robot suitable for educational purposes. The robot uses four legs with a total of eight degrees of freedom, supported by MG996R servo motors capable of delivering the required torque. The mechanical structure, walking gait, and center of gravity have been designed to maximize stability while allowing future expansion with sensors and advanced control algorithms.
