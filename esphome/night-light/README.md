# Night Light

ESPHome configuration for driving a single white LED with an ESP32-C3 Super Mini and exposing it to Home Assistant.

## Wiring

- Connect GPIO4 to the anode of the LED through a suitable current-limiting resistor (around 330Ω).
- Connect the cathode of the LED to GND.
- Power the ESP32-C3 Super Mini via its 5V or 3.3V input as required.

With this wiring the LED can be turned on/off and dimmed from Home Assistant.

