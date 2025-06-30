# 💧 KelolaSenseAqua

**KelolaSenseAqua** adalah sistem modular IoT yang dirancang untuk monitoring dan kontrol kualitas air pada berbagai sektor seperti akuakultur, hidroponik, pertanian, hingga pengendalian polusi. Sistem ini mengusung arsitektur modular, efisien, dan fleksibel dengan pendekatan plug-n-play yang memungkinkan ekspansi dan perawatan mandiri oleh pengguna akhir.

---

## 🚀 Visi

> Membangun sistem IoT terbuka, hemat biaya, dan mudah digunakan yang dapat dimanfaatkan oleh hobiis maupun pelaku industri kecil/menengah untuk mengelola ekosistem air secara cerdas.

---

## ⚙️ Fitur Utama

- Sensor modular (wired dan wireless, EEPROM + ID tagging)
- Sistem distribusi daya modular dengan proteksi mandiri (PCU)
- Kontrol lighting, fan, feeding, dan aktuator lain secara paralel
- Integrasi ESP32 sebagai penghubung ke cloud / mobile apps
- Penggunaan NRF untuk sensor wireless jarak jauh
- Backend cloud-ready (REST/GraphQL, MQTT, DB)
- Mobile App (Flutter) & Web Admin (Next.js)

---

## 📦 MVP Roadmap

📁 Lihat folder [`docs/mvp`](./docs/mvp) untuk detail teknis:

| MVP | Judul                    | Status     |
| --- | ------------------------ | ---------- |
| 1   | Power Control Unit (PCU) | 🛠️ Drafted |
| 2   | Sensor Monitoring Dasar  | 🛠️ Drafted |
| 3   | Display Monitor Tahap 1  | 🛠️ Drafted |

MVP selanjutnya akan mencakup:

- Remote Sync via MQTT
- Modular Lighting System
- Sensor Wireless Deployment
- Admin Dashboard & Analytics

---

## 🧰 Teknologi & Tools

| Area             | Tools                                  |
| ---------------- | -------------------------------------- |
| Firmware         | PlatformIO, LVGL                       |
| MCU              | CH32, ATtiny, ESP32                    |
| Cloud            | AWS, Docker, MQTT Broker, REST/GraphQL |
| Frontend         | Flutter (mobile), Next.js (admin)      |
| CI/CD            | GitHub Actions                         |
| Diagram & Design | Figma, Diagram.io, KiCad               |
| Manajemen        | Notion, ClickUp, GitHub Project        |

---

## 📁 Struktur Direktori

```
kelolasenseaqua/
├── docs/
│   ├── mvp/              # Dokumen MVP per tahap
│   ├── architecture/     # Diagram sistem & sequence
│   └── r&d/              # Catatan riset komponen
├── firmware/             # Kode firmware MCU
├── web/                  # Admin panel (Next.js)
├── mobile/               # Aplikasi pengguna (Flutter)
├── .prettierrc           # Format code
├── .gitignore
└── README.md
```

---

## 🙏 Kontribusi & Lisensi

Project ini masih dalam tahap pengembangan dan eksplorasi. Setiap insight, kritik, atau kontribusi sangat dihargai.

Lisensi akan ditentukan setelah MVP terbentuk dan roadmap terbuka disusun.

---

> "Kami tidak mengejar kompleksitas, kami membangun modularitas yang mengutamakan kontrol, efisiensi, dan kemandirian pengguna."

\-- KelolaSenseAqua
