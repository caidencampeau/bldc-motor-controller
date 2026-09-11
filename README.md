# BLDC Motor Controller

## Project Overview

This project is a custom 12–24 V three-phase BLDC motor controller designed as a professional hardware-development and portfolio project.

The goal is to develop experience in power electronics, PCB design, embedded motor control, sensing, protection, communications, hardware bring-up, and engineering documentation.

## Rev A Target Specifications

* 12–24 VDC input
* Approximately 5 A continuous phase current
* Approximately 10 A short-duration peak phase current
* 50–120 W BLDC motor target
* STM32G431-class microcontroller
* DRV8353-class three-phase gate driver
* Six external 60 V N-channel MOSFETs
* Hall-sensored six-step commutation
* Approximately 20 kHz PWM
* Closed-loop PI speed control
* Three-shunt current sensing
* DC bus voltage sensing
* Power-stage temperature sensing
* CAN/CAN-FD communication
* UART telemetry/debug
* SWD programming/debug
* 4-layer PCB
* Hardware overcurrent, undervoltage, gate-driver fault, and thermal protection

FOC may be explored in a later revision but is not a Rev A requirement.

## Project Goals

The main goals of this project are to:

* Learn professional PCB design and hardware-development practices
* Select components using electrical requirements, calculations, and datasheets
* Gain experience with Altium Designer
* Use LTspice and MATLAB/Simulink where useful
* Learn power-electronics PCB layout and grounding
* Develop current, voltage, and temperature
