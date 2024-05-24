# Chip-8 Emulator

## About
This is a simple implementation of the Chip-8 Emulator written using `C++` and `SDL`. This was written by following along `Austin Morlan's` blog which you can find [here](https://austinmorlan.com/posts/chip8_emulator/).

## Setup Instructions

1. Clone the project
2. Run the following command
```
g++ main.cpp chip8.cpp platform.cpp -o chip8 -I ./include -L ./lib -l SDL2 -l glad
```
3. Run `./chip8` command and you are ready to begin.

## Future Scope

- Implement sound
- Implement a debugger interface
