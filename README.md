# Mobile Pentium 3 Adapter
An attempt to recreate an adapter for Pentium 3 mobile processors to socket 370 (bga495 -> pga370) by reverse engineering existed one.
![alt text](https://github.com/Hluppppa/MobilePentium3Adapter/blob/main/Pictures/pcb_front.jpg)
![alt text](https://github.com/Hluppppa/MobilePentium3Adapter/blob/main/Pictures/pcb_back.jpg)

Core Voltage (VCC) table:
| VID3 | VID2 | VID1 | VID0 | VCC  |
| ----| ----| ----| ----| ---- |
| 1-2 | 1-2 | 1-2 | 1-2 | 1.30 |
| 1-2 | 1-2 | 1-2 | 2-3 | 1.35 |
| 1-2 | 1-2 | 2-3 | 1-2 | 1.40 |
| 1-2 | 1-2 | 2-3 | 2-3 | 1.45 |
| 1-2 | 2-3 | 1-2 | 1-2 | 1.50 |
| 1-2 | 2-3 | 1-2 | 2-3 | 1.55 |
| 1-2 | 2-3 | 2-3 | 1-2 | 1.60 |
| 1-2 | 2-3 | 2-3 | 2-3 | 1.65 |
| 2-3 | 1-2 | 1-2 | 1-2 | 1.70 |
| 2-3 | 1-2 | 1-2 | 2-3 | 1.75 |
| 2-3 | 1-2 | 2-3 | 1-2 | 1.80 |
| 2-3 | 1-2 | 2-3 | 2-3 | 1.85 |
| 2-3 | 2-3 | 1-2 | 1-2 | 1.90 |
| 2-3 | 2-3 | 1-2 | 2-3 | 1.95 |
| 2-3 | 2-3 | 2-3 | 1-2 | 2.00 |
| 2-3 | 2-3 | 2-3 | 2-3 | 2.05 |

ATTENTION! This adapter is still in development and has not been tested yet!

Made with KiCad 12.05.2024

Links:

https://download.intel.com/design/PentiumIII/datashts/24526408.pdf

https://datasheet.octopart.com/KC80526LY500256SL4JP-Intel-datasheet-125284.pdf
