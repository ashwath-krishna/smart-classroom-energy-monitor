# Sensor Selection Notes

## mmWave radar — primary sensor

The project proposes mmWave radar as the primary occupancy sensor. Depending on the module and installation, mmWave may detect subtle body movement or breathing-like motion, potentially helping when a person is sitting still.

**Limitations to investigate:** performance varies by module and environment. Moving objects, including fan blades, may cause unwanted detections. Mounting, sensitivity settings, and tuning need practical evaluation.

## PIR — secondary sensor

PIR sensing responds to changes in infrared radiation associated with movement. It can provide useful evidence when a person enters or moves around.

**Limitation:** a person who remains still for a long period may not create enough change for reliable detection.

## Why combine them?

The proposed logic treats a credible presence indication from either sensor as evidence that the room is occupied. The combined approach is intended to reduce false-vacancy decisions, but this must be verified experimentally rather than assumed.

## Selection details to record

When exact modules are selected, add their manufacturer, model number, supply voltage, output type, pinout, detection range, configuration options, and datasheet link here. These specifications are not provided in the current project material.
