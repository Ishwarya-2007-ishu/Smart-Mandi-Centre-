 🌾 Smart Mandi Centre

Smart India Hackathon 2026

**Problem Statement ID:** SIH26032  
**Problem Statement Category:** Software  
**Team Name:** HexaFlux  
**Theme:** Smart Automation

---

📌 Problem Statement

Farmers often face long waiting times, lack of information regarding procurement schedules, and uncertainty about procurement status.

The existing manual procurement process creates challenges such as:

- Long waiting time
- No visibility of procurement schedules
- Uncertainty about quality-check and acceptance status
- Lack of payment status information
- Crowd management difficulties

---

💡 Our Solution

**Smart Mandi Centre** is a digital procurement management platform designed to make the agricultural procurement process easier, faster and more transparent for farmers and procurement-centre officers.

The system provides:

- Multilingual Farmer Mobile Application
- Voice Assistant
- Digital Token System
- Procurement Slot Booking
- Live Queue Tracking
- Waiting-Time Estimation
- Procurement Status Tracking
- Payment Status Tracking
- IVR support for basic-phone users
- AI/ML-based arrival, crowd and waiting-time prediction

---
 🎯 Key Features

👨‍🌾 Farmer Mobile App

- Farmer registration using mobile number
- OTP-based login
- Multilingual interface
- Procurement slot booking
- Crop and quantity selection
- Digital token generation
- QR token verification
- Live queue tracking
- Estimated waiting time
- Procurement status
- Payment status
- Notifications
- Voice Assistant

 📞 IVR Support

Farmers without smartphones can access the system through keypad/voice telephone services.

This helps improve accessibility for farmers with limited digital literacy.

🧑‍💼 Officer Dashboard

Officers can:

- View dashboard
- Manage farmers
- Verify farmer details
- Allocate tokens
- Adjust time slots
- Monitor live queues
- Manage procurement
- Verify crop details
- Confirm quantity and quality
- Verify payment status
- Generate reports
- Send notifications

🤖 AI/ML Intelligence

The system uses AI/ML to help predict:

- Farmer arrivals
- Centre crowd
- Waiting time

These predictions can support proactive slot allocation and queue management.

---

 ⭐ Unique Value Proposition

- One common real-time view for both farmers and officers
- AI-driven proactive slot allocation
- Multilingual and voice-enabled system
- App + Voice Assistant + IVR accessibility
- Support for both smartphone and basic-phone users

---

 🏗️ System Architecture

The system consists of:

Farmer Mobile Application

- Authentication
- Language Selection
- Book Procurement Slot
- Queue & Token Management
- Procurement Status
- Payment Status
- Voice Assistant

Office Desktop Application

- Farmer Management
- Token Management
- Queue Management
- Procurement Management
- Payment Management
- Reports
- Notifications

Application Server

- Business Logic
- APIs
- Data Processing

Database

- Farmer Data
- Token / Queue Data
- Payment Data

External Services

- OTP Service
- SMS Gateway
- Voice / Language Service
- Payment Gateway
- Notification Service

---

🛠️ Technology Stack

 Frontend

- Flutter
- Dart
- React.js

Backend

- Python
- FastAPI

AI / ML

- Scikit-learn
- Whisper
- Google Cloud

Database

- MySQL

Communication & Services

- Exotel
- SMS API
- Payment Gateway

Security & APIs

- JWT
- REST API

 Version Control

- Git
- GitHub

---

🔄 Farmer Workflow

1. Farmer Registration
2. OTP Login
3. Select Language
4. Book Procurement Slot
5. Select Crop & Quantity
6. Choose Date & Time Slot
7. Get Digital Token
8. Track Live Queue
9. Visit Mandi
10. Show Token at Entry
11. Crop Verification & Procurement
12. Quality Check
13. Confirm Quantity & Price
14. Payment Notification
15. Receive Payment Receipt

---

🧑‍💼 Officer Workflow

1. Login to System
2. View Dashboard
3. Manage Farmers
4. Verify Farmer Details
5. Manage Tokens & Slots
6. Monitor Live Queue
7. Procurement Monitoring
8. Verify Crop Details
9. Confirm Quantity & Quality
10. Payment Verification
11. Generate Reports
12. Send Notifications
13. Logout Securely

---

🔐 Security

The system focuses on:

- OTP Authentication
- Role-Based Access
- Secure Communication
- Masked Banking Data
- JWT Authentication
- Secure API Communication

---

🚀 Feasibility

Technical Feasibility:
Uses a proven technology stack including Flutter, React, FastAPI and MySQL.

Data & Access Security:
OTP authentication, encrypted communication and role-based access help protect user data.
 
Innovation:
AI-based arrival, crowd and waiting-time prediction can support slot allocation.

Operational Feasibility:
The project can be developed through phased implementation:

UI → Backend → Token/Queue → Status → Voice → AI/ML → Integration

Economic Feasibility:
The system can work with farmers' existing phones and a basic helpline without requiring new hardware.

---

🌱 Benefits

- Reduces farmer waiting time
- Reduces crowd at procurement centres
- Provides advance schedule and slot visibility
- Provides live queue information
- Provides digital token and QR verification
- Provides procurement and payment status
- Supports multiple languages
- Supports voice-based interaction
- Supports basic-phone users through IVR
- Helps officers manage farmers and queues efficiently
- Reduces unnecessary travel and waiting

---

📊 Existing Process vs Smart Mandi Centre

| Feature | Existing / Manual Process | Smart Mandi Centre |
|---|---|---|
| Advance Schedule & Slot Visibility | ❌ | ✅ |
| Live Queue & Waiting-Time Estimate | ❌ | ✅ |
| Digital Token + QR Verification | ❌ | ✅ |
| Unified Procurement / Payment Status | ❌ | ✅ |
| Multilingual Voice Assistant | ❌ | ✅ |
| IVR Access for Basic Phones | ❌ | ✅ |
| AI-based Arrival / Crowd Prediction | ❌ | ✅ |

---

⚠️ Challenges & Mitigation

Technical Challenges

**Risk:** Rural connectivity gaps and voice-recognition accuracy across regional languages and accents.

**Mitigation:**
- IVR fallback for low-connectivity users
- Iterative Speech-to-Text tuning
- Confirmation prompts

 User / Business Challenges

**Risk:** Farmers may distrust a new digital process or may have difficulty using smartphone applications.

**Mitigation:**
- Voice-first design
- Officer-assisted onboarding
- IVR access for non-smartphone users

---

🔮 Future Enhancements

- Expand support for additional regional languages
- Improve AI/ML prediction accuracy
- Add more procurement centres
- Add more crop categories
- Improve voice-based interaction
- Enhance analytics and reporting
- Integrate additional external services

---

👥 Team Members

| S.No | Name | Branch | Year |
|---|---|---|---|
| 1 | Harithra K | B.E. CSE | III Year |
| 2 | Ishwarya P | B.E. CSE | III Year |
| 3 | Lokeshwar K | B.E. CSE | III Year |
| 4 | Kishore Kumar G | B.E. CSE | III Year |
| 5 | Priyanka T | B.E. CSE | III Year |
| 6 | Priyadharshi S | B.E. CSE | III Year |

---

 📁 Project Structure


Smart-Mandi-Centre/
│
├── frontend/
│   ├── farmer-app/
│   └── officer-dashboard/
│
├── backend/
│   ├── api/
│   ├── services/
│   └── models/
│
├── ai-ml/
│   ├── prediction/
│   └── models/
│
├── database/
│
├── documentation/
│
├── screenshots/
│
├── README.md
│
└── .gitignore
