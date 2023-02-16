# Calculator-PCB

I decided to design a calculator pcb with some simple components that i had. I chose an atmega328p microcontroller that can achieve the necessary tasks because it contains   enough  digital pins for the button matrix and also contains i2c communication for the display.

The matrix contains 6 rows and 4 columns, 10 buttons for numbers, 5 for arithmetic operations, 4 for trigonometric operations, and one each for exponentials,  integrals, derivatives, equation resolutions and matrix operations.

It also contains two buttons, one to reset the calculator and the second to erase the last number written. The PCB has a power supply circuit to decrease the input voltage thanks to a lm7805 regulator.
