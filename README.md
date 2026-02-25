# ⛽ Fuel Verify Pro – Smart Fuel Fraud Detection System
Note : it's a prototype not a complete project .
Live Demo: https://blue-hazel-70.tiiny.site

Developed By: Shobhit Shukla
Program: B.Tech CSE (Artificial Intelligence & Machine Learning)

---

## 🚀 Project Overview

Fuel Verify Pro is a smart IoT-based fuel verification and fraud detection system designed to prevent fuel meter manipulation at petrol pumps. The system compares pump meter readings with real-time sensor data to detect discrepancies during refueling sessions. If the difference crosses a predefined threshold, the system flags it as potential fraud.

This project demonstrates how AI concepts, IoT integration, and real-time visualization can improve transparency and trust in fuel dispensing systems.

---

## 🎯 Problem Statement

Fuel fraud and meter tampering are common issues at fuel stations where customers may receive less fuel than displayed on the meter.

### Challenges

* Lack of real-time verification
* Manual monitoring is unreliable
* No digital audit trail
* Customers cannot validate fuel quantity instantly

### Solution

Fuel Verify Pro introduces a Dual-Verification Mechanism:

1. Pump Meter Reading (Operator Input)
2. IoT Sensor Reading (Actual Fuel Flow)

The system compares both values and automatically detects suspicious differences.

---

## ✨ Key Features

* Real-time Fuel Flow Visualization
* IoT Sensor Simulation (ESP32 Data Stream)
* Fraud Detection Logic with Threshold Analysis
* Digital Receipt Generation
* Session History & Audit Log
* Smart UI Dashboard with Live Charts
* Pump & Fuel Type Selection
* Digital Verification Status (Verified / Fraud)

---

## 🧠 How It Works

1. Operator enters pump meter reading.
2. IoT flow sensor measures actual dispensed fuel.
3. System calculates:

Difference = | Meter Reading – Sensor Reading |

If difference > ±0.15 Litres → Fraud Alert Triggered
Otherwise → Refueling Verified

---

## 🖥️ System Interface Modules

### Live Flow Monitoring

* Flow Rate (L/min)
* Real-time waveform visualization
* Total sensor fuel measurement

### Verification Engine

* Meter input comparison
* Sensor data analysis
* Fraud threshold validation

### Control Panel

* Pump selection
* Fuel type selection
* Vehicle number input
* Session start / stop

### Digital Receipt System

* Session ID
* Fuel details
* Verification status

---

## 🛠️ Technology Stack

Frontend: HTML5, CSS3, JavaScript
UI Design: Custom Futuristic Dashboard
Visualization: Canvas API
Simulation: JavaScript-based IoT Flow Model
Concept Hardware: ESP32 + Flow Sensor (Simulated)

---

## 📊 Fraud Detection Logic

if (difference > 0.15 Litres)
status = FRAUD DETECTED
else
status = VERIFIED

Sensor readings simulate realistic variations and noise to mimic real-world IoT environments.

---

## 📁 Project Structure

FuelVerifyPro/
│
├── index.html  # Main dashboard UI
├── README.md   # Project documentation

---

## ▶️ How to Run

1. Download or clone the project
2. Open index.html in any modern browser
3. Enter vehicle number and meter reading
4. Click Start Session
5. Click Stop & Verify to analyze results

No server setup required.

---

## 🧪 Demo Mode

Enable “Simulate Meter Tampering” to test fraud detection scenarios.

---

## 📸 Use Cases

* Smart Petrol Pumps
* Government Fuel Monitoring Systems
* AI / IoT Hackathons
* Academic Demonstrations
* Consumer Protection Platforms

---

## 🔮 Future Improvements

* Real ESP32 Hardware Integration
* Cloud Database Storage
* Blockchain-based Audit Logs
* AI-powered Anomaly Prediction
* Mobile App Companion
* QR-based Public Verification System

---

## 👨‍💻 Author

Shobhit Shukla
B.Tech CSE (AIML)

Focus Areas:
Artificial Intelligence | Cyber Security | IoT Systems | Smart Automation Solutions

---

## 📜 License

This project is developed for educational and research purposes.
