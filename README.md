# Experimenting with the 28BYJ-48 Stepper Motor

This project demonstrates how to control a **28BYJ-48 stepper motor** using an **Arduino** and a **ULN2003 driver board**. The motor is driven using the built-in **Stepper.h** library and accepts Serial input in degrees to perform precise rotations.

## Components
- Arduino Uno (or compatible)
- 28BYJ-48 stepper motor
- ULN2003 driver board
- Jumper wires
- USB cable

## Features
- Enter rotation angle (degrees) via Serial Monitor (e.g. `90` or `-180`)
- Degrees are converted to motor steps automatically
- Supports clockwise and counterclockwise motion

## Usage
1. Open `Stepper_Motor_Experiment.ino` in the Arduino IDE.
2. Upload to the Arduino.
3. Open the Serial Monitor (baud rate 9600).
4. Type an angle in degrees and press Enter.
   - Example inputs: `90` → rotate 90° clockwise
   - `-180` → rotate 180° counterclockwise

## Files
- `Stepper_Motor_Experiment.ino` — Arduino sketch using `Stepper.h`
- `README.md` — this file

## Notes
- The `Stepper.h` library is included with the Arduino IDE.
- Adjust pin numbers in the sketch if you wire to different Arduino pins.
- For smoother motion or higher torque, consider using a dedicated stepper driver and a proper power supply.

## License
Feel free to reuse and modify. No license specified — add one if you want to set reuse terms.
