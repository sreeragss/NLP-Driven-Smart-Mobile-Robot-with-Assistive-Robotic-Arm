# NLP-Driven-Smart-Mobile-Robot-with-Assistive-Robotic-Arm
NLP-Driven Smart Mobile Robot with Assistive Robotic Arm
📌 Project Overview

This project is my M.Tech Mini Project (2025) at the College of Engineering Trivandrum.
It introduces a smart mobile robotic assistant designed to support automated grocery shelf navigation and product retrieval using a voice-controlled interface and a 5-DOF robotic arm.

The system enables a user to simply give a voice command such as:

"Pick the red box from Shelf A"

The robot then:

Understands the command using Natural Language Processing (NLP).

Navigates to the correct shelf while avoiding obstacles with ultrasonic sensors.

Detects the target product using computer vision with ArUco markers.

Picks the product with its robotic arm using inverse kinematics.

Returns to the initial/home position with the item.

This project is aimed at assisting elderly and physically challenged individuals, making daily shopping tasks easier and more independent.

⚙️ Features

✅ Voice Command Control using Google Speech Recognition & NLP

✅ Vision-Based Object Detection with OpenCV and ArUco markers

✅ 5-DOF Robotic Arm Control with inverse kinematics

✅ Mobile Base Navigation with ultrasonic sensors for obstacle avoidance

✅ Integration of Raspberry Pi (vision, NLP, navigation) with Arduino UNO (servo actuation)

✅ Autonomous Pick-and-Place Operations with 85% success rate in testing

🛠️ Hardware Used

Mobile Base: 4-wheel DC motor platform with L298N driver

Controller (Navigation + Vision): Raspberry Pi 3B+

Robotic Arm: 5-DOF manipulator with MG996R and SG90 servo motors

Microcontroller (Arm Control): Arduino UNO

Sensors: Ultrasonic sensors (front & rear) for obstacle detection

Camera: USB webcam for ArUco marker detection

Power Supply: 5V, 5A regulated supply + battery pack

💻 Software Stack

Operating System: Raspbian (Raspberry Pi OS)

Programming Languages: Python (main), C++ (Arduino control)

Libraries & Tools:

OpenCV (ArUco marker detection, pose estimation)

NumPy

Google Speech Recognition API (NLP & voice commands)

PySerial (Raspberry Pi ↔ Arduino communication)

Arduino IDE (servo actuation)

🚀 Methodology

Voice Command → NLP Parsing (extract shelf & product info)

Navigation to Shelf (distance-based + ultrasonic obstacle detection)

Product Detection (camera scans for ArUco marker)

Pose Estimation → Inverse Kinematics (compute arm joint angles)

Pick-and-Place Execution (servo movements via Arduino)

Return to Home Position

📊 Results

Detection Accuracy: 95%

IK Success Rate: 90%

Pick-and-Place Completion: 85%

Smooth integration of navigation, vision, and manipulation on a low-cost hardware platform.

🔮 Future Work

SLAM-based autonomous navigation

AI-based object detection (YOLO / MobileNet-SSD) to eliminate dependency on ArUco markers

Adaptive / soft gripper design with force sensors

Improved speech interface with offline NLP support

Multi-object task scheduling and planning

📸 Demo

(You can add images or upload demo GIFs/videos of your robot in action here once available)

👨‍💻 Author

Sreerag S S

M.Tech (Robotics & Automation), College of Engineering Trivandrum

LinkedIn
 | GitHub
