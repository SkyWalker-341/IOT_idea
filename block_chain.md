# AI-Enabled Blockchain Security Framework for Autonomous IoT Devices

## Introduction
IoT devices are increasingly used in critical applications like **smart cities, healthcare, and industrial automation**. However, they face two major problems:

1. **Security Threats:** IoT devices are vulnerable to cyberattacks due to centralized control and lack of real-time threat detection.
2. **Data Integrity Issues:** IoT-generated data can be tampered with, leading to incorrect decisions in critical applications.

Our project introduces an **AI-driven, blockchain-secured IoT network** that autonomously detects and mitigates security threats while ensuring data integrity.

## How It Works
The system consists of three key layers:

### 1. IoT Edge Devices
- Devices (sensors, cameras, smart meters) collect real-time data.
- Uses **lightweight AI models** to detect anomalies (e.g., unauthorized access, faulty readings).

### 2. AI-Powered Security Layer
- **Federated Learning** enables IoT devices to collaboratively train AI models without sharing raw data.
- AI assigns a **trust score** to each device based on behavior.
- If a device is compromised, AI flags it and alerts the network.

### 3. Blockchain Trust Layer
- Each IoT device has a **Decentralized Identity (DID)** stored on the blockchain.
- **Smart contracts** automatically revoke permissions for low-trust devices.
- Logs all AI-detected threats immutably to prevent tampering.

## Workflow
1. **IoT device collects data** (e.g., temperature, motion, power usage).
2. **AI analyzes data** in real-time and assigns a trust score.
3. **Blockchain stores trust scores** and security logs immutably.
4. **Smart contracts enforce security actions** (e.g., isolate compromised devices, trigger updates).
5. **The system self-heals** by updating AI models and quarantining threats.

## Real-Life Problems Solved
### Problem 1: Securing Smart City Infrastructure
- IoT devices in smart cities (traffic cameras, streetlights, sensors) are vulnerable to hacking.
- Our system detects malicious behavior and prevents unauthorized access using AI-driven trust scores and blockchain security.

### Problem 2: Ensuring Reliable Data in Industrial IoT (IIoT)
- Industrial sensors monitor equipment health, but faulty readings or tampered data can cause failures.
- Our system ensures **data integrity** by logging trusted device data on the blockchain, preventing false or manipulated readings.

## Example Use Case
Consider a **smart factory** using IoT sensors for temperature control:
1. A sensor starts sending abnormal temperature readings.
2. AI detects it as an anomaly and lowers its trust score.
3. Blockchain logs the anomaly and triggers an **automated alert**.
4. The system **isolates the faulty sensor** to prevent false data influence.
5. Factory operators receive real-time insights, ensuring system reliability.

