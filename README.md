
# Smart Waste Management and Awareness System 🚮📡

## 📖 Overview

In India, one of the pressing challenges in urban infrastructure is the **overflowing of dustbins** due to inefficient waste monitoring and management. Dustbins often remain full for days without being emptied, primarily because there is no timely notification system in place.

To address this, we developed a comprehensive solution: **Smart Waste Management and Awareness System**, which consists of two major components:

---

## 🔧 1. IoT-Based Smart Dustbin

Our smart dustbin uses various sensors and wireless technologies to automate and optimize waste collection.

### 🚪 Lid Automation
- Uses ultrasonic or IR sensors to detect hand gestures.
- Automatically opens the lid when a user approaches.

### 📊 Waste Level Monitoring
- An **ultrasonic sensor** monitors the fill level.
- When the bin is 100% full:
  - The lid remains closed to avoid spillage.
  - A **notification** is sent to the admin for prompt emptying.

### 🌡️ Environmental Monitoring
- A **DHT sensor** records temperature and humidity inside the bin.
- A **heat sensor** detects abnormal temperature rise due to decomposition or delay in cleaning.
- Sends alerts if environmental thresholds are exceeded, ensuring hygiene and safety.

### 📶 Wireless Communication
- Integrated **ESP8266 Wi-Fi module** transmits data every 30 minutes.
- Enables real-time monitoring and cloud-based logging.
- Ensures authorities receive consistent updates with no manual input.

---

## 🌍 2. Awareness Website

We observed a lack of awareness among students and faculty regarding proper waste disposal and the purpose of smart dustbins. To bridge this gap, we developed an **interactive Awareness Website**.

### 🌐 Key Features

- **Multilingual Support:** Accessible to a wide audience with support for multiple Indian languages.
- **AI Chatbot:** Offers real-time answers to common questions about the system and waste management best practices.
- **Live Monitoring Dashboard:** Displays real-time data from deployed bins — fill level, temperature, alerts, and more.
- **Live Customer Support:** Real-time human assistance for technical issues, feedback, or general queries.

---

## 💡 Technologies Used

| Area            | Tools / Hardware                         |
|------------------|------------------------------------------|
| Microcontroller | Arduino / ESP8266 / NodeMCU              |
| Sensors         | Ultrasonic, DHT11/22, IR Sensor, LM35     |
| Software        | Arduino IDE, HTML/CSS/JS, Firebase / MySQL |
| Cloud           | Firebase, ThingSpeak (optional)           |
| Website         | Bootstrap, JavaScript, Google Translate API |
| AI Chatbot      | Dialogflow / Custom JS-based Bot         |

---

## 🚀 How to Run

### 📥 Clone the Repository
```bash
git clone https://github.com/AniketGangurde02/Smart-Waste-Management-and-Awareness-System
cd smart-waste-management
