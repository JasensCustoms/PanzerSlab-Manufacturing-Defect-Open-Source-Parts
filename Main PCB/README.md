# Main PCB

The main PCB has the critical placement of the Brook PCB, USB output, AUX PCB connections, OLED connections, and LEDs. Everything is unrouted. The files are provided in Fusion Archive Format. Placement of MX sockets should be at the center of each circle on the PCB to ensure fitment.

## What's in This Folder

- `slab-main-pcb-open-source-unrouted.f3z` — unrouted board, Fusion Archive Format
- `slab-main-pcb-open-source-board-mx-routed.fbrd` — routed MX version
- `slab-main-pcb-open-source-board_2026-07-29.zip` — production files
- `slab-main-pcb-open-source-board_bom.csv` / `slab-main-pcb-open-source-board_cpl.csv` — BOM and component placement (CPL) files

## Parts List (BOM)

Complete parts list from `slab-main-pcb-open-source-board_bom.csv` (LCSC part numbers included for ordering). Use the CPL file for component placement.

| Qty | Part | Designators | Footprint | LCSC # |
|---|---|---|---|---|
| 15 | 0.1µF capacitor | C1–C4, C6–C15, C20 | 0402 | C60474 |
| 15 | SK6812MINI reverse-mount RGB LED | U$4–U$18 | C5149201 | C5149201 |
| 15 | Kailh hot-swap switch socket | SW1–SW15 | SWITCH_SOCKET | C5156480 |
| 2 | 22Ω resistor | R5, R6 | 0805 | C17561 |
| 2 | 500Ω resistor | R3, R4 | 0402 | C227124 |
| 2 | 2x4 header | U$1, U$2 | 2X4 | C225289 |
| 1 | 1x4 right-angle header | JP2 | 1X04/90 | C32713263 |
| 1 | MF-SMDF050 resettable fuse | U$19 | MF-SMDF050 | C210839 |
| 1 | JST S4B-PH-SM4-TB connector (PH, 4-pin, side-entry SMT) | X1 | S4B-PH-SM4-TB | C265102 |
| 1 | USB-302S USB connector | U$20 | USB-302S | C112455 |

### Additional Parts Not on the BOM

- **4x 1x11 2.54mm pitch low-profile machine pin sockets** — required for the Brook PCB mounting area.

## Routed MX Version

> **UNTESTED AS OF 07/29/2026** — please manufacture at your own risk. Download the files and check them yourself as a second check.

Includes a USB key so if someone ever publishes a GP2040 board in the same Gen5X footprint, you can make use of the auth key functionality.

<img width="1261" height="838" alt="Routed MX main PCB, top view" src="https://github.com/user-attachments/assets/98f38758-d453-4b2f-ac92-0368e88ba2d9" />

<img width="1267" height="842" alt="Routed MX main PCB, bottom view" src="https://github.com/user-attachments/assets/c346c8bd-ee0b-430e-bf6c-f30665dba697" />

## License & Community

Part of the [Panzer SLAB — Manufacturing Defect Compatible Parts](../README.md) repository. Provided for **personal, non-commercial use only** — full terms in [LICENSE.md](../LICENSE.md). Questions? Join the Jasen's Customs Discord: [discord.gg/UJmNMunTqa](https://discord.gg/UJmNMunTqa)
