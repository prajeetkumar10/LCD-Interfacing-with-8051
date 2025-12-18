<h1 align="center">Hexadecimal Counter using 8051 and LCD </h1>
This experiment implements a hexadecimal counter using an 8051 microcontroller and a 16x2 LCD. The counter counts from 0 to F on the LCD and updates the display continuously.

## ASCII Values of the Hexadecimal Values

| Hex  | ASCII Character | ASCII Hex |
| ---- | --------------- | --------- |
| 0x0  | '0'             | 0x30      |
| 0x1  | '1'             | 0x31      |
| 0x2  | '2'             | 0x32      |
| 0x3  | '3'             | 0x33      |
| 0x4  | '4'             | 0x34      |
| 0x5  | '5'             | 0x35      |
| 0x6  | '6'             | 0x36      |
| 0x7  | '7'             | 0x37      |
| 0x8  | '8'             | 0x38      |
| 0x9  | '9'             | 0x39      |
| 0xA  | ':'             | 0x3A      |
| 0xB  | ';'             | 0x3B      |
| 0xC  | '<'             | 0x3C      |
| 0xD  | '='             | 0x3D      |
| 0xE  | '>'             | 0x3E      |
| 0xF  | '?'             | 0x3F      |
| 0x10 | 'A'             | 0x41      |
| 0x11 | 'B'             | 0x42      |
| 0x12 | 'C'             | 0x43      |
| 0x13 | 'D'             | 0x44      |
| 0x14 | 'E'             | 0x45      |
| 0x15 | 'F'             | 0x46      |


Here the counter starts to count from 0x30 to 0x39 beacuse microcontrollers use ASCII values. after 0x39, from 0x3a to 0x3f are occupied by punctuation marks and special characters so, we jump from 0x39 to 0x41



