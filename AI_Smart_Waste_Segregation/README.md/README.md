AI-Driven Smart Biomedical Waste Segregation System
📌 Project Overview

This project presents an intelligent system for automatic biomedical waste segregation and monitoring using Artificial Intelligence (CNN) and IoT technologies.

The system identifies different types of biomedical waste using image processing and automatically sorts them into appropriate bins, reducing human effort and contamination risks.

🎯 Objectives
Automate biomedical waste segregation
Reduce human exposure to hazardous waste
Improve accuracy using AI-based classification
Provide real-time monitoring using IoT
⚙️ Technologies Used
Embedded Systems: ESP32-CAM, ESP8266
Programming: C, Python
AI Model: Convolutional Neural Network (CNN)
Libraries: OpenCV, TensorFlow / Keras
IoT Platform: Blynk
Sensors: Ultrasonic Sensor
Actuators: Servo Motors
🧩 System Architecture
Waste image captured using ESP32-CAM
Image processed using CNN model
Waste classified into categories
Signal sent to ESP8266
Corresponding bin opens using servo motor
Ultrasonic sensor monitors fill level
Data sent to Blynk for real-time updates
🗂️ Waste Categories
🟡 Yellow – Infectious Waste
🔴 Red – Contaminated Plastic Waste
🔵 Blue – Glassware Waste
⚫ Black – General Waste
🔌 Hardware Components
ESP32-CAM
ESP8266
Servo Motors (4x)
Ultrasonic Sensors (4x)
Power Supply (12V Adapter + Buck Converter)
Breadboard & Connecting Wires
💻 Software Implementation
Image preprocessing using OpenCV
CNN model trained for waste classification
Communication using ESP-NOW protocol
Real-time notification via Blynk app
📊 Features

✔️ Automatic waste detection and sorting
✔️ AI-based classification for high accuracy
✔️ Real-time bin monitoring
✔️ Remote notifications
✔️ Low-cost and scalable system

🚀 Future Enhancements
Improve model accuracy with larger dataset
Add mobile app with advanced analytics
Integrate cloud storage for data tracking
Add voice or alert system for maintenance
📷 Project Demo

(Add your images or demo video link here)

📚 Applications
Hospitals
Clinics
Laboratories
Medical Colleges
🤝 Contributors
Shunmuga Vijayaraja
(Add team members if any)