# Hardware

## Required Components
- LilyGO T-Relay (ESP32) board
- 3 solenoid valves (12V or 24V)
- 1 pump relay or contactor (if using high-power pump)
- Power supply (for pump and valves)

## GPIO Assignments

| Function         | GPIO Pin | Notes                     |
|------------------|----------|---------------------------|
| Pump Control     | GPIO21   | Activates pump relay      |
| Zone 1 Valve     | GPIO19   | First irrigation zone     |
| Zone 2 Valve     | GPIO18   | Second irrigation zone    |
| Zone 3 Valve     | GPIO5    | Third irrigation zone     |
| Status LED       | GPIO25   | Inverted onboard LED      |

## Notes
- GPIO25 is used as an inverted logic status LED (active LOW).
- Relays should match the power draw of connected valves/pumps.
