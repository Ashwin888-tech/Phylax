# PHYLAX – Smart Access Control System

## Overview

PHYLAX is an embedded biometric access control system designed to provide secure authentication using fingerprint recognition. The system supports multiple users, master fingerprint management, fingerprint enrollment, deletion, and relay-controlled electronic locking through an intuitive OLED-based user interface.

The project demonstrates the integration of embedded systems, biometric authentication, and secure access control for residential, laboratory, and office applications.

---

## Features

* Fingerprint-based authentication
* Master fingerprint verification
* Multi-user enrollment
* Master user enrollment
* Secure fingerprint deletion
* Protection against accidental deletion of the final master fingerprint
* OLED graphical user interface
* Relay-controlled electronic lock
* Push-button menu navigation
* Fingerprint ID management
* Embedded access control firmware

---

## Hardware Used

* ESP32 Development Board
* Optical Fingerprint Sensor
* SSD1306 OLED Display
* Relay Module
* Push Buttons
* Electronic Door Lock
* Power Supply

---

## Software Used

* Arduino IDE
* Embedded C++
* Adafruit Fingerprint Library
* Adafruit SSD1306 Library
* Wire Library

---

## Working Principle

1. The system waits for fingerprint authentication.
2. Registered users are verified using the fingerprint sensor.
3. Upon successful authentication, the relay unlocks the electronic lock.
4. Master users can enter enrollment mode.
5. New fingerprints can be enrolled.
6. Existing fingerprints can be deleted securely.
7. The system prevents accidental removal of the final master fingerprint.

---

## Functionalities

* User Verification
* Master Verification
* User Enrollment
* Master Enrollment
* Fingerprint Deletion
* OLED Status Display
* Relay Door Control
* Secure User Management

---

## Repository Structure

```
Phylax-Smart-Access-Control
│
├── Phylax_Smart_Access_Control.ino
├── README.md
└── LICENSE
```

---

## Applications

* Smart Door Lock
* Laboratory Access
* Office Security
* Attendance Systems
* Embedded Security Systems
* Smart Home Automation

---

## Future Improvements

* Wi-Fi Integration
* Mobile Application
* RFID + Fingerprint Authentication
* Face Recognition Integration
* Remote User Management
* Cloud Logging
* Audit Trail Storage

---

## Author

Ashwin Bhat

Electronics and Communication Engineering Student

---

## License

MIT License
