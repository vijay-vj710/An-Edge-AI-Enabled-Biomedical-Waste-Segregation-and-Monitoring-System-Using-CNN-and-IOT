# An-Edge-AI-Enabled-Biomedical-Waste-Segregation-and-Monitoring-System-Using-CNN-and-IOT
AI-based waste segregation using ESP32-CAM, Edge Impulse, ESP-NOW and IoT
📌 Project Overview

This project implements an Edge AI-based biomedical waste segregation system using Edge Impulse and IoT.

The system captures waste images using an ESP32-CAM, performs on-device AI inference, and automatically sorts waste into appropriate bins—minimizing latency, internet dependency, and human exposure.

🎯 Objectives

Enable real-time waste classification on edge devices
Reduce dependency on cloud processing
Improve safety in biomedical waste handling
Automate segregation with minimal human intervention

⚙️ Technologies Used

Edge AI Platform: Edge Impulse
Microcontrollers: ESP32-CAM, ESP8266
Programming: C/C++ (Arduino IDE)
Computer Vision: Image Classification (Impulse Design)
IoT Platform: Blynk
Communication: ESP-NOW
Sensors: Ultrasonic Sensor
Actuators: Servo Motors

🧠 Edge Impulse Workflow

Data Collection
Capture biomedical waste images using ESP32-CAM
Data Labeling
Label images into categories (Yellow, Red, Blue, Black)
Impulse Design
Image preprocessing + Feature extraction
Classification block (CNN)
Model Training
Train and validate model in Edge Impulse Studio
Deployment
Export model as Arduino library
Upload to ESP32-CAM

🧩 System Architecture

ESP32-CAM captures image
Edge Impulse model runs locally (on-device inference)
Waste category predicted
Data sent via ESP-NOW to ESP8266
Corresponding servo motor opens bin lid
Ultrasonic sensor checks bin fill level
Status sent to Blynk app

🗂️ Waste Categories
🟡 Yellow – Infectious Waste
🔴 Red – Plastic Waste
🔵 Blue – Glass Waste
⚫ Black – General Waste

🔌 Hardware Components
ESP32-CAM
ESP8266
Servo Motors (4x)
Ultrasonic Sensors (4x)
12V Adapter + Buck Converter
Breadboard & Jumper Wires

💻 Software Implementation
Edge Impulse model integration (Arduino library)
ESP-NOW for low-latency communication
Blynk for IoT dashboard and alerts
Embedded C for hardware control

📊 Key Features
✔️ On-device AI (no cloud required)
✔️ Fast and low-latency inference
✔️ Automatic waste segregation
✔️ Real-time monitoring and alerts
✔️ Energy-efficient and scalable

🚀 Future Enhancements
Improve dataset for higher accuracy
Add object detection (multiple waste items)
Integrate cloud analytics dashboard
Add voice alert system in hospitals

📚 Applications
Hospitals
Diagnostic Labs
Medical Waste Management Units
Smart Cities

🤝 Contributors
Shunmuga Vijayaraja T
Varshan M

📜 License

This project is developed for academic and research purposes.
