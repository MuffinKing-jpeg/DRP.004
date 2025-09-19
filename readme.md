# DRP.004

Quack with the **new level**!
![top image](/MEDIA/DRP.004_top.png)
![bottom image](/MEDIA/DRP.004_bot.png)

## Docs

- [Interactive BOM](./bom/ibom.html)
- [Schematics](./PLOTS/DRP.004.pdf)
- [Production files](./production/)

## Changes in v3

- Completely new power design
  - 1.8v for MCU + LDR
  - ~5.5v for servo only
- Interface moved to one side.
- MOAR SILK!
- ENIG

## Issues to overcome

- [x] Replace R16 from 10k to 3.3k
- [x] ~~Replace Q2 and Q1(?) to IRLML6402~~ Refactored power supply
- [x] Reroute EN_LOAD_BAT to PA8
- [x] Reroute EN_LDR to PA11
- [x] Reroute ADC_LDR to PA12
- [x] Fix typos
