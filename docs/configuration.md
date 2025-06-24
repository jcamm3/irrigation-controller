# Configuration

## ESPHome YAML
All control logic resides in `irrigation.yaml`. Key configuration sections include:

### Sprinkler Component
Manages zone cycling:
- `valve_switch_id`: GPIO pins for each zone
- `run_duration_number`: runtime (1–240 min)

### Schedule and Timing
- `datetime:` defines start times
- `switch:` template switches enable schedules per day

### Rain Delay Logic
Two template switches provide:
- 24-hour delay
- 48-hour delay
Each resets automatically after the defined time.

### Manual Control
The "Manual Start Full Cycle" switch triggers the full irrigation cycle immediately.

### Web Interface
Groups are organized as:
- 🌱 Overview
- 🕒 Schedules
- ⏱️ Durations
- 🚿 Zones
- 🟢 Manual Control
- 📅 Active Days
- ⚙️ System Info
