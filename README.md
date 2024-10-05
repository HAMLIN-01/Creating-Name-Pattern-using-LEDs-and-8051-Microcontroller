# Creating-Name-Pattern-using-LEDs-and-8051-Microcontroller
Each letter of the name is displayed one at a time through a series of LEDs.
# Description
This project involves displaying a name pattern using multiple LEDs controlled by the 8051 microcontroller. The LEDs are arranged to represent characters, and they light up in a sequence to "print" the name one letter at a time. The program is written in Embedded C and simulated using Proteus to visualize the LED pattern transitions.The project demonstrates how to manage multiple outputs on the microcontroller, using GPIO pins to control each LED in a specific pattern. It also helps in understanding how to sequence outputs to create a meaningful display.
# Features:
Microcontroller Used: 8051 (AT89C51 or equivalent)
Programming Language: Embedded C
Simulation Software: Proteus
Pattern Display: Each letter of the name is displayed one at a time through a series of LEDs.
# How it Works:
Multiple LEDs are connected to the GPIO pins of the 8051 microcontroller (e.g., P2.0 to P2.7).
The microcontroller outputs a specific pattern for each letter, turning the corresponding LEDs ON or OFF.
The letters are displayed one after another with a short delay in between, simulating the printing of a name using LEDs.
After the full name is displayed, the process repeats.
# Simulation:
The Proteus simulation allows you to visually observe the LED pattern change in real-time, ensuring the correct name sequence is displayed as intended without needing physical hardware.
