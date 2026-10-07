# Arduino Automatic Street Light System

## Objective

To automatically control an LED based on the surrounding light intensity
using an LDR sensor and Arduino.

## Components

- Arduino Uno
- LDR sensor
- LED
- 220Ω resistor
- Breadboard
- Jumper wires

## Working

The LDR sensor is connected to analog pin A0. The Arduino continuously
reads the light intensity. When the light level falls below the defined
threshold, the LED is switched ON. When sufficient light is available,
the LED is switched OFF.

## Expected Output

The LED should automatically turn ON in low-light conditions and turn OFF
when sufficient light is available.

## QA Approach

The project is tested for:

- LDR sensor connection
- Analog input
- Light threshold
- LED operation
- Serial Monitor output
- Program compilation


## QA Resolution Tracking

The automatic street light project was tested using GitHub Issues.
Sensor connectivity, light threshold, LED operation, analog pin
configuration and Serial Monitor output were reviewed during QA.
All identified issues were documented and resolved.
