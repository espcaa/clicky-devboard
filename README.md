# Clicky devboard

## [[JOURNAL]](https://github.com/espcaa/clicky-devboard/blob/main/JOURNAL.md) - [[BOM]](https://github.com/espcaa/clicky-devboard/blob/main/kicad/production/bom.csv) - [[KICAD FILES]](https://github.com/espcaa/clicky-devboard/tree/main/kicad)

This is a devboard based on the RP2350 chip (the rp2040's successor) with three mechanical switches, with every gpio exposed on pin headers + extras like 3v3 and vbus. It was entirely designed in Kicad and everything is open source! 4 layer board that can be manufactured with normal jlcpcb tolerances.\
\
<img width="480" alt="image (4)" src="https://github.com/user-attachments/assets/88eba296-8e45-43b1-92fe-fa589f5c9f9b" />
<img width="480" alt="image (2)" src="https://github.com/user-attachments/assets/40a904b8-e985-4eeb-80eb-cc2ea861f0d2" />

## Main components

- RP2350
- 3x Cherry MX switches
- Recommended abracon crystal & inductors
- AP63203WU-7 for the 5v to 3v3 conversion
- 1x23 pin headers
- W25Q64JVSSIQ_C179171 chip for the flash (64mb)
- a usb-c connector

## Features

- clicky
- ~~might work~~ works!
- open source

## Schematic/PCB

<img width="480" alt="Screenshot 2025-08-07 at 18 11 06" src="https://github.com/user-attachments/assets/cf91e515-7c88-472a-8a18-f382df9c5390" /> \

you can download everything in the [kicad/ folder](https://github.com/espcaa/clicky-devboard/tree/main/kicad)

## Notes

- there's a resistor missing for the usb-c, so it only works in one orientation :(
