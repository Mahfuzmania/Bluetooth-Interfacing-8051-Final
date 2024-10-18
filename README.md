# Bluetooth Interfacing with 8051 Microcontroller

This project enables wireless control of components like LEDs, relays, and buzzers via the HC-05 Bluetooth module connected to an 8051 microcontroller. Commands sent from a smartphone control various operations such as countdowns, Morse code transmission, and encryption.

## Features
- **Countdown Timer**: `C` command starts a countdown with a buzzer alert.
- **LED Relay Control**: Use `L` to toggle the LED relay ON/OFF.
- **Morse Code Mode**: Transmit Morse code for A and B using the `M` command.
- **Encryption Mode**: `D` triggers simple encryption by shifting ASCII values.
- **Reset System**: Send `0` to reset the system to its default state.

## Components
- 8051 Microcontroller
- HC-05 Bluetooth Module
- LCD Display
- Relay, Buzzer, and LED Matrix

## Project Files
- **final_over.asm**: Assembly source code for the 8051.
- **final_over.hex**: Compiled file for programming the microcontroller.
- **final_over.lst**: Debugging list file.
- **final_over.dev**: Development project file.

## Instructions
1. Flash the `final_over.hex` file to the 8051 microcontroller.
2. Connect to the HC-05 Bluetooth module via a smartphone.
3. Use a Bluetooth terminal app to send commands and control the system.
