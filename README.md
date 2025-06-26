# Irrigation Controller

ESPHome-based 3-zone irrigation controller with schedule automation, rain delay, manual cycle control, and a local web UI for configuration and monitoring. Designed for the LilyGO T-Relay ESP32 board.

## 🌿 Features

- 🚿 **3 Independent Zones** with runtime-adjustable durations
- 📅 **Daily Scheduling** with up to 3 start times per day
- ✅ **Per-Day Enable Switches**
- 🌧️ **Rain Delay** options (24h / 48h) with auto-reset
- 🔘 **Manual Cycle Trigger**
- ⏱️ **Real-Time Countdown** for active zone
- 🔄 **Dynamic UI Status** including active zone highlighting and time remaining
- 📋 **Irrigation Summary** text sensor
- 🌐 **Web Interface** with grouped sections and icons
- ⚙️ **System Monitoring:** temperature, uptime, state
- 🔁 **Cancel and Pause/Resume Cycle** controls

## 🧠 Hardware

- **Board**: LilyGO T-Relay (ESP32)
- **Power**: 5V DC
- **Relays**: 3 onboard (Zone 1–3)

## 🚀 Getting Started

1. Flash the board using ESPHome CLI:
   ```bash
   esphome run irrigation-controller.yaml
   ```
2. Connect to Wi-Fi and open the web UI.
3. Configure zone durations, schedule times, and enable days.

## 📦 Files

- `irrigation-controller.yaml` – Main configuration
- `CHANGELOG.md` – Version history
- `.gitignore` – Ignore generated files

## 📜 License

MIT License

---
Maintained by **John Camm**
