# 🌞 **_Advance Solar Electric Tricycle_**
### **_Real-Time IoT Monitoring Dashboard (ESP32 + ThingSpeak)_**

This project is a **_complete IoT monitoring dashboard_** designed for an **_Advance Solar Electric Tricycle_**.  
It displays **_real-time sensor data_** collected from an ESP32 and provides live charts and map tracking for:

- 🌡️ **_Temperature_**
- 💧 **_Humidity_**
- ❤️ **_Heart Rate (BPM)_**
- 🫁 **_SpO₂_**
- 📏 **_Ultrasonic Distance_**
- 📍 **_GPS Location (Latitude & Longitude)_**

All values are fetched from the **_ThingSpeak API_** and visualized using **_Chart.js_** and **_Leaflet Maps_**.

---

## 🚀 **_Live Demo_**
👉 https://shagunattri06.github.io/Advance-Solar-Electric-Tricycle-/
---

## 📌 **_Features_**

### ✅ **_Real-Time Sensor Monitoring_**
- Auto-refresh every **_30 seconds_**
- Manual refresh for instant updates

### 📊 **_Interactive Graphs_**
- Built using **_Chart.js_**
- Smooth animated line charts
- Stores last **_10 readings_** for each sensor

### 🗺️ **_Live Map Tracking_**
- Built using **_Leaflet.js_**
- Auto-update marker based on GPS values  
- Default location set to **_Chitkara University, Rajpura, Punjab_**

### 💎 **_Modern & Responsive UI_**
- Clean white card layout  
- Mobile-friendly design  
- Lightweight and fast

---

## 🛠️ **_Tech Stack_**

| Component | Technology |
|----------|------------|
| **_Frontend_** | HTML, CSS, JavaScript |
| **_Charts_** | Chart.js |
| **_Maps_** | Leaflet.js + OpenStreetMap |
| **_IoT Platform_** | ThingSpeak |
| **_Microcontroller_** | ESP32 |

---

## 🔌 **_ThingSpeak Configuration_**

- **_Channel ID:_** **3161036**  
- **_API Key (Read):_** **W9BRV0UO44PT32YJ**

### **_Field Structure_**
| Field | Sensor |
|-------|--------|
| **_field1_** | Temperature |
| **_field2_** | Humidity |
| **_field3_** | Heart Rate |
| **_field4_** | SpO₂ |
| **_field5_** | Distance |
| **_field6_** | Latitude |
| **_field7_** | Longitude |

---

## 🛰️ **_Future Enhancements_**
- Battery voltage monitoring  
- Motor speed/torque visualization  
- ESP32 sleep mode optimization  
- SMS alerts / mobile app  
- Cloud storage (Firebase / MongoDB)

---

## 👤 **_Author_**
**_Shagun Attri_**  
_2nd Year CSE — IoT & Frontend Development_

---

## 📄 **_License_**
This project is **_open-source_** and free to use.
