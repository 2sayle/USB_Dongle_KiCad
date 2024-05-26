# USB Dongle (KiCad project)

KiCad project to create a custom USB-C key with mass storage and a microSD connector.
Find all the KiCad schematics and layout files.
Libraries containing custom footprints and symbols are available in ./Libraries folder.

## Hardware

- USB-C connector
- USB 2.0 High Speed Interface (through ULPI)
- STM32F730R8T microcontroller
- MicroSD connector
- Power LEDs
- GPIOs for SWD (Serial Wire Debug)

## Requirements

List any software requirements or dependencies needed to use or modify the project. For a KiCad project, this would include:

- KiCad EDA Suite version 7.0.2

## Installation

```
git clone https://github.com/2sayle/USB_Dongle_KiCad.git
```

## Usage

Explain how to use the project, with examples and screenshots if applicable.

## Documentation

Links to additional documentation for the project, such as a user manual or technical specifications.
- [STM32F730 Reference Manual](https://www.st.com/resource/en/reference_manual/rm0431-stm32f72xxx-and-stm32f73xxx-advanced-armbased-32bit-mcus-stmicroelectronics.pdf)
- [STM32F730R8 Datasheet](https://www.st.com/resource/en/datasheet/stm32f730i8.pdf)
- [ULPI Interface](http://ww1.microchip.com/downloads/en/DeviceDoc/334x.pdf)
- [USB ESD Protection](https://www.st.com/resource/en/datasheet/usbulc6-2m6.pdf)

Note: Datasheets are also available by selecting a component and pressing 'D' key, in KiCad schematics editor.
