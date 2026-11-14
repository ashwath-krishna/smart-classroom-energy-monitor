# Performance Metrics

## 1. False-vacancy events

A false-vacancy event occurs when the system declares the room vacant while one or more people are actually present. This is especially important because it could lead to lights being switched off while the room is occupied.

Possible rate:

\[
\mathrm{False\ vacancy\ rate} =
\frac{\mathrm{False\ vacancy\ decisions}}{\mathrm{Observed\ occupied\ decisions}} \times 100\%
\]

Define the counting unit consistently before testing (for example, decision intervals or occupancy episodes).

## 2. False-occupancy events

A false-occupancy event occurs when the system reports occupied while the room is actually empty.

Possible rate:

\[
\mathrm{False\ occupancy\ rate} =
\frac{\mathrm{False\ occupancy\ decisions}}{\mathrm{Observed\ vacant\ decisions}} \times 100\%
\]

## 3. Time to declare vacancy

Measure the elapsed time between the room becoming empty (according to observation) and the system declaring Vacant. Report the configured timeout and measured delay separately.

## 4. Energy-estimate comparison

If an independent reference reading is available, compare it with the dashboard estimate. State the reference instrument/method, measurement period, appliance ratings, and assumptions. Do not call an estimate a measured energy value.

## Reporting table template

| Trial | Scenario | Actual occupancy | PIR-only result | Dual-sensor result | Vacancy delay | Notes |
|---|---|---|---|---|---|---|
| 1 | Sitting still | | | | | |
| 2 | Entering/leaving | | | | | |
| 3 | Empty room, fan running | | | | | |
| 4 | Different distance | | | | | |
