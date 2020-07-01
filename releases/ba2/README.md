# Programming

This is a step-by-step to take the MDeck BA-2 board from assembled board to functioning unit by programming the various systems and running validations.

### Requirements

Besides the contents of this folder, you'll need the following software:

* A Windows computer (VM is fine)
* Bluetooth module programming tools - [Microchip BM64 Software & Tools (DSPKv2.1)](http://ww1.microchip.com/downloads/en/DeviceDoc/BM64%20Software%20&%20Tools%20(DSPKv2.1).zip)
* 




### Hardware Setup

* Show and introduce hardware components (programmer, bed, DUT) and go through all the connections.

The programming breaks down into 3 parts:
* Update the BT module firmware
* Program the vendor-specific BT EEPROM settings (BT name, DSP settings, etc.)
* Program the MCU with Cantaloupe Radio firmware

### Updating the BT module firmware

At the time of this writing, the BM64 devices still ship with v1.1 firmware. The MDeck BA-2 was designed to work with v2.1 firmware, which added many bugfixes and needed features. 

