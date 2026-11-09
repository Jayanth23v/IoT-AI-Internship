
Mini Project – Smart LED Control System

Internship: IoT with AI
Week: 1
Platform: Arduino Uno and Tinkercad Circuits

1. Introduction

The Smart LED Control System is a basic Arduino-based project that demonstrates how electronic components can be controlled using a microcontroller. It uses a push button as an input device and an LED as an output device.

When the push button is pressed, the Arduino detects the input and switches ON the LED. When the button is released, the LED switches OFF.

2. Objectives

- Understand Arduino Uno programming.
- Interface a push button with a microcontroller.
- Control an LED using a digital output pin.
- Understand digital input and output operations.
- Design and test a circuit using Tinkercad.

3. Components Used

1. Arduino Uno R3
2. Breadboard
3. LED
4. Push button
5. 220Ω resistor
6. Jumper wires

4. Circuit Connections

Push Button:

- One terminal is connected to digital pin 2.
- The other terminal is connected to GND.
- INPUT_PULLUP is used in the Arduino program.

LED:

- LED anode is connected to digital pin 13 through a 220Ω resistor.
- LED cathode is connected to GND.

5. Working Principle

The Arduino continuously monitors the push button connected to digital pin 2.

With INPUT_PULLUP:

- When the button is pressed, the input becomes LOW and the LED turns ON.
- When the button is released, the input becomes HIGH and the LED turns OFF.

6. Arduino Program

int buttonPin = 2;
int ledPin = 13;

void setup() {
  pinMode(buttonPin, INPUT_PULLUP);
  pinMode(ledPin, OUTPUT);
}

void loop() {
  int buttonState = digitalRead(buttonPin);

  if (buttonState == LOW) {
    digitalWrite(ledPin, HIGH);
  } else {
    digitalWrite(ledPin, LOW);
  }
}

7. Testing and Results

The circuit was designed using Tinkercad Circuits.

During simulation:

- Pressing the push button turns the LED ON.
- Releasing the push button turns the LED OFF.

8. Applications

- Push-button operated lighting systems.
- Basic smart home lighting concepts.
- Microcontroller-based automation.
- Learning digital input and output control.

9. Future Enhancements

- Add Wi-Fi connectivity using ESP32.
- Control LEDs using a mobile application.
- Add automatic lighting using a light sensor.
- Control multiple LEDs independently.

10. Conclusion

The Smart LED Control System demonstrates how a push button can control an LED through an Arduino microcontroller. The project provides practical knowledge of circuit design, digital input/output and Arduino programming. Tinkercad simulation allows the circuit to be tested without physical hardware.
