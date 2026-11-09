# Assignment 7 – Reading Sensor Values Using Arduino

This assignment demonstrates how to interface a TMP36 temperature sensor with Arduino Uno and read temperature values using the Arduino IDE Serial Monitor.

## Components Used
1. Arduino Uno R3
2. TMP36 Temperature Sensor
3. Breadboard
4. Jumper wires

## Circuit Connections

With the flat face of the TMP36 sensor facing you and its pins pointing downward:

- Left pin – 5V
- Middle pin – Analog pin A0
- Right pin – GND

## Working Principle

The TMP36 sensor produces an analog voltage corresponding to the surrounding temperature.

Arduino reads the sensor output using analogRead() and converts the analog value into voltage. The temperature is then calculated in degrees Celsius.

The readings are displayed in the Serial Monitor at a baud rate of 9600.

## Result

Temperature readings were obtained from the TMP36 sensor and displayed in the Tinkercad Serial Monitor.

## Tools Used
- Arduino Uno
- TMP36 Temperature Sensor
- Tinkercad Circuits
- Arduino IDE / Serial Monitor
