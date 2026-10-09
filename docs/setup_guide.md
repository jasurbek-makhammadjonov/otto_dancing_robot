# Setup Guide

## 1. Software
- Install [Arduino IDE](https://www.arduino.cc/en/software).
- Install the Otto library:
  - Download from the OttoDIY GitHub (`OttoDIYLib`) as ZIP.
  - Arduino IDE -> Sketch -> Include Library -> Add .ZIP Library.
- The sketch also uses `Wire`, `SoftwareSerial` and `EEPROM` (built into Arduino IDE).

## 2. Upload
1. Connect Arduino Nano via USB.
2. Tools -> Board -> Arduino Nano; choose the correct Processor (try "ATmega328P (Old Bootloader)" if upload fails).
3. Select the COM port and click Upload.

## 3. Servo calibration
Calibration offsets are read from EEPROM addresses 0-3 (YL, YR, RL, RR). Before attaching the servo horns, send `q` so all servos go to the home position (90 degrees), then attach the legs and feet straight.

## 4. Power
Do not power four servos from USB alone if they jitter or the board resets; use a battery pack.
