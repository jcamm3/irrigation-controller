# Changelog – Irrigation Controller

## [1.4.2] – 2025-07-24
### Added
- Seasonal Adjustment (`input_number.seasonal_adjustment_percent`) to scale zone run durations
- Manual Rain Delay override (`input_boolean.rain_delay_manual`)
- Automated Rain Delay integration using OpenWeatherMap forecast
  - Forecast rain total and start time sensors
  - Binary sensor to determine "Will it Rain Today?"
- Integration with existing schedule logic to skip irrigation on rainy days

### Improved
- Internal logic to check both manual and automated rain delay before running any scheduled irrigation
- Enhanced debug logging at boot for configured schedule and lifetime water usage sync

---

## [1.4.1] – 2025-07-20
### Fixed
- Corrected `pulse_meter` logic for total and daily water usage tracking
- Daily reset of water usage and `daily_gallons_used` calculation

### Added
- `irrigation_mode` text sensor to reflect current system state
- Manual cycle pause/resume functionality
- `active_zone_time_remaining` countdown (numeric + text)
- Reset button for today's water usage
- Enhanced `irrigation_daily_summary` to include water data and pause state
