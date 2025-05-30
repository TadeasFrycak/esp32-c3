# ESP32-C3 Nano

:warning: **Temporary warning**: This version of PCB has not been yet validated and it is actively being worked on

Compact and minimalist **ESP32-C3** breakout designed in [KiCAD](https://www.kicad.org/)

![Preview](docs/3d_preview.png "Preview")

## Features
- **Breadboard friendly**
- **Compact dimensions** - 46 x 21.5 mm
- **USB-C** connector for programming (using CDC, so no external usb-serial convertor)
- **External VIN pin** with schottky diode (so both VIN and USB power can be applied at the same time)
- **Low dropout regulator to 3V3** (LDO)
- **Reset** and **Boot** buttons on board
- **Integrated PCB antenna**
- **USB ESD protection**
- Chip: **ESP32-C3FH4**

## Interactive HTML BOM
Thanks to the awesome KiCAD [IBOM](https://github.com/openscopeproject/InteractiveHtmlBom) plugin, we can now generate this stunning BOM! You can find it in docs/ibom.html
![IBOM](docs/ibom.png "IBOM")

## Schematics
![schematics](docs/schematics.png "schematics")

## Contributors:
- **SZKANDERA Filip** (filip.szkandera@gmail.com, [@FilipSzkandera](https://github.com/FilipSzkandera/))
- **FRYČÁK Tadeáš** (info@frycak.com, [@TadeasFrycak](https://github.com/TadeasFrycak/))
