# Irrigation Controller

A fully customizable 3-zone ESPHome-based irrigation controller designed for the LilyGO T-Relay board (ESP32). Supports daily schedule automation, rain delay features, manual cycle control, and real-time status updates via web interface or Home Assistant.

## 🔧 Features

- 🕒 **Scheduled Irrigation**
  - Up to 3 start times per day
  - Per-day enable/disable switches
  - Runtime-adjustable durations per zone

- 🌧️ **Rain Delay**
  - 24h and 48h rain delay options with automatic reset

- 🛠️ **Manual Control**
  - Trigger full-cycle irrigation manually
  - Cancel manual or scheduled cycles mid-run

- 🖥️ **Web Interface**
  - Built-in ESPHome web server with organized UI sorting groups
  - Password-protected access with grouped controls

- 📊 **Status & Monitoring**
  - Active zone indicator and irrigation mode sensor
  - Formatted uptime, system health, and connection status
  - “Irrigation Daily Summary” sensor with next schedule and current state

## 📦 Hardware

- **Board:** LilyGO T-Relay (ESP32, esp32dev)
- **Relays:** Controls 3 irrigation valves and 1 pump
- **LED:** Status indicator (inverted GPIO)
- **Power:** 5V via barrel jack or micro-USB

## 📐 GPIO Assignments

| GPIO   | Function               |
|--------|------------------------|
| GPIO21 | Pump Relay             |
| GPIO19 | Valve 1 – Zone 1       |
| GPIO18 | Valve 2 – Zone 2       |
| GPIO5  | Valve 3 – Zone 3       |
| GPIO25 | Status LED (inverted)  |

## 📝 Getting Started

1. Flash the ESPHome YAML to the LilyGO T-Relay board
2. Connect to Wi-Fi (fallback AP mode: `Irrigation Fallback Hotspot` / `saintmoor`)
3. Access the web interface or integrate with Home Assistant
4. Configure start times, durations, and enable switches

## 📄 Documentation

- [CHANGELOG.md](CHANGELOG.md) – version history and feature additions

## 🧑‍💻 Author

John Camm

---

> Built with [ESPHome](https://esphome.io/) and designed for reliable zone irrigation control.
