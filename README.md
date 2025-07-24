# Irrigation Controller (v1.4.2)

**Author:** John Camm  
**Board:** LilyGO T-Relay / ESP32 (esp32dev)  
**Firmware:** ESPHome 2025.7.2  

## Overview

An ESPHome-powered irrigation controller with:
- 3 irrigation zones (independent runtime + day scheduling)
- Manual + scheduled cycle control
- Seasonal adjustment scaling
- Real-time countdown & mode reporting
- Pulse-based water usage tracking (flow rate, daily, total)
- Rain delay support (manual + OpenWeatherMap forecast)

## Key Features

- 🌧️ Forecast-based Rain Delay via OWM
- 🕒 Multi-time Daily Schedule per Zone
- 💧 Water Flow Metering (gallons/min, daily, lifetime)
- 📊 Daily Irrigation Summary Text Sensor
- 🟡 Manual Cycle Controls + Pause/Resume
- 📡 Web + OTA + Home Assistant Integration

## Setup

1. Flash `irrigation.yaml` to LilyGO T-Relay board.
2. Ensure OpenWeatherMap integration is available in Home Assistant.
3. Install `rain_forecast_openweathermap.yaml` package.
4. Calibrate flow sensor (pulses/gal) as needed.
5. Optional: Add Lovelace dashboard cards for summary and water graphing.

## Version History

See `CHANGELOG.md` for details.
