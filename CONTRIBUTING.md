# 🤝 Contributing to KelolaSenseAqua

Thank you for your interest in contributing to **KelolaSenseAqua**! This document outlines the process to contribute effectively to this project, especially since it is modular, multi-language, and hardware-software integrated.

---

## 📦 Repository Structure (High-Level)

```
KelolaSenseAqua/
├── docs/              ← Documentation
├── hardware/          ← KiCad, PCB, BoM
├── firmware/          ← MCU code (CH32/ATmega)
├── services/          ← Backend services
├── frontend-admin/    ← Web Admin (Next.js)
├── mobile-app/        ← Mobile App (Flutter)
├── diagrams/          ← Mermaid/Drawio
├── ci/                ← CI/CD & GitHub Actions
├── docker/            ← Containerization & K8s
└── README.md
```

---

## ⚙️ Git Flow

We follow a structured Git workflow:

- `main` → stable production release
- `develop` → active development base
- `feature/xyz` → feature branches (merged to develop)
- `bugfix/xyz` → for small fixes (to develop)
- `hotfix/xyz` → for urgent fixes (to main)
- `release/x.y.z` → pre-release version (merged to main)

### 💡 Naming Convention

- `feature/pcu-protection`
- `feature/mobile-dashboard`
- `bugfix/pin-mapping-error`

---

## 🧪 Development Guidelines

### 🧼 Code Style

- JavaScript/TypeScript: Follow Prettier format (`.prettierrc` is provided)
- Python: Use `black`
- C/C++: Follow PlatformIO style guide

### ✅ Commit Message Convention

Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/):

```
feat: add relay cutoff feature for PCU
fix: resolve crash in sensor reading module
refactor: clean up MQTT handler logic
```

---

## 🧰 Tools Required

| Domain     | Tool             |
| ---------- | ---------------- |
| PCB Design | KiCad            |
| MCU Dev    | PlatformIO       |
| Web Dev    | Node.js, Next.js |
| Mobile     | Flutter          |
| Backend    | Go, Python, Nest |
| Infra      | Docker, K8s      |
| Cloud      | AWS              |

---

## 📝 How to Contribute

1. **Fork the repository**
2. **Create a new branch**: `feature/your-feature-name`
3. **Write your code / add docs**
4. **Make sure it builds and passes all tests**
5. **Submit a Pull Request to `develop`**
6. Wait for review or feedback

---

## 📣 Communication

- Use GitHub Issues for bugs, proposals, or questions
- Use Discussions for long-term ideas or brainstorming

---

## 👥 Contributors Agreement

By contributing, you agree to:

- Respect others’ contributions
- Not upload malicious code or sensitive data
- Share R\&D with proper attribution if inspired from other open projects

---

Thank you again for helping grow **KelolaSenseAqua** 💧

> "Solve real problems with elegance, empathy, and engineering."
