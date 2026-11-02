# Changelog

Notable changes to this project are documented here.

## version 1

### Added

- Initial Home Assistant Modbus TCP package for the EM2GO Home wallbox.
- Sensors for charger and cable state, error code, total and phase power, current, voltage, energy, duration, current limits, communication timeout, charge mode, charging phases, and serial-number registers.
- Template controls for fallback current, charging current limit, Modbus timeout, charge mode, charging phases, and start/stop charging commands.
- Standalone Lovelace dashboard for wallbox controls, measurements, and diagnostics.
- README installation guidance, source attribution, safety notes, and tested hardware details for model `EMH011AC1RW`.
- Notes documenting observed device-specific behavior: the app-configured current ceiling limits Modbus charging, per-phase power readings require an empirically observed scale factor, and serial-number registers are displayed as hexadecimal words.