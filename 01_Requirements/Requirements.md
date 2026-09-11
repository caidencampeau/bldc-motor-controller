# Rev A System Requirements

## Power
- Input voltage: 12–24 VDC
- Continuous phase current: 5 A
- Peak phase current: 10 A short-duration
- Motor power target: 50–120 W

## Motor Control
- Three-phase BLDC motor
- Hall-sensored six-step commutation
- PWM frequency: approximately 20 kHz
- Closed-loop PI speed control

## Controller
- STM32G431-class MCU
- DRV8353-class gate driver
- Six external N-channel MOSFETs

## Sensing
- Three-shunt phase-current sensing
- DC bus voltage sensing
- Power-stage temperature sensing

## Communications
- CAN/CAN-FD
- UART debug/telemetry
- SWD programming/debug

## Protection
- Hardware overcurrent protection
- Undervoltage protection
- Gate-driver fault detection
- Thermal protection

## PCB
- 4-layer PCB
- Designed for low-noise current sensing
- EMC-conscious layout
- Accessible test points for bring-up

## Future / Not Required for Rev A
- FOC
- Sensorless control
- Regenerative braking