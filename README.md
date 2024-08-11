# INA219 High Side DC Current Sensor Breakout Board - Custom Design

![INA219 Sensor](./Images/TOP%203D_INA219%20V1.0_2024-08-11.png)

## Description

This repository contains the custom design files for a modified INA219 High Side DC Current Sensor Breakout Board. The design is fully compatible with the Adafruit INA219 module but incorporates several key improvements to enhance performance and reliability.

### Key Improvements

- **Redesigned Layout:** The PCB layout has been completely redesigned, maintaining the same form factor and mounting hole placements as the original Adafruit module.
- **EMI Shielding:** Integrated electromagnetic interference (EMI) shielding for improved signal integrity in noisy environments.
- **4-Wire Kelvin Connection:** Correct 4-wire Kelvin connection for more accurate current sensing, minimizing the impact of trace resistance.
- **Matched Area for Vin- and Vin+:** Ensures balanced signal paths for Vin- and Vin+, improving measurement accuracy.
- **Decoupling Capacitor:** A decoupling capacitor has been added across the amplifier input pins to reduce noise and improve stability.
- **Configurable I2C Address:** I2C address pins (A0 and A1) can be jumper soldered to either ground or VCC, allowing for flexible address configuration.

## Repository Contents

- **Schematics:** Detailed schematic diagrams in PDF and EasyEDA format.
- **Gerber Files:** Ready-to-manufacture Gerber files for PCB fabrication.
- **3D Files:** 3D models of the PCB for visual inspection and mechanical integration.
- **EasyEDA Project:** Direct link to the EasyEDA project for further modifications and enhancements.

## Getting Started

To use this design:

1. **Review the Schematics:** Understand the circuit design and verify it meets your project requirements.
2. **Manufacture the PCB:** Use the provided Gerber files to order PCBs from your preferred manufacturer.
3. **Assemble the Board:** Solder the necessary components onto the PCB.
4. **Integration:** Integrate the sensor into your project, using the same connections as the original Adafruit INA219 module.

## Images

![Schematic Diagram](https://example.com/schematic-image-url) <!-- Replace with your actual image URL -->

![3D PCB View](https://example.com/3d-pcb-image-url) <!-- Replace with your actual image URL -->

## EasyEDA Project

You can access the EasyEDA project for this design [here](https://easyeda.com/yourusername/ina219-custom-design). This allows you to modify the design, generate BOMs, and more.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
