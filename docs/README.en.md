# 💧 KelolaSenseAqua

**KelolaSenseAqua** is a modular IoT system designed for monitoring and controlling water quality across various sectors such as aquaculture, hydroponics, agriculture, and pollution control. The system promotes a modular, cost-efficient, and flexible architecture with a plug-n-play approach that allows end-users to expand and maintain it independently.

---

## 🚀 Vision

> Build an open, cost-effective, and user-friendly IoT system that enables hobbyists and small/medium businesses to manage aquatic ecosystems intelligently.

---

## ⚙️ Core Features

- Modular sensors (wired and wireless with EEPROM ID tagging)
- Distributed power control system with self-protection (PCU)
- Control of lighting, fan, feeding, and other actuators in parallel
- ESP32 integration for cloud/mobile access
- NRF-based wireless sensor communication for long-distance data
- Cloud-ready backend (REST/GraphQL, MQTT, DB)
- Mobile App (Flutter) & Admin Panel (Next.js)

---

## 📦 MVP Roadmap

📁 See [`docs/mvp`](./docs/mvp) for technical details:

| MVP | Title                    | Status     |
| --- | ------------------------ | ---------- |
| 1   | Power Control Unit (PCU) | 🛠️ Drafted |
| 2   | Basic Sensor Monitoring  | 🛠️ Drafted |
| 3   | Display Monitor Phase 1  | 🛠️ Drafted |

Next MVPs will include:

- Remote Sync via MQTT
- Modular Lighting System
- Wireless Sensor Deployment
- Admin Dashboard & Analytics

---

## 🧰 Tech Stack & Tools

| Area               | Tools                                  |
| ------------------ | -------------------------------------- |
| Firmware           | PlatformIO, LVGL                       |
| MCU                | CH32, ATtiny, ESP32                    |
| Cloud              | AWS, Docker, MQTT Broker, REST/GraphQL |
| Frontend           | Flutter (mobile), Next.js (admin)      |
| CI/CD              | GitHub Actions                         |
| Diagram & Design   | Figma, Diagram.io, KiCad               |
| Project Management | Notion, ClickUp, GitHub Project        |

---

## 📁 Project Structure

```
kelolasenseaqua/
├── docs/
│   ├── mvp/              # MVP documentation per stage
│   ├── architecture/     # System and sequence diagrams
│   └── r&d/              # Component research notes
├── firmware/             # MCU firmware source
├── web/                  # Admin panel (Next.js)
├── mobile/               # End-user app (Flutter)
├── .prettierrc           # Code formatting config
├── .gitignore
└── README.md
```

---

## 🙏 Contribution & License

This project is under active development and exploration. Any insight, feedback, or contribution is welcome.

The license will be defined after the MVP is finalized and public roadmap is available.

---

> "We don't chase complexity. We build modularity that prioritizes control, efficiency, and user autonomy."

\-- KelolaSenseAqua
