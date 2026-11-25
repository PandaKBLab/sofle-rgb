# PandaKB Sofle RGB

The PandaKB Sofle RGB MX is a split mechanical keyboard with per-key RGB lighting. The hardware files below apply to PCB revision `SofleRGB-MX-20260424`.

## Firmware

| Setup | Firmware | Availability |
| --- | --- | --- |
| Wired split | QMK / Vial | Build for this PCB revision pending verification |
| Wireless split | ZMK | Build for this PCB revision pending verification |

Select firmware for your controller and PCB revision. Verified builds, source links and flashing instructions will be listed on the [Releases page](https://github.com/PandaKBLab/sofle-rgb/releases).

## Hardware downloads

| File | Download |
| --- | --- |
| Left MX switch plate | [DXF](hardware/sofle-rgb-mx-20260424-plate-left.dxf) |
| Right MX switch plate | [DXF](hardware/sofle-rgb-mx-20260424-plate-right.dxf) |
| Bare PCB mechanical model | [STEP](hardware/sofle-rgb-mx-20260424-pcb.step) |
| Schematic | Pending a complete schematic for this PCB revision |
| Cases | [PandaKB Sofle RGB community models](cases/) |

The STEP contains the bare board and holes. Copper traces, silkscreen and component models are omitted. The switch plate DXFs are 1:1 in millimeters. Switch and screw-hole centers were aligned to this PCB in CAD. A physical fit test is pending.

## Credits

The [Sofle RGB design](https://josefadamcik.github.io/SofleKeyboard/build_guide_rgb.html) was contributed by Dane Evans and is based on Josef Adamčík’s Sofle. The DXFs are adapted from the [upstream Sofle RGB switch plate](https://github.com/josefadamcik/SofleKeyboard/blob/fb294f7c58d0f91c379a9ef339159d4d056643e9/Sofle_RGB/Case/PCBTop/SofleKeyboardTopPlate.kicad_pcb). The left plate is mirrored from the right. See the [upstream license notice](hardware/UPSTREAM-NOTICE.txt).
