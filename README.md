# 🤖 NLP-Driven Smart Mobile Robot with Assistive Robotic Arm

![Python](https://img.shields.io/badge/Python-3.7-blue?logo=python)
![Arduino](https://img.shields.io/badge/Arduino-UNO-green?logo=arduino)
![Raspberry Pi](https://img.shields.io/badge/Raspberry%20Pi-3B+-red?logo=raspberrypi)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-orange?logo=opencv)
![License](https://img.shields.io/badge/License-MIT-lightgrey)

---

## 📌 Project Overview  
This is my **M.Tech Mini Project (2025)** at *College of Engineering Trivandrum*.  
It presents a **smart mobile robotic assistant** that:  

- 🎤 Understands **voice commands** using **NLP & Google Speech Recognition**  
- 🚗 Navigates supermarket-style aisles with **ultrasonic obstacle detection**  
- 🎯 Detects products via **computer vision (OpenCV + ArUco markers)**  
- 🦾 Retrieves items using a **5-DOF robotic arm** with inverse kinematics  
- 👵 Designed as an **assistive robot for elderly & physically challenged individuals**  

---

## ✨ Key Features  
✔️ Voice-controlled shopping assistant  
✔️ NLP for natural interaction  
✔️ ArUco marker–based product recognition  
✔️ 5-DOF robotic arm with gripper  
✔️ Autonomous navigation with obstacle avoidance  
✔️ Raspberry Pi + Arduino integration  

---

## 🛠️ Hardware Setup  
| Component            | Specification / Role |
|----------------------|----------------------|
| **Mobile Base**      | 4-wheel DC motor platform (L298N motor driver) |
| **Controller**       | Raspberry Pi 3B+ (NLP, vision, navigation) |
| **Robotic Arm**      | 5-DOF manipulator (3 × MG996R + 3 × SG90 servos) |
| **Microcontroller**  | Arduino UNO (servo control) |
| **Sensors**          | Ultrasonic sensors (front & rear) |
| **Camera**           | USB webcam (ArUco detection & pose estimation) |
| **Power**            | 5V, 5A regulated power supply + battery pack |

---

## 💻 Software Stack  
- **Python 3.7** (control logic, NLP, vision, navigation)  
- **C++ (Arduino IDE)** (servo actuation)  
- **Libraries:**  
  - OpenCV (ArUco marker detection, pose estimation)  
  - NumPy  
  - Google Speech Recognition API  
  - PySerial (Raspberry Pi ↔ Arduino comms)  

---

## 🚀 System Workflow  
1. 🎤 **User Command** → “Pick the red box from Shelf A”  
2. 🧠 **NLP Parsing** → Extracts product + shelf  
3. 🚗 **Navigation** → Robot moves to shelf (distance-based + ultrasonic)  
4. 👁️ **Vision** → Detects ArUco marker, estimates 3D pose  
5. 🦾 **IK + Arm Control** → Computes servo angles, picks product  
6. 🏠 **Return** → Robot goes back to home position  

---

## 📊 Results  
- ✅ **Detection Accuracy:** 95%  
- ✅ **IK Success Rate:** 90%  
- ✅ **Pick-and-Place Success:** 85% (40 trials)  
- 💡 Demonstrated **affordable, modular assistive robotics system**  

---

## 🔮 Future Improvements  
🔹 SLAM-based autonomous navigation  
🔹 AI-driven object detection (YOLO/MobileNet-SSD)  
🔹 Adaptive soft gripper with force sensors  
🔹 Multi-object retrieval task scheduling  
🔹 Better voice interface with offline NLP  

---

## 📸 Demo & Media  
👉   ![two](https://github.com/user-attachments/assets/16dc69cf-2804-424c-8171-89c239281787)
![Bot_Movement_to_Shelf](https://github.com/user-attachments/assets/38791b60-33f4-4553-bc83-c2b7dcc886d1)
![Final_output](https://github.com/user-attachments/assets/5b762158-22e5-4829-9bfd-aab4445fed9c)


---

## 👨‍💻 Author  
**Sreerag S S**  
- 🎓 M.Tech Robotics & Automation, College of Engineering Trivandrum  
- 🌐 [LinkedIn](https://linkedin.com/in/sreerag-s-s-05483a140)  
- 💻 [GitHub](https://github.com/sreeragss)  

---

⭐ If you like this project, don’t forget to **star the repo** and share feedback!  
