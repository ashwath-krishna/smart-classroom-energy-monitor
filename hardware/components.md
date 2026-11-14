# Hardware Components

## Components Used in the Proposed Design

| Component | Purpose |
|---|---|
| ESP32 | Main microcontroller |
| mmWave Radar Sensor | Primary occupancy detection |
| PIR Sensor | Secondary occupancy detection |

## Component Description

### 1. ESP32
The ESP32 reads sensor signals and is intended to communicate with the Python dashboard through Wi-Fi.

### 2. mmWave Radar Sensor
Used as the primary sensor to detect classroom occupancy, including subtle movements depending on the selected module.

### 3. PIR Sensor
Used as a secondary sensor to detect movement through changes in infrared radiation.

## Additional Requirements
- Power supply
- Connecting wires
- Suitable mounting materials
- Optional appliance-state sensing components

## Note
Exact module models and electrical specifications are yet to be finalized.
