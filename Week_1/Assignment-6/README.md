# Assignment 6 – Push Button Interfacing with Arduino

This assignment demonstrates how to interface a push button with Arduino Uno and control an LED based on button input.

## Components Used
1. Arduino Uno R3
2. Breadboard
3. Push button
4. LED
5. 220Ω resistor
6. Jumper wires

## Circuit Connections

### Push Button
- One terminal is connected to digital pin 2.
- The other terminal is connected to GND.
- INPUT_PULLUP is used in the Arduino program.

### LED
- LED anode is connected to digital pin 13 through a 220Ω resistor.
- LED cathode is connected to GND.

## Working Principle

The Arduino reads the push button state using digitalRead().

- When the button is pressed, the input becomes LOW and the LED turns ON.
- When the button is released, the input becomes HIGH and the LED turns OFF.

## Result

The push button successfully controls the LED in the Tinkercad simulation.

## Tools Used
- Arduino Uno
- Tinkercad Circuits
- Arduino C/C++
