# Frost Warning – Home Assistant Blueprint (BOM)

This blueprint sends a mobile notification if frost is likely based on Bureau of Meteorology (BOM) data (temp + dew point).

- ⚠️ Triggers early morning (custom time)
- ❄️ Checks BOM temp and dew point difference
- 📱 Sends a mobile app notification

## Requirements

- [BOM Custom Component](https://github.com/bremor/bureau_of_meteorology)
- Home Assistant mobile app (for notifications)

## Installation

1. Copy to `blueprints/automation/yourusername/frost_warning_bom.yaml`
2. Reload automations
3. Create new automation from blueprint in UI