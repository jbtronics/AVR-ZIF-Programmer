# AVR-ZIF-Programmer Bootloader

based on https://github.com/baerwolf/USBaspLoader
Licensed under GPLv2.

## Instructions
### Precompiled hex
You can flash the file "mega8_12MHz.hex" to your master MCU (Mega 8) and set the following fuses: `lfuse:0xbf` and `hfuse:0xd0`
### Build from source
Go into `firmware/` folder, open a console and type `make flash` to build and flash the bootloader, then type `make fuses` to burn the needed fuses.
