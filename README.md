# 🛠️ PCB Design Practice Challenge
24 hands-on PCB projects — from basic power supplies to a complete Arduino Nano dev board


## 📌 About This Repo
This repository documents my journey through the real circuits designed end-to-end in KiCad, starting from simple linear power supplies and building up to sensor modules, motor/actuator control, switching regulators, and a full microcontroller development board.

Each project = one circuit + one new PCB design concept. No theory dumps — just schematics, layouts, and the design decisions behind them.

💡 Every project here includes schematics, PCB layout files, and (where finished) Gerbers/BOM, version-controlled as I go.

## 🚀 Progress Tracker

| # | Project | Core Skills Covered | Status |
|---|---------|----------------------|--------|
| 01 | 12V to 5V DC Power Supply | Linear regulator circuit, schematic capture, 2-layer layout | ⬜ |
| 02 | 12V to 3.3V DC Power Supply | Voltage regulation, footprint placement, decoupling | ⬜ |
| 03 | Triple Voltage Power Supply | Multi-rail regulation, multiple regulator ICs on one board | ⬜ |
| 04 | AC to DC Power Supply Design | Rectification, bridge rectifier, filtering capacitors | ⬜ |
| 05 | Astable Multivibrator (NE555) | Timer IC circuit design, RC network sizing | ⬜ |
| 06 | 2-Channel Relay Module | Relay driver circuit, flyback diode, isolation | ⬜ |
| 07 | IR Sensor Module (LM358) | Comparator circuit, op-amp biasing, sensor interfacing | ⬜ |
| 08 | High DC Voltage Sensor Module | Voltage divider sensing, isolation, protection | ⬜ |
| 09 | Soil Moisture Sensor Module | Analog sensor interfacing, signal conditioning | ⬜ |
| 10 | MAX30100 Heart Rate Monitor | I2C sensor integration, biomedical sensor layout | ⬜ |
| 11 | Automatic AC Switch (PIR Sensor) | PIR interfacing, relay/triac switching, mains safety | ⬜ |
| 12 | Automatic Plant Watering System | Sensor + actuator integration, pump/relay driving | ⬜ |
| 13 | Gesture-Based Home Automation | Gesture sensor integration, relay/wireless control | ⬜ |
| 14 | DC Motor Speed Control (Arduino) | PWM motor control, driver IC layout | ⬜ |
| 15 | 1602 LCD & Navigation Buttons | Parallel LCD interfacing, button debounce circuitry | ⬜ |
| 16 | Line Follower Robot (IR Array) | Multi-sensor array, motor driver, robotics layout | ⬜ |
| 17 | DC-DC Buck Converter (LM2596) | Switching regulator design, inductor/cap selection | ⬜ |
| 18 | 3.3V Buck-Boost Converter (TPS650230) | Buck-boost topology, wide input range regulation | ⬜ |
| 19 | Li-Ion Battery Charger (TP5100) | Battery charge management, protection circuitry | ⬜ |
| 20 | Arduino Nano Dev Board — Part 1 | MCU board schematic: power, USB, crystal | ⬜ |
| 21 | Arduino Nano Dev Board — Part 2 | Full board layout, routing, component placement | ⬜ |
| 22 | Arduino Nano Dev Board — Part 3 | Final review, DRC, Gerber export, panelization | ⬜ |


## 🎯 Skills I'm Building
Schematic Capture · Footprint & Symbol Design · PCB Layout & Routing · Power Supply Design (Linear, Buck, Buck-Boost) · Sensor & Actuator Interfacing · Battery Management · DRC/ERC & Manufacturing Prep

By project 24, this challenge covers the full board-design workflow used in real embedded/hardware products:

- **Power Design** — linear regulators, AC-DC rectification, buck & buck-boost converters, battery charging
- **Sensor Interfacing** — IR, PIR, gesture, moisture, high-voltage, and biomedical (MAX30100) sensor modules
- **Actuator & Motor Control** — relay switching, PWM motor drivers, robotics layouts
- **Display & UI** — LCD interfacing, navigation controls
- **Full Board Design** — a complete Arduino Nano-class development board from schematic to Gerbers

## 🗂️ Repo Structure
```
pcb-design-practice-challenge/
├── 01-12v-to-5v-power-supply/
├── 02-12v-to-3.3v-power-supply/
├── ...
├── 22-arduino-nano-dev-board-part3/
├── 23-course-closure/
├── LICENSE
└── README.md
```
Each folder contains the KiCad project files, exported Gerbers/BOM (once finalized), and any reference images for that project.

## 🎓 Course Reference
Based on the [Practice Projects for PCB Designers](https://www.youtube.com/playlist?list=PLiieClpxhGSh8kq3vfBSml4NfWSR8fXJi) playlist by Vaibhav Sugandhi (Linked Frequency).

## 🛠️ Tools Used
- KiCad (schematic capture, PCB layout)

## 📜 License
This project is licensed under the MIT License.

⭐ If you're also learning PCB design, feel free to fork this and track your own boards!
