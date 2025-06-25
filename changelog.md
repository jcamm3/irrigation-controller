# Changelog – Irrigation Controller

All notable changes to this project are documented in this file.

---

## [1.3.0] – 2025-06-25
### Added
- `Irrigation Daily Summary` sensor with zone enable state, rain delay status, next event, and health overview.
- Connection status indicator and formatted uptime.
### Improved
- Schedule detection logic for "next scheduled event" and daily summary.
- Logging during manual and scheduled irrigation cycles.
### Fixed
- Daily reset of scheduled cycle cancellation flag at midnight.

---

## [1.2.0] – 2025-06-24
### Added
- `Cancel Scheduled Cycle` switch and associated flag logic.
- Global flag `scheduled_irrigation_disabled_today` for per-day skip handling.
### Improved
- UI grouping with sorting weights for zones, durations, and settings.
- Script structure for handling manual vs. scheduled cycles.

---

## [1.1.0] – 2025-06-22
### Added
- Enable switches for each schedule time (S1–S3).
- Rain delay switches with 24h/48h auto-reset.
- Sensors for countdown, next event, and current zone.
### Improved
- Icon consistency and entity naming.

---

## [1.0.0] – 2025-06-20
### Initial Release
- 3-zone irrigation system with daily scheduling.
- Manual cycle trigger, runtime duration control, and pump/valve switching.
- Web interface with OTA and Wi-Fi configuration.
