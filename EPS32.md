# Intrusion Detection in Networking on ESP32 with Custom AI

## **Project Overview**
This project focuses on implementing an **AI-based Intrusion Detection System (IDS)** on an **ESP32** to enhance network security. The system uses **packet sniffing and machine learning** to detect malicious activities and prevent unauthorized access.

## **Problems Solved**
1. **Unauthorized Network Access Detection** - Detects unauthorized users and suspicious activities on WiFi networks.
2. **Lightweight AI-Based Intrusion Detection** - Provides a cost-effective, IoT-friendly intrusion detection system without the need for heavy computational resources.

## **How It Works?**
1. **Packet Sniffing:** ESP32 captures network packets in **promiscuous mode**.
2. **Feature Extraction:** Extracts packet attributes such as **size, duration, protocol type, and entropy**.
3. **AI-Based Classification:** The AI model, trained on normal and malicious traffic, classifies packets as safe or suspicious.
4. **Intrusion Alerts:** If an intrusion is detected, an alert is sent via **MQTT, HTTP request, or LED/Buzzer**.
5. **Data Logging:** Logs are stored on an **SD card or cloud** for further analysis.

## **Workflow**
1. **ESP32 captures network packets** in promiscuous mode.
2. **Extracts important packet features** (e.g., size, IP, protocol type).
3. **Feeds the features to the AI model** (running TensorFlow Lite Micro).
4. **AI model classifies packets** as normal or malicious.
5. **Sends alerts** to the server, MQTT broker, or triggers a local warning.
6. **Logs the detected intrusions** for further analysis.

## **Example Use Case**
### **Scenario 1: Unauthorized Device Detection**
- A home WiFi network should allow only authorized devices.
- ESP32 monitors connected devices and detects unknown MAC addresses.
- If an unknown device joins, ESP32 triggers an alert via MQTT to the admin.

### **Scenario 2: Anomaly Detection in IoT Devices**
- A smart home system is controlled via IoT devices.
- If a smart device starts sending abnormal traffic (e.g., high-frequency packets), ESP32 detects the anomaly and blocks the device.

## **Real-Life Applications**
1. **Home and Office Network Security** - Prevents unauthorized access to WiFi networks.
2. **IoT Device Protection** - Identifies compromised IoT devices and prevents attacks such as **DDoS and Man-in-the-Middle (MITM) attacks**.

---
This project provides a **low-cost, AI-driven solution** for network intrusion detection in **homes, offices, and IoT environments**.

