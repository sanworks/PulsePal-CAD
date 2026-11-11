# Pulse Pal design files

These are the hardware design files of Pulse Pal, an open source pulse train generator maintained
by [Sanworks LLC](https://sanworks.io): circuit boards, enclosures and a bill of materials. A Pulse
Pal plays precisely timed voltage pulse trains on four analog output channels, started by software
or by two trigger inputs.

Pulse Pal has two other repositories:

- [PulsePal](https://github.com/sanworks/PulsePal): the Python, MATLAB and C++ interfaces, the
  GUIs, the MATLAB firmware loader and USB drivers. Start there to use a Pulse Pal.
- [PulsePal-Firmware](https://github.com/sanworks/PulsePal-Firmware): the firmware, for Pulse Pal 2
  (Arduino Due) and Pulse Pal 3 (Teensy 4.1), with versioned releases.

## Contents

| Path | Contents |
|---|---|
| `/PCB/v3_0/` | Pulse Pal 3: board 3.0.1 |
| `/PCB/r2_1/` | Pulse Pal 2: PulsePalSMT Rev 0.8 |
| `/PCB/r2_0/` | Pulse Pal 2: PulsePalSMT Rev 0.5 |
| `/PCB/r1_1/` | Pulse Pal 1: Rev 1.0 and Rev 1.1, and a drawing of the essential I/O circuit |
| `/Enclosure/Pulse Pal 3/` | Fusion 360 models, STL files for 3D printing, laser cut panels (SVG), and manufacturing and assembly notes (`Readme.txt`) |
| `/Enclosure/Pulse Pal 2/` | Laser cut enclosure (CorelDRAW) |
| `/Enclosure/Pulse Pal 1_X/` | Laser cut enclosures for Pulse Pal 1.0 and 1.1 (CorelDRAW), and a screen support (SketchUp, STL) |
| `PulsePal r3_0_1 BOM.xlsx` | Bill of materials for Pulse Pal 3 (board 3.0.1) |

Each circuit board folder holds the schematic (`.sch`) and the board layout (`.brd`), which open in
Eagle, and in `GERBER/` the CAM files for manufacturing the board. The `Readme.txt` files in
`/PCB/r1_1/` and `/PCB/r2_0/` name the board house those files were prepared for.

## License

Pulse Pal is an open source instrument, released under the GNU General Public License version 3
(see [LICENSE](LICENSE)). You can build and modify the device for your own use and even release
derivative works commercially, but all derivative versions of the software and hardware must
remain open source under the GNU General Public License v3.

Preassembled Pulse Pals are available at https://sanworks.io. Please contact us with any
questions, bugs and general feedback: admin@sanworks.io
