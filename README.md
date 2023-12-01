# Dual channel fixed power supply
 
[![Version](https://img.shields.io/github/v/release/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/releases/tag/Initial)
[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![GitHub Issues](https://img.shields.io/github/issues/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr/jkordek1/TVZ_KTM_ApplicationBoard)](https://github.com/jkordek1/TVZ_KTM_ApplicationBoard/pulls)

Enclosure for dual AMES15-277NZ AC-DC converter.
Specifications:
• Universal Input: 85 - 305VAC/100 - 430VDC
• Operating Temp: -30 °C to +70 °C
• High isolation voltage: Up to 4000VAC
• Low ripple & noise, 150mV(p-p) typ.
• Output short circuit, over-current, over-voltage protection
• Regulated Output 

## Images
<p align="center">
 <img width="1000" src="https://raw.githubusercontent.com/jkordek1/Dual-channel-fixed-power-supply/main/Images/Front_v4.png">
</p>

## Work in progress
This project is marked as work in progress and is not ready yet for a full release.

 ## Features
 - Toggle switches
 - LEDs
 - MCP2551 high-speed CAN transceiver
 - Digital I2C temperature sensor with address selection jumpers
 - UART, CAN, Parallel, analog, SPI and I2C communications between master and slave
 - Probe clips for easy oscilloscope connections
 
 ## Folder structure
    .
    ├── ...
    ├── 3d models               # 3D models of components
    ├── Images                  # Images of the project
    ├── KiCAD files             # Main KiCAD project folder
    │   ├── Datasheet           # Datasheet collection
    │   ├── jlcpcb              # jlcpcb production files
    │   ├── Graphics            # Custom graphics for PCB
    │   └── gerber              # gerber output folder
    └── ...
 
