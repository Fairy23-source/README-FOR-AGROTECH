# Agrotech-v1

> Smart farming dashboard integrating IoT sensors, disease detection, and crop analysis.

![GitHub stars](https://img.shields.io/github/stars/Ratnadip143/Agrotech-v1?style=for-the-badge&logo=github) ![GitHub forks](https://img.shields.io/github/forks/Ratnadip143/Agrotech-v1?style=for-the-badge&logo=github) ![GitHub issues](https://img.shields.io/github/issues/Ratnadip143/Agrotech-v1?style=for-the-badge&logo=github) ![Last commit](https://img.shields.io/github/last-commit/Ratnadip143/Agrotech-v1?style=for-the-badge&logo=github) ![License](https://img.shields.io/badge/license-MIT-green?style=for-the-badge)
##📑 Table of Contents

- [Description](#description)
- [Key Features](#key-features)
- [Use Cases](#use-cases)
- [Quick Start](#quick-start)
- [Project Structure](#project-structure)
- [Deployment](#deployment)
- [Contributing](#contributing)
- [License](#license)
## 📝 Description

AgroTech is a smart farming and irrigation solution designed to help farmers monitor crops, assess soil health, and make informed agricultural decisions. By integrating IoT sensors, web technologies, and mobile access, the project addresses the challenge of real-time crop monitoring and early disease identification. It provides a central hub where users can inspect ambient conditions and make data-driven adjustments.
## ✨ Key Features

- **🌿 Plant Disease Detection** — Analyze uploaded crop images or captures from an ESP32-CAM to identify plant conditions and receive treatment suggestions.
- **📊 Live Sensor Visualizations** — Render real-time temperature, humidity, and soil moisture metrics using interactive frontend charts powered by Chart.js.
- **🔥 Firebase Backend Integration** — Store live agricultural telemetry data and manage user authentication utilizing Firebase services.
- **📷 ESP32-CAM Field Monitoring** — Capture and stream real-time images over a local WiFi network directly into the web application's detection interface.
- **🧮 Seed Requirement Calculator** — Calculate necessary seed quantities and total weight across multiple crop categories based on custom inputs.
## 🎯 Use Cases

- Setting up an automated greenhouse monitoring system that tracks soil moisture, temperature, and ambient humidity via ESP32 microcontrollers.
- Diagnosing plant foliage health on-site by uploading leaf photographs to detect diseases and view suggested treatments.
- Visualizing live environmental telemetry on a unified Web dashboard backed by a Firebase Realtime Database.
- Planning seasonal planting parameters by calculating seed count and weight requirements for custom acreage.
## ⚡ Quick Start

```bash
# 1. Clone the repository
git clone https://github.com/Ratnadip143/Agrotech-v1.git
# See the Development Setup section below

```
## 📸 Preview

### 🔐 Login
![Login](https://github.com/Ratnadip143/Agrotech-v1/blob/main/Preview-1.png)

### 🏠 Dashboard
![Dashboard](https://github.com/Ratnadip143/Agrotech-v1/blob/main/Preview-2.png?raw=true)



### 🌱 Disease Detection
![Detection](https://github.com/Ratnadip143/Agrotech-v1/blob/main/Preview-3.png?raw=true)

### Select a Tool
![Seect](https://github.com/Ratnadip143/Agrotech-v1/blob/main/Preview-4.png?raw=true)
## 📁 Project Structure

```
.
├── Agrotech app Password.png
├── Preview-1.png
├── Preview-2.png
├── Preview-3.png
├── Preview-4.png
├── firebase.json
└── public
    ├── 404.html
    ├── LICENSE
    ├── SECURITY.md
    ├── android-chrome-192x192.png
    ├── android-chrome-512x512.png
    ├── apple-touch-icon.png
    ├── demo.html
    ├── favicon-16x16.png
    ├── favicon-32x32.png
    ├── favicon.ico
    ├── index.html
    └── site.webmanifest
```
## 🚢 Deployment

### Firebase Hosting

`firebase deploy`
## 👥 Contributing

Contributions are welcome! Here's the standard flow:

1. **Fork** the repository
2. **Clone** your fork: `git clone https://github.com/Ratnadip143/Agrotech-v1.git`
3. **Branch**: `git checkout -b feature/your-feature`
4. **Commit**: `git commit -m 'feat: add some feature'`
5. **Push**: `git push origin feature/your-feature`
6. **Open** a pull request

Please follow the existing code style and include tests for new behavior where applicable.
## 📜 License

This project is licensed under the **MIT** License.

---
