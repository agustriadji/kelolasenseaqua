# 🌊 Project Overview – KelolaSenseAqua

**KelolaSenseAqua** is a modular and scalable IoT platform designed to monitor and control water quality for multiple sectors including aquaculture, hydroponics, agriculture, and pollution monitoring.

The system emphasizes:

- Plug-and-play modular sensors (wired and wireless)
- Efficient power distribution and protection
- Remote monitoring & control via mobile/web
- Cost-efficiency and DIY-friendly deployment

---

## 💡 Background & Problem

Conventional water monitoring systems tend to be:

- Expensive and rigid (non-modular)
- Difficult to repair (single point of failure)
- Non-flexible for varied use-cases
- Lacking real-time analytics and remote control

These limitations make it difficult for hobbyists, small farmers, and communities to adopt intelligent water management tools.

---

## 🧩 Modular System Design

The system consists of the following modular components:

1. **Power Control Unit (PCU)**

   - AC input, relay isolation, and protection circuit
   - Microcontroller for safety logic and socket-level monitoring

2. **Sensor Module**

   - Supports both wired and wireless sensors
   - Communicates via Serial/NRF, and relays data to ESP32

3. **Smart Control Socket**

   - ESP32 board for remote access and MQTT integration

4. **Lighting Module**

   - Plugable LED emitter groups
   - Panel relay control, active ventilation

5. **Feeding Module**

   - Stepper/motor-based feeding with scheduled triggers

6. **Fan Control Module**

   - Parallel fan socket with power limit

7. **Wireless Modular Sensors**
   - NRF communication
   - EEPROM for ID, type, and location metadata

---

## 🎯 Target MVP Use Cases

The system is designed to scale. However, the MVP (Minimum Viable Product) targets small-to-medium use cases such as:

- Aquarium & aquascape automation
- Small hydroponic setups
- Environmental monitoring in remote areas
- Early warning systems for fish cages (wireless sensor nodes)

---

## 🔧 Technology Stack

| Domain          | Tools & Platforms                  |
| --------------- | ---------------------------------- |
| Planning & Docs | ClickUp, Notion                    |
| Hardware        | KiCad, PlatformIO                  |
| Firmware        | CH32 / ATtiny / ESP32              |
| Frontend        | Flutter (Mobile), Next.js (Web)    |
| Backend         | Go / Python / Nest.js              |
| Communication   | MQTT, WebSocket, Serial            |
| Cloud           | AWS, Cloud DB, Analytics           |
| DevOps          | GitHub Actions, Docker, Kubernetes |

---

## 🚀 Core Features

- Modular sensor architecture with EEPROM metadata
- Fault-isolated power distribution unit
- MQTT and REST API communication
- Real-time dashboard and mobile app integration
- OTA-ready design (ESP32)
- Scalable from aquarium hobbyists to agro-farmers

---

## 📌 Roadmap (Early Stage)

- [x] System architecture & diagram design
- [ ] MVP 1: Power Control Unit (with protection logic)
- [ ] MVP 2: Local Sensor Monitoring (basic)
- [ ] MVP 3: Display Interface
- [ ] Web dashboard prototype (Next.js)
- [ ] Mobile app prototype (Flutter)
- [ ] MQTT integration with ESP32
- [ ] Hardware testing on aquarium setup

---

## 📂 Project Structure (Work-in-Progress)

```bash
KelolaSenseAqua/
├── docs/
│   ├── overview.md
│   ├── mvp/
│   ├── r&d/
│   └── architecture/
├── hardware/
├── firmware/
├── services/
├── frontend-admin/
├── mobile-app/
├── diagrams/
├── docker/
├── ci/
└── README.md
```

---

## ✨ Vision

KelolaSenseAqua is more than a hobbyist project. It is a flexible foundation for building scalable environmental sensing and control systems for real-world problems. Its modular design supports various deployment environments and encourages DIY innovation while reducing maintenance complexity and cost.

---
