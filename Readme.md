# Mini Environmental Monitoring PCB

A mini environmental monitoring system designed using **KiCad 10** and an **Arduino Nano**. This project monitors temperature and ambient light intensity and provides an interface for an OLED display and LED indicators.

## Features

- Temperature sensing using an LM35 temperature sensor
- Ambient light detection using a Light Dependent Resistor (LDR)
- OLED display interface using I²C communication
- LED status indicators controlled by the Arduino Nano
- Custom electronic schematic design
- Custom PCB layout and routing
- Power and ground planning
- Electrical Rules Check (ERC) and Design Rules Check (DRC)

## Components Used

| Component | Purpose |
|---|---|
| Arduino Nano | Main controller |
| LM35 temperature sensor | Measures temperature |
| Light Dependent Resistor (LDR) | Detects ambient light intensity |
| OLED display connector | Connects the OLED display |
| LEDs | Visual status indication |
| 330 Ω resistors | Limit LED current |
| 10 kΩ resistor | LDR voltage divider |
| 100 nF capacitor | Power supply decoupling |
| 10 µF capacitor | Power supply filtering |

## Tools and Technologies

- **KiCad 10** — Schematic design and PCB layout
- **Arduino Nano** — Embedded controller
- **Electronic Circuit Design** — Component selection and circuit connections
- **PCB Design** — Component placement, track routing, and design verification

## Circuit Schematic

The circuit schematic illustrates the electrical connections between the Arduino Nano, LM35 temperature sensor, LDR voltage divider, OLED connector, LEDs, resistors, and capacitors.

![Circuit Schematic](./images/schemetic.png)

## PCB Layout

The PCB layout illustrates the physical arrangement of the electronic components and the copper tracks connecting them.

![PCB Layout](./images/pcbLayout.png)

## Design Verification

- [x] Schematic design completed
- [x] Electrical Rules Check (ERC)
- [x] Component footprint assignment and verification
- [x] PCB component placement
- [x] PCB track routing
- [x] Design Rule Check (DRC)

## Project Status

The schematic and PCB design were developed using KiCad 10. Hardware testing and firmware development can be documented separately as those stages are completed.

## Future Improvements

- Develop Arduino firmware for temperature and light measurements
- Display real-time sensor readings on the OLED display
- Calibrate and evaluate sensor accuracy
- Test the assembled PCB under different environmental conditions
- Improve the design based on testing results

## Learning Objectives

- Understand electronic schematic design
- Learn component selection and footprint assignment
- Practice PCB component placement and track routing
- Apply power and ground planning principles
- Perform ERC and DRC checks
- Develop practical PCB design skills

---

**Designed using KiCad 10.**