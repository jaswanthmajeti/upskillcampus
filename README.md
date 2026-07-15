# HVAC and Remote Energy Monitoring System using Node-RED & MQTT

An Industrial IoT simulation project that demonstrates the design and implementation of a real-time HVAC and Remote Energy Monitoring System using **Node-RED** and **MQTT**. This project simulates HVAC monitoring without physical hardware by generating virtual sensor data, enabling real-time visualization and analysis through an interactive dashboard.


---

## 📌 Project Overview

This project aims to simulate an Industrial IoT-based HVAC monitoring solution by replacing physical sensors and DAMS hardware with Node-RED. The system generates simulated environmental and electrical parameters, transmits them using MQTT, and visualizes them on a monitoring dashboard for analysis and decision-making.

---

## 🎯 Objectives

- Simulate HVAC monitoring without physical hardware.
- Generate virtual sensor data using Node-RED.
- Implement MQTT-based publish-subscribe communication.
- Develop a real-time monitoring dashboard.
- Analyze monitored data for operational insights.

---

## 📊 Parameters Monitored

- 🌡️ Temperature
- 💧 Humidity
- ⚡ Voltage
- 🔌 Current
- ⚙️ Energy Consumption
- 👥 Occupancy Count

---

## 🏗️ System Architecture

The system follows a typical Industrial IoT monitoring workflow:

```
Simulated HVAC Parameters
          │
          ▼
      Node-RED
          │
          ▼
    MQTT Publisher
          │
          ▼
     MQTT Broker
          │
          ▼
   MQTT Subscriber
          │
          ▼
 Node-RED Dashboard
          │
          ▼
     Data Analytics
```

---

## 🛠️ Tech Stack

- Node-RED
- MQTT
- Node-RED Dashboard
- Git
- GitHub