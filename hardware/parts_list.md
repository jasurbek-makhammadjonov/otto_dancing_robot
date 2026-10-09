# Parts List

## Electronics
| # | Part | Qty | Notes |
|---|---|---|---|
| 1 | Arduino Nano | 1 | With pins soldered; Nano I/O shield makes wiring easier |
| 2 | SG90 micro servo | 4 | 2 for legs, 2 for feet |
| 3 | Passive buzzer | 1 | Pin D13 |
| 4 | 8x8 LED matrix (MAX7219) | 1 | Optional, defined on A3/A2/A1 |
| 5 | Mini-USB cable | 1 | Upload code and control via Serial |
| 6 | Battery pack | 1 | Servos need their own supply (e.g. 4xAA or Li-ion with regulator) |
| 7 | Jumper wires | - | Female-female / male-female |

## Mechanical
| # | Part | Qty | Notes |
|---|---|---|---|
| 1 | 3D-printed body, head, legs, feet | 1 set | See `stl_files/` |
| 2 | Small screws | ~8 | For servos and horns |

## Pin map
| Function | Pin |
|---|---|
| Left leg servo | D2 |
| Right leg servo | D3 |
| Left foot servo | D4 |
| Right foot servo | D5 |
| Buzzer | D13 |
| Matrix DIN / CS / CLK | A3 / A2 / A1 |

## Source of STL files
Original Otto DIY files: https://hackaday.io/project/11776-otto-diy
