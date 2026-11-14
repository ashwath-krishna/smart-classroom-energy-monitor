# Circuit Design Notes

The available project description identifies an ESP32, a mmWave radar sensor, and a PIR sensor, but does not provide a finalized circuit diagram or exact module models.

## Before wiring

1. Record the exact model number and datasheet for each sensor and the ESP32 board.
2. Confirm each module's supply-voltage range and output logic voltage.
3. Confirm whether outputs are digital, UART, or another interface.
4. Check ESP32 pin compatibility and avoid pins reserved for boot/configuration unless their use is understood.
5. Establish a common ground where required by the chosen interfaces.
6. Test each sensor independently before combining them.

## Appliance state

The project presentation leaves the method for confirming light/fan ON state unresolved. Decide whether this will be measured through a suitable isolated current-sensing arrangement, obtained from a switch-state input, or entered manually. Any mains-voltage work must be designed and checked by a qualified person; do not connect mains wiring directly to an ESP32.

## Status
This is a planning document, not a verified wiring guide. Add a tested schematic only after selecting the exact components.
