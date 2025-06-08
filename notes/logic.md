# Pseudocode – BLE Plant Health Monitor

## Goal
Measure soil moisture, temp, light and stream data to phone via BLE.

## Flow
- [ ] Read:
  - Soil moisture (analog)
  - Temp/humidity sensor (I2C)
  - Light level (analog)
- [ ] Send values over BLE every 10 s
- [ ] Visualize data on mobile app
- [ ] Trigger alert if soil < threshold
