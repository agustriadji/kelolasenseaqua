# 🌊 KelolaSenseAqua

**KelolaSenseAqua** is a modular IoT system designed to monitor and control water quality in various sectors such as aquaculture, hydroponics, agriculture, and pollution control. The system utilizes a plug-and-play sensor approach with wired and wireless communication and focuses on cost efficiency, flexibility of use, and ease of integration.

---

## 💡 Problem

- Current environmental monitoring devices are expensive and not modular.
- Damage to one part requires replacement of the entire unit.
- Different needs per user (farmers, hobbyists, breeders).
- Lack of remote access and data integration features for decision making.

---

## 🧩 Solution

- **Sensor Modular Plug-and-Play**: Each sensor has EEPROM metadata (ID, type, location), can be installed wired or wireless (NRF).
- **Unit Pengontrol Terpisah**: ESP32 for remote access (optional), local MCU for protection & power distribution functions.
- **Web Dashboard + Mobile App**: For configuration, data monitoring, and notifications.
- **Data Streaming & Automasi**: Based on MQTT, WebSocket, and cloud integration.

---

## 📦 Modular System Structure

1. **Power Control Unit**

   - AC current distribution
   - Load protection
   - MCU CH32 for safety & isolation function

2. **Lighting Module**

   - Plugable LED emitters
   - Extendable Panel
   - Panel group + relay/dimmer + fan & ventilation

3. **Feeding Machine**

   - Motor (relay/stepper) for automatic feeding

4. **Fan Module**

   - Parallel socket for external fan (12V)

5. **Smart Control Socket**

   - Accommodates ESP32, remote access

6. **Sensor Module (wired/wireless)**

   - Socket for multiple sensors
   - Event-based or polling

7. **Sensor Wireless Modular**

   - NRF + EEPROM ID/type
   - For hard-to-reach areas such as cages

---

## 🛠️ Tools & Tech

| Domain        | Tools                   |
| ------------- | ----------------------- |
| Plan & Docs   | ClickUp, Notion         |
| Hardware      | KiCad, PlatformIO       |
| Web & Mobile  | Next.js, Flutter        |
| Backend       | Go / Python / Nest.js   |
| Cloud & Infra | AWS, Docker, Kubernetes |
| CI/CD         | GitHub Actions          |

---

## 🚀 First MVP

### Use-case: Aquarium/Aquascape Monitoring

- pH + Temperature Sensor
- Local MCU for data acquisition
- Send data via serial/MQTT to ESP32
- ESP32 → local dashboard (Next.js) or push notification

---

## 👥 Initial Target User

- Ornamental fish / aquascape hobbyist
- Cage fish farmers
- Small-scale hydroponic farmers
- Agro/hydro monitoring community

---

## 🛣️ Initial Roadmap

- [ ] System diagram and module documentation
- [ ] ClickUp task: MVP pH + temperature sensor
- [ ] Hardware prototype: sensor + EEPROM + ESP32
- [ ] Local Dashboard (Next.js)
- [ ] Early stage mobile UI/UX (Flutter)
- [ ] MQTT Integration & push notifications

---

## 📂 Repository

```
KelolaSenseAqua/
├── docs/                  ← Main documentions
├── hardware/              ← KiCad & BoM
├── firmware/              ← PlatformIO firmware sensor
├── services/              ← Backend API & data processor
├── frontend-admin/        ← Web admin (Next.js)
├── mobile-app/            ← Flutter app
├── diagrams/              ← .drawio, schema
├── ci/                    ← GitHub Actions
├── docker/                ← Dockerfile & K8s configs
└── README.md              ← This document
```

---

## ✨ Filosofi

This product is not just for aquarium monitoring. **KelolaSenseAqua** is the foundation of a modular monitoring system that can be used for various needs in the water, agriculture, and environmental sectors. With its cost efficiency, ease of maintenance, and scalability, this product comes as a real solution to everyday problems that are often overlooked.
