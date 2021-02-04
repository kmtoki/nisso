# NISSO Keyboard

![](./img/top.jfif)

This keyboard is adjusted the Esrille new keyboard NISSE for me

## Required Parts

- Plates
  - plate/top.dxf
  - plate/bottom.dxf
- KeySwitch (MX compatible) x66
- KeyCaps x66
- Pro Micro x2
- TRRS Jack x2
- TRRS Cable
- Diodle x66
- Screws M3\*6 x16
- Spacer M3
  - 5mm x4 (bottom both side)
  - 10mm x2 (upper outer side)
  - 15mm x2 (upper inner side)
- Rubber Seal (non-slip)

## Build

I will not design a PCB
however we can make hand-wired while looking at kicad scheme file

![](./img/hand_wired.jfif)

## Firmware

use QMK firmware

```sh
cp -r qmk your_qmk_firmware/keyboards/nisso
make nisso:default:flash
```
