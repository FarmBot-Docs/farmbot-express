---
title: "Farmduino Express"
slug: "farmduino-express"
description: "The Farmduino microcontroller features a board layout and connectors that are optimized for FarmBot. It receives G-code commands from the Raspberry Pi and then moves the motors, reads sensors, activate peripherals, and more. It features integrated Trinamic TMC2130 stepper drivers for ultra quiet movements."
price: $75.00
quantity:
  standard: 1
  xl: 1
specs:
  Microcontrollers: ATmega2560
  Stepper Drivers: Trinamic TMC2130
  Input Voltage: 24V
  Fuse: 7.5 amp blade fuse
  Power Receptacle: Black 3-pin receptacle (<a href="https://www.molex.com/molex/products/part-detail/pcb_headers/2002411113">Molex Part 2002411113</a>
  Vacuum Peripheral Receptacle: Black 3-pin receptacle (<a href="https://www.molex.com/molex/products/part-detail/pcb_headers/2002411113">Molex Part 2002411113</a>)
  Other Peripheral Receptacles: (Water and Lighting) - Black 2-pin receptacle (<a href="https://www.molex.com/molex/products/part-detail/pcb_headers/1510481206">Molex Part 151048-1206</a>)
  Motor Receptacles: Black 4-pin receptacle (<a href="https://www.molex.com/molex/products/part-detail/pcb_headers/0705430038">Molex Part 705430038</a>)
  DC Current per I/O Pin: 40 mA
  DC Current for 3.3V Pin: 50 mA
  PCB color: Black
  RoHS Compliant: Yes
  CE Certification: Yes (<a href="https://drive.google.com/file/d/1jnkea58oUiYslRBIA3NhDchciEu2fbQI/view?usp=share_link">Certificate of Conformity</a>)
internal-specs:
  internal part name: Farmduino Express v1.1
  rev: A
  vendor: LDO
  cost: $32.90
  notes: ---
---

## Open-source

{%
include callout.html
type="success"
title="Farmduino is open-source"
%}

|Resource|Link|
|--------|----|
|Schematics, board layout, and hardware source files|[Google Drive Folder](https://drive.google.com/drive/folders/17aEUbVUxo379uS3NhHq-Okkus4Nw7wx2?usp=sharing)
|Arduino MCU firmware source code|[GitHub](https://github.com/FarmBot/farmbot-arduino-firmware)

**Component tests**{:.internal}

|Test         |Description  |Target       |Tolerance    |
|-------------|-------------|-------------|-------------|
|Pins         |Inspect the pins for damage.|No pins should be bent|N/A
|Fuse         |Ensure the blade fuse is inserted and of the correct amperage.|7.5 Amps|N/A
|Color        |Inspect the color of the PCB.|Matte black|N/A
|Functionality|Use the factory test firmware to test motor and peripheral functions.|All functions work|N/A
|SPI comms    |Modify Trinamic TMC2130 parameters (eg: motor current)|Parameters should update.|N/A
