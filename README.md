# Edge-Computing Smart Home Appliance

## Project Overview
An intelligent smart home system using hardware interrupts and automated gas safety overrides.

## Components Used
- Arduino Uno
- PIR Motion Sensor
- MQ-2 Gas Sensor
- 3 Green LEDs
- 1 Red LED
- Buzzer
- 220Ω Resistors

## Working Principle
1. PIR sensor detects human motion.
2. Hardware interrupt activates the smart lighting array.
3. MQ-2 gas sensor monitors gas levels.
4. When gas value exceeds the threshold, the safety override activates.
5. Lights turn OFF, red LED flashes, and buzzer sounds.

## Technologies
- Arduino C++
- Wokwi Simulator
- Hardware Interrupts
- Sensor-based Automation

## Files
- `sketch.ino` – Arduino program
- `diagram.json` – Circuit connections
