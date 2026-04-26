# 🌱 Smart Agriculture & Livestock IoT System

An IoT-based system for monitoring environmental conditions and automating irrigation and livestock support using ESP32, FastAPI, and a real-time dashboard.

---

## 🚀 Features

* Soil moisture monitoring
* Temperature and humidity tracking
* Automated irrigation control based on sensor data
* Manual override via dashboard
* Real-time data visualization

---

## 🧠 System Architecture

Sensors → ESP32 → Backend (FastAPI) → Database → Dashboard

---

## ⚙️ Automation Logic

* If soil moisture is below threshold → irrigation ON
* If soil moisture is sufficient → irrigation OFF

---

## 🛠️ Technologies Used

* ESP32
* FastAPI
* HTML, JavaScript
* MySQL / MariaDB
* HTTP / MQTT

---

## ▶️ How to Run

```id="run2"
cd backend
pip install -r requirements.txt
uvicorn app:app --reload
```

Open dashboard/irrigation_dashboard.html in browser.

---

## 📸 Screenshots

(Available in media folder)

---

## 🔧 Future Improvements

* Livestock tracking integration
* Mobile alerts
* AI-based irrigation optimization

---

## 👨‍💻 Author

KWIZERA Innocent
