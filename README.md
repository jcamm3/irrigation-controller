<<<<<<< HEAD
# Irrigation Controller 🌿

**Version:** 1.2.0  
**Author:** John Camm  
**Last Updated:** 2025-06-24  

Smart multi-zone irrigation controller using ESPHome and a LilyGO T-Relay (ESP32) board. Supports scheduled watering, manual start, rain delay logic, and a grouped local web interface.

## 🚀 Features
- 3 irrigation zones with adjustable runtimes
- Up to 3 configurable scheduled start times
- Day-of-week enable toggles (Sunday–Saturday)
- Rain delay switches (24h / 48h) with auto-reset
- Manual start switch for full cycle
- ESPHome web interface with control group sorting
- Uptime, internal temperature, and network monitoring

## 🛠 Hardware
- LilyGO T-Relay (ESP32)
- GPIO21 – Pump Relay
- GPIO19 – Zone 1 Valve
- GPIO18 – Zone 2 Valve
- GPIO5  – Zone 3 Valve
- GPIO25 – Inverted Onboard LED

## 📁 Files
- `irrigation.yaml` – Main ESPHome configuration
- `docs/index.md` – Documentation entry point
- `docs/overview.md` – Functional summary
- `docs/hardware.md` – Hardware wiring and specs
- `docs/configuration.md` – YAML and control explanations

## 🔧 Getting Started
1. Customize `secrets.yaml` for your Wi-Fi.
2. Flash to LilyGO T-Relay using ESPHome.
3. Access via local IP or fallback hotspot.
=======
# irrigation-controller
>>>>>>> 0b804afc8f6d1549b980483aff418679fd004671
