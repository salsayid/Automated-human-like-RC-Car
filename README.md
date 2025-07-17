# Automated Human-like Moving Target

## Overview

This project combines an RC car with a mounted football-wall dummy wearing a numbered T-shirt to create a human-like moving target. The system allows for controlled-speed navigation across a field, enabling accurate testing of HUDL cameras (e.g., Nexus) and wearable tracking devices (e.g., Wimu). The goal is to simulate realistic motion for performance evaluation and data collection.

## Features

- RC car platform with manual and semi-autonomous navigation capability
- Lightweight dummy securely mounted using a custom 3D-printed structure
- Numbered jersey attached and stabilized to improve camera visibility
- Integration with Wimu device for motion tracking and data logging
- Configurable autopilot system using Pixhawk 6C and GPS module
- Field-tested for compatibility with HUDL camera systems

- <img width="2040" height="1530" alt="image" src="https://github.com/user-attachments/assets/a42cb394-0039-40b5-8638-29a56a7116a0" />
<img width="1392" height="748" alt="image" src="https://github.com/user-attachments/assets/a4a3893f-9d55-4332-84b2-ba63cc510ba3" />



## System Components

- RC Car (chassis and motor controller)
- Football-wall dummy (lightweight model)
- Pixhawk 6C flight controller
- GPS module
- Power module and cabling
- Wimu wearable device
- Custom 3D-printed mounting hardware
- Numbered sports jersey


## Mechanical Design

The dummy is mounted using a low-profile support structure designed to maintain stability during motion. A rotational boom system allows for limited passive alignment with wind forces to reduce unwanted spin. Cable management and component housing are included in the design for field durability.

## Usage

1. Power on the RC car and autopilot system.
2. Place the Wimu on the back of the dummy once the LED indicator cycles through RED, GREEN, and BLUE.
3. Use manual RC control or preloaded autopilot missions for navigation.
4. Record video from HUDL cameras and collect Wimu data during the test.
5. Export Wimu data and GPS paths for post-processing and analysis.

## Data & Visualization

- Wimu data can be downloaded via USB and converted for analysis.
- GPS paths can be exported from SPRO and imported into Google Earth (KML format).
- Data is used to compare target velocity and movement consistency.

## Repository Structure

- `/docs` – Overview slides and documentation
- `/hardware` – BOM and mounting diagrams
- `/data` – Sample Wimu recordings and GPS paths
- `/images` – Photos and video stills from test runs

## Credits

- Sayid Alsayid 
- Carlos Agell
