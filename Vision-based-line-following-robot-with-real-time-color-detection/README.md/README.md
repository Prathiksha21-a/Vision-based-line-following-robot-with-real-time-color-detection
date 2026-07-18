#  Vision-Based Line Following Robot with Real-Time Color Detection

##  Overview

This project presents a Vision-Based Line Following Robot developed using ESP32, ESP32-CAM, OpenCV, and IR sensors. The robot autonomously follows a predefined path while detecting Red, Green, and Blue color stations in real time using computer vision. Upon detecting a predefined color, the robot pauses briefly before resuming navigation, simulating station-based operations in an autonomous robotic system.

The project demonstrates the integration of embedded systems, computer vision, and wireless communication for intelligent robot navigation.

---

## Features

- Autonomous line following using IR sensors
- Real-time color detection using ESP32-CAM and OpenCV
- Detection of Red, Green, and Blue color stations
- Automatic stop at detected color stations
- Resumes navigation after a short delay
- Serial communication between the vision system and ESP32
- Live video streaming over Wi-Fi

---

##  Hardware Used

- ESP32 Development Board
- ESP32-CAM Module
- L298N Motor Driver
- IR Sensor Array
- DC Geared Motors
- Robot Chassis
- Li-ion Battery

---

##  Software Used

- Arduino IDE
- Python
- OpenCV

---

##  Working Principle

1. The IR sensors detect and follow the black line.
2. The ESP32 controls the robot's movement.
3. The ESP32-CAM streams live video to the computer over Wi-Fi.
4. Python and OpenCV process the video to detect Red, Green, and Blue colors.
5. When a predefined color is detected, a command is sent to the ESP32.
6. The robot stops briefly at the detected station.
7. The robot automatically resumes navigation.

---

##  Applications

- Warehouse automation
- Educational robotics
- Smart manufacturing
- Autonomous Guided Vehicle (AGV) concepts
- Indoor autonomous navigation

---

##  Technologies Used

- ESP32
- ESP32-CAM
- OpenCV
- Python
- Arduino
- Computer Vision
- Embedded Systems
- Robotics

---

##  Future Improvements

- QR code-based navigation
- Obstacle avoidance
- AI-based object detection
- IoT monitoring
- Autonomous delivery functionality