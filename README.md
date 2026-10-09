# Otto Dancing Robot

A serial-controlled biped robot built on the open-source [Otto DIY](https://www.ottodiy.com) platform. Send a single character over USB and Otto walks, turns, dances, or plays an emotion gesture with sound.

![Otto robot](images/otto.jpg)

## Features
- Walk forward / backward, turn left / right
- 10+ dance moves: moonwalk, crusaito, flapping, swing, jitter, updown and more
- 7 emotion gestures with buzzer sounds (happy, sad, victory, angry, sleeping, fretful, fail)
- Servo calibration values stored in EEPROM
- Simple control over Serial Monitor (9600 baud)

## Hardware
| Part | Qty | Pin |
|---|---|---|
| Arduino Nano | 1 | - |
| SG90 servo | 4 | D2 (left leg), D3 (right leg), D4 (left foot), D5 (right foot) |
| Passive buzzer | 1 | D13 |
| 8x8 LED matrix (MAX7219) | 1 | DIN A3, CS A2, CLK A1 |

Full list: [hardware/parts_list.md](hardware/parts_list.md)
Wiring: [hardware/circuit_diagram.png](hardware/circuit_diagram.png)
3D-printed parts: [hardware/stl_files/](hardware/stl_files/)

> Note: the LED matrix pins are defined in the code, but the matrix is not driven yet. The robot works without it.

## Getting started
1. Print the parts from `hardware/stl_files/` and assemble the robot.
2. Wire the electronics following the circuit diagram.
3. Install the Otto library (see [docs/setup_guide.md](docs/setup_guide.md)).
4. Open `src/otto_dance/otto_dance.ino` in Arduino IDE and upload.
5. Open Serial Monitor (9600 baud) and send commands. See [docs/usage.md](docs/usage.md).

## Project structure
```
src/otto_dance/otto_dance.ino   Arduino sketch
hardware/                       circuit diagram, parts list, STL files
docs/                           setup and usage guides
images/                         photos / demo
```

## Demo
Add a video link here.

## Credits
Robot design and library: [Otto DIY](https://www.ottodiy.com) (CC-BY-SA).

## License
Code: MIT. 3D models follow the original Otto DIY license (CC-BY-SA).
