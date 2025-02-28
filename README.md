# Combination Lock with Multiplexer (MUX) - PCB Design

## Overview
This project involves designing a **combination lock** circuit using a **multiplexer (MUX)**, implemented on a custom-designed **PCB (Printed Circuit Board)**. The lock operates by accepting a predefined sequence of inputs and unlocking only when the correct combination is entered.

This project was developed as a **semester project for a Digital Logic Design course**. The primary goal was to gain hands-on experience in **PCB design and assembly**.



## Components Used
- **Multiplexer (MUX)**: 74HC151
- **AND Gate IC**: 74LS08
- **Keypad**: 3-pin switches as input
- **LEDs & Resistors**: For status indication (Locked/Unlocked)
- **Power Supply**: 5V DC

## Circuit Design & PCB Layout
The PCB was designed using **Fusion360**, marking the first PCB design experience for this project. Key considerations included:
- Proper signal routing to avoid noise interference.
- Ground planes for stability.
- Compact design to fit in small enclosures.


## Drawbacks & Areas for Improvement
- **Fixed Combination**: The current design does not allow changing the combination.
- **Order-Dependent Code**: The lock only works with a specific order, limiting possible combinations.
- **Lack of Incorrect Entry Detection**: There is no way to detect wrong inputs.
- **Security Flaw**: The system can be easily bypassed by turning all switches to the ON position.

## Future Improvements
- Add a **mechanism to detect incorrect inputs**.
- Improve security to prevent bypassing by engaging all switches.


## Repository Contents
- **PCB Design Files**: Fusion360 project files.
- **Schematics**: Circuit diagrams in PDF format.

## License
This project is open-source and licensed under the **MIT License**.



