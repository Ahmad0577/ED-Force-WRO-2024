# WRO24 Competition Project - ED Force

## Overview
This project is designed for the WRO24 competition, incorporating advanced sensors, control systems, and vision technologies to achieve optimal performance in robotic tasks such as line tracking, obstacle avoidance, and counting. Our robot integrates a range of components including IMU sensors, dual cameras, and a custom power management system.

## Components and Features

### 9-Axis IMU & Proportional-Integral Steering
We employ a 9-axis IMU (Inertial Measurement Unit) to track the robot’s orientation and motion. This sensor feeds data into our proportional-integral (PI) steering control algorithm, ensuring smooth and responsive directional control based on real-time feedback.

### Power System
Our robot utilizes two independent battery systems:
- **Battery 1**: Directly powers the core components of the 
- **Battery 2**: Connected to a voltage regulator, providing consistent power to more sensitive components and sensors, preventing power dips during high-load conditions.

### Vision Systems
- **HuskyLens Camera**: This AI-powered camera is responsible for detecting lines and counting objects. Its machine learning capabilities allow the robot to adapt to varying conditions and line patterns.
- **Pixy Camera**: Dedicated to obstacle avoidance, the Pixy camera quickly identifies and tracks objects, ensuring the robot can navigate complex environments without.
