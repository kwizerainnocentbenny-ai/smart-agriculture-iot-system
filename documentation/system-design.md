# 🌱 Smart Agriculture System Design

## 📌 Overview

This system is designed to monitor environmental conditions and automate irrigation in agricultural environments using IoT technologies.

---

## 🧠 System Architecture

Sensors → ESP32 → Backend API → Database → Web Dashboard

---

## ⚙️ Components

### 1. Sensors

* Soil moisture sensor
* Temperature and humidity sensor

### 2. ESP32 (Edge Device)

* Reads sensor data
* Applies automation logic
* Sends data to backend

### 3. Backend (FastAPI)

* Receives and processes data
* Provides API for dashboard
* Handles control commands

### 4. Database

* Stores sensor readings
* Logs irrigation activity

### 5. Dashboard

* Displays real-time data
* Allows manual control of irrigation

---

## 🔄 Data Flow

1. Sensors collect environmental data
2. ESP32 processes and evaluates conditions
3. Data is sent to backend via HTTP/MQTT
4. Backend stores data in database
5. Dashboard displays data to user

---

## 🤖 Automation Logic

* If soil moisture < threshold → Irrigation ON
* If soil moisture ≥ threshold → Irrigation OFF

---

## 📈 Scalability

* System can support multiple sensor nodes
* Backend can aggregate data from multiple farms
* Can be extended with AI-based decision systems
