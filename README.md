# ESP32 Smart Temperature & Fan Controller

## Project Overview

This project is an ESP32-based Smart Temperature and Fan Controller designed using KiCad.

The system monitors temperature using a DHT11 sensor and controls a 12V DC fan through a MOSFET. An OLED display is used to display temperature information and system status.

## Features

- ESP32-WROOM-32 microcontroller
- DHT11 temperature sensor
- 0.91-inch I2C OLED display
- Automatic 12V DC fan control
- MOSFET-based fan switching
- Status LED
- Reset and control push buttons
- 5V to 3.3V voltage regulation
- 2-layer PCB design
- Custom PCB layout designed in KiCad
- Gerber and drill files generated

## Tools Used

- KiCad
- PCB Editor
- Schematic Editor
- 3D PCB Viewer

## Main Components

| Component | Part |
|---|---|
| Microcontroller | ESP32-WROOM-32 |
| Temperature Sensor | DHT11 |
| Display | 0.91" I2C OLED |
| Voltage Regulator | AMS1117-3.3 |
| MOSFET | NMOS |
| Fan | 12V DC Fan |
| LED | 5mm LED |
| Diode | SS14 |
| Buttons | 6mm Tactile Switch |

## PCB Design

### Schematic

![Schematic](Images/Schematic_View.png)

### PCB Routing

![PCB Routing](Images/PCB_Routing_View.png)

### 3D PCB View

![3D PCB](Images/3D_PCB_View.png)

## PCB Design Features

- Component placement optimized for routing
- ESP32 antenna keep-out area maintained
- Ground copper pour
- Clearly labeled components
- Mounting holes provided
- Connectors provided for external connections
- PCB silkscreen labeling

## Project Files

The repository contains:

- KiCad schematic
- KiCad PCB layout
- KiCad project file
- Gerber files
- Drill files
- PCB routing image
- 3D PCB image

## Project Status

PCB schematic and layout design completed in KiCad.

This repository is intended as a PCB design project and documentation portfolio.

## Author

Vishal Bodkhe
