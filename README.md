# AVR128DA48 ADC Differential Example

This repository provides an Atmel Studio solution with a bare metal code example for ADC differential mode. 

In the main loop, the program reads the differential value between the AIN4 analog channel (PD4 pin) and AIN3 analog channel (PD3 pin).

## Configurations

PD4 - Configured as AIN4

PD3 - Configured as AIN3

ADC0 - Configured in Free Run Mode to accumulate 64 samples

VREF - Reference voltage for ADC0 set to 2.048V

## Required Tools 

Software: ATMEL Studio and AVR-DA Device Packs

Hardware: AVR128DA48 Curiosity Nano

## Compatibility
The source code is compatible with the following devices: AVR128DA28, AVR128DA32, AVR128DA48, and AVR128DA64.
