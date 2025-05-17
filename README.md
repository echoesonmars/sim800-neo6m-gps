# SIM800L + NEO-6M GPS Tracker with Web Server

A microcontroller-based GPS tracking project using the SIM800L GSM module and the NEO-6M GPS module. The device collects real-time GPS coordinates and sends them over GSM to a remote web server, where the location can be visualized or logged.

## 📦 Features

- Real-time location tracking via NEO-6M GPS
- Data transmission over GSM using SIM800L
- Remote web server for receiving and displaying data
- Arduino-based implementation
- Easily extendable for SMS alerts, Google Maps integration, or database logging

## 🔌 Hardware Requirements

- SIM800L GSM module  
- NEO-6M GPS module  
- Arduino (Uno, Nano, or similar)  
- Power supply (stable 3.7V–4.2V for SIM800L)  
- SIM card with data plan  

## 🧠 Folder Structure

├── sim800l-gps-webserver/ → Arduino code for sending GPS data via GSM
├── test-gps/ → Code for testing GPS module standalone
├── test-sim800l/ → Code for testing GSM module standalone
├── web-server/ → Web server files (e.g., PHP or Node.js + HTML)
└── README.md → This file