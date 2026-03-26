This is a split wireless keyboard running ZMK with custom PCB and case designs

![PXL_20260326_034125895](https://github.com/user-attachments/assets/d54e8bab-0baf-4eab-ab14-6d032593541b)

## Tools/software Used:
- [Ergogen](https://github.com/ergogen/ergogen) for layout and PCB generation as well as DXF files for case design
- [KiCad](https://www.kicad.org/) to wire the PCB
- [FreeCAD](https://www.freecad.org/) for case and plate design
- [ZMK](https://zmk.dev/) for the wireless firmware
- A slightly modified version of [this](https://github.com/AYM1607/zmk-driver-azoteq-iqs5xx) trackpad firmware by AYM1607

A big thank you to all the awesome people who have contributed to these projects, all of this being free and open source is truly amazing!

Its main features are:
- Bluetooth low energy connectivity
- Azotec TPS43 trackpad mounted on the right side
- 5000mAh batteries in each side
- Dual rotary encoders
- Nice! View display
- Low profile with choc v1 switches

## PCB Renders
| Side | Top | Bottom |
| :--- | :---: | :---: |
| **Left Half** | ![Left Top](docs/images/left_half-3D_top.png) | ![Left Bottom](docs/images/left_half-3D_bottom.png) |
| **Right Half** | ![Right Top](docs/images/right_half-3D_top.png) | ![Right Bottom](docs/images/right_half-3D_bottom.png) |

You can find the source FCStd file for the case and plates [here](mechanical/Cantanker_Case_and_Plates.FCStd) and print-ready exports below:
| Part | STLs | STEPs |
| :--- | :--- | :--- |
| **Left Case** | [Download](mechanical/exports/Cantanker_Left_Case.stl) | [Download](mechanical/exports/Cantanker_Left_Case.step) |
| **Right Case** | [Download](mechanical/exports/Cantanker_Right_Case.stl) | [Download](mechanical/exports/Cantanker_Right_Case.step) |
| **Left Plate** | [Download](mechanical/exports/Cantanker_Left_Plate.stl) | [Download](mechanical/exports/Cantanker_Left_Plate.step) |
| **Right Plate** | [Download](mechanical/exports/Cantanker_Right_Plate.stl) | [Download](mechanical/exports/Cantanker_Right_Plate.step) |
