⛽ Fuel Verify Pro – Smart Fuel Fraud Detection System

https://blue-hazel-70.tiiny.site


Developed by: Shobhit Shukla
Program: B.Tech CSE (Artificial Intelligence & Machine Learning)

🚀 Project Overview

Fuel Verify Pro is a smart IoT-based fuel verification and fraud detection system designed to prevent fuel meter manipulation at petrol pumps.

The system compares pump meter readings with real-time sensor data to detect discrepancies during refueling sessions. If the difference crosses a predefined threshold, the system flags it as potential fraud.

This project demonstrates how AI, IoT concepts, and real-time visualization can improve transparency and trust in fuel dispensing systems.

🎯 Problem Statement

Fuel fraud and meter tampering are common issues in fuel stations where customers may receive less fuel than shown on the meter.

Challenges:

Lack of real-time verification

Manual monitoring is unreliable

No digital audit trail

Customers cannot validate fuel quantity instantly

Solution:

Fuel Verify Pro introduces a dual-verification mechanism:

Pump Meter Reading (Operator Input)

IoT Sensor Reading (Actual Fuel Flow)

The system compares both values and automatically detects suspicious differences.

✨ Key Features

✅ Real-time Fuel Flow Visualization
✅ IoT Sensor Simulation (ESP32 Data Stream)
✅ Fraud Detection Logic with Threshold Analysis
✅ Digital Receipt Generation
✅ Session History & Audit Log
✅ Smart UI Dashboard with Live Charts
✅ Pump & Fuel Type Selection
✅ Digital Verification Status (Verified / Fraud)

🧠 How It Works

Operator enters pump meter reading.

IoT flow sensor measures actual dispensed fuel.

System compares:

Difference = | Meter Reading – Sensor Reading |

If difference > ±0.15 Litres:

🚨 Fraud Alert Triggered

Otherwise:

✅ Refueling Verified

🖥️ System Interface Modules
🔵 Live Flow Monitoring

Displays:

Flow Rate (L/min)

Real-time waveform visualization

Total sensor fuel measurement

🟢 Verification Engine

Compares:

Meter input

Sensor data

Fraud threshold

🟠 Control Panel

Allows:

Pump selection

Fuel type selection

Vehicle number input

Session start/stop

🔴 Digital Receipt System

Generates secure session receipts with:

Session ID

Fuel details

Verification status

🛠️ Technology Stack

Frontend: HTML5, CSS3, JavaScript

UI Design: Custom futuristic dashboard

Visualization: Canvas API

Simulation: JavaScript-based IoT flow model

Concept Hardware: ESP32 + Flow Sensor (Simulated)

📊 Fraud Detection Logic
if (difference > 0.15 Litres)
   status = FRAUD DETECTED
else
   status = VERIFIED

Sensor readings simulate realistic variations and noise to mimic real-world IoT environments.

📁 Project Structure
FuelVerifyPro/
│
├── index.html        # Main dashboard UI
├── README.md         # Project documentation
▶️ How to Run

Download or clone the project

Open index.html in any modern browser

Enter:

Vehicle number

Meter reading

Click Start Session

Click Stop & Verify to analyze results

No server setup required.

🧪 Demo Mode

Enable Simulate Meter Tampering option to test fraud detection scenarios.

📸 Use Cases

Smart Petrol Pumps

Government Fuel Monitoring

AI/IoT Hackathons

Academic Demonstrations

Consumer Protection Systems

🔮 Future Improvements

Real ESP32 Integration

Cloud Database Storage

Blockchain Audit Logs

AI-based anomaly prediction

Mobile App Companion

QR-based public verification system

👨‍💻 Author

Shobhit Shukla
B.Tech CSE (AIML)

Focused on:

Artificial Intelligence

Cyber Security

IoT Systems

Smart Automation Solutions

📜 License

This project is developed for educational and research purposes.
