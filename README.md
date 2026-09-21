# **SAIROS: AI-Powered Underground Mine Safety, Monitoring and Rescue Rover.**

Smart India Hackathon 2026

### About the project:

SAIROS is a six-wheel ground rover being developed for underground mine safety, monitoring and rescue support.

The main idea is to send the rover into a mine area where it may not be safe for a person to enter immediately. The rover collects information about the surroundings using gas sensors, environmental sensors, camera, ultrasonic sensors and LiDAR. The collected information is processed and sent to a base station through a wireless mesh network.

### Problem Statement:

Underground coal mines can have hazardous conditions such as toxic gases, low oxygen levels, poor visibility, high temperature, obstacles, flooding and mine collapses. During an emergency, the rescue team may not have enough information about the affected area before entering it.

Entering an unknown mines section can expose rescue personnel to additional risks. It can also taken time to understand what has happened inside the mine.

The problem  statement therefore requires a system that can  operate in the hazardous underground environments, monitor mine conditions, provide visual information, detect hazards,assist in locating trapped workers and help rescue teams make better decisions.

### Proposed Solution

SAIROS is a six-wheel AI-Powered ground rover developed for underground mine safety, monitoring and rescue support. The rover carries gas sensors, temperature and humidity sensors, thermal and low-light camera, ultrasonic sensors and YDLiDAR X2. It collects information from the underground environment and sends data to base station. The Raspberry Pi 4 and ESP32 acts as a main controlling unit. YOLOv8 is used for AI-based person detection while OpenCV is used for image and video processing. For underground mine communication, TP-Link Archer Wi-Fi nodes are used to create a multi-hop mesh network. MQTT is used for transmitting data and alerts to the monitoring system.


