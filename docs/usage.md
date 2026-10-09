# Usage

Open Serial Monitor at **9600 baud** and send one character.

> The last received character is kept in memory, so Otto repeats that move in a loop until you send another command. Send `q` to stop.

## Movement
| Key | Action |
|---|---|
| w | Walk forward |
| s | Walk backward |
| a | Turn left |
| d | Turn right |
| q | Stay (home position) |

## Dance moves
| Key | Action |
|---|---|
| x | Bend |
| z | Shake legs |
| e | Moonwalk |
| r | Crusaito |
| f | Flapping |
| c | Swing |
| t | Tiptoe swing |
| g | Jitter |
| b | Updown |
| y | Ascending turn |
| h | Jump |

## Gestures (with sound)
| Key | Gesture |
|---|---|
| n | Happy |
| u | Sad |
| j | Victory |
| m | Angry |
| k | Sleeping |
| o | Fretful |
| l | Fail |

## Troubleshooting
- Robot does not respond: check baud rate (9600) and that line ending is set to "No line ending".
- Servos jitter or board resets: use a separate battery pack.
- Robot leans or walks crooked: re-run calibration (see setup guide).
