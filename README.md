# Nitehawk-SB V2

Nitehawk V2 is a toolboard featuring STM32G0B1 MCU, TMC2209 stepper drive, ADXL345 Accelerometer, and USB hub. The form factor is based on [hartk’s two piece stealthburner toolhead PCB](https://github.com/hartk1213/Voron-Hardware-SBPCB/tree/master/Stealthburner_Toolhead_PCB) but with some minor changes. Nitehawk-36's USB based connection method allows for a simple and easy setup compared to other CAN toolboards. The USB connnection also allows for a secondary USB port to connect your nozzle webcam or eddy current probe.

<img title="" src="./Images/Nitehawk-SB-main.jpg" alt="Nitehawk-SB-main.jpg" width="547">

## Features

- Convenient wiring, no more complicated and error prone breakout cables
- USB Klipper connection, no additional software or hardware setup compared to CAN.
- Secondary USB port, an onboard USB port allows you to connect a second USB - device to your toolhead without running an additional umbilical cable.
- Custom toolhead cable, a single combined USB data and power cable rated for drag chain use, but can also be used in umbilical configuration.
- Convenient Input Shaping, run input shaper calibration at anytime with an onboard ADXL345 accelerometer.
- Tachometer enabled fan ports (PCF and HEF), allowing for fan speed detection.

## Change list from Nitehawk-SB V1

- MCU changed from RP2040 to STM32G0B1.
- Added USB hub.
- Added I2C port.
- Reversed header gender between main toolboard and fan adapter PCB. The headers are also now keyed prevent misalignment.
- Improved ESD performance.
- Probe, TH0, XY Endstop ports changed from JST-XH2.5 to JST-PH2.0