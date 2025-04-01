# Door Access Control System

## 📌 Project Overview

This project is a complete **Door and Presence Control System** developed for the course _Project and Laboratory on Embedded Communication Systems_ at **Politecnico di Torino**.

It combines a **Flutter-based frontend**, a **Flask backend**, and **Raspberry Pi + RFID hardware integration** to deliver a scalable and secure access management platform. Users are organized by roles and companies, with role-based permissions, RFID badge access, and full statistics and logging.

---

## 🔧 Technologies Used

- **Frontend**: Flutter (Dart)
- **Backend**: Flask (Python), MySQL, JWT, SMTP
- **Hardware**: Raspberry Pi, MFRC522 RFID reader, GPIO
- **Other Tools**: CORS, Regex validation, Chromium kiosk mode

---

## 👥 User Roles and Permissions

The system implements Role-Based Access Control (RBAC), supporting the following roles:

- **System Administrator (SA)**: full access to all system features
- **Customer Administrator (CA)**: manages company, rooms, and users
- **Customer Operator (CO)**: manages basic user permissions and room access
- **User (USR)**: limited to personal profile, statistics, and room check-in/out

---

## 📱 Key Features

- 🔐 JWT-based authentication with password hashing
- 🧾 User registration with regex validation and RFID token assignment
- 📊 Real-time access statistics, room logs, and activity tracking
- 📩 Password recovery via email using SMTP
- 🧪 Emulate users to test role-based permissions (admin-only)
- 🏢 Company and room management (add, modify, delete)
- 📡 Raspberry Pi integration for door access and LED/relay control
- 🌐 Multi-platform frontend (Android, iOS, Web, Desktop) via Flutter

---

## 🧪 Hardware Integration

The system includes a Python client running on Raspberry Pi to:

- Read/write RFID tags (MFRC522)
- Control LEDs and door mechanisms
- Interact with the backend to validate room access
- Run a browser in kiosk mode for touch display operation

---

## 📂 Project Structure

