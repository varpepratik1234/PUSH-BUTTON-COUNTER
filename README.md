# PUSH-BUTTON-COUNTER
COMPONY: CODETECH IT SOLUTIONS

NAME: PRATIK BHASKAR VARPE

INTERN ID: CT12NUW

DOMAIN: EMBEDDED SYSTEMS

DURATION: 8 WEEKS

START DATE: 20TH JANUARY 2025

MENTOR: NEELA SANTOSH

#DESCRIPTION

A Push Button Counter project created in Tinkercad is an educational and interactive project that introduces basic electronics and programming concepts. It involves a push button that increments a counter each time it is pressed, displaying the updated count on a seven-segment display. This project leverages the Arduino Uno microcontroller to manage the logic and control the output display. Tinkercad, a popular online platform for 3D design and electronics simulation, is used to design and test the entire circuit and code, making it accessible to beginners and hobbyists interested in learning more about electronics, microcontrollers, and coding. Project Overview: The Push Button Counter is designed to simulate a simple counting system, where a user interacts with the system by pressing a button. Each press increases a counter, and the current count is displayed on a seven-segment display. This project provides a hands-on introduction to basic concepts like input/output (I/O) devices, user interaction, and microcontroller programming. The project is ideal for beginner electronics enthusiasts, particularly those just starting to work with Arduino.

In the context of Tinkercad, users can simulate the entire project virtually, using a drag-and-drop interface to build the circuit and write the code to control it. This eliminates the need for physical components, making it an ideal platform for learning and prototyping.

Components Used: Arduino Uno: The microcontroller that processes the input from the push button and updates the count on the seven-segment display. The Arduino board is the heart of the system and is programmed to handle logic, input reading, and output control. Push Button: The input device that triggers the counter when pressed. Each press of the button increments the count. The button sends a low signal to the microcontroller when pressed and a high signal when released. Seven-Segment Display: This is an output device used to visually display the count. A seven-segment display consists of seven LEDs arranged in a figure-eight pattern that can be lit up in different combinations to represent numeric digits from 0 to 9. Resistors: These are used to limit the current flowing through the circuit, preventing damage to the components. In this project, resistors are used with the push button and the seven-segment display to ensure proper current control. Breadboard: A reusable platform used for building and testing the circuit. It provides a convenient way to connect the components together without the need for soldering. Wires: Used to connect the various components on the breadboard and to the Arduino. Circuit Design: The circuit is built using a breadboard, which allows for easy and temporary assembly. The push button is connected between one of the digital input pins of the Arduino (such as pin 2) and ground (GND). The seven-segment display is connected to the digital output pins of the Arduino. Each segment of the display (labeled a to g) is connected through a current-limiting resistor to the corresponding Arduino pin. The segments light up in different combinations to form digits.

In Tinkercad, users can design the circuit by dragging and placing components on the virtual breadboard. Connections between components are made using virtual wires, and the circuit is instantly ready for simulation. Tinkercad also provides the ability to simulate the entire system in real time, allowing users to see the effects of changes to the circuit and code as they work.

Programming: The Arduino programming environment is used to write the code that will control the system. The code consists of several key functions:

Setup Function: This function runs once when the program starts. It is used to initialize the button pin as an input and the seven-segment display pins as outputs. This prepares the system to receive inputs and provide outputs.

void setup() { pinMode(buttonPin, INPUT); // Set each segment pin of the seven-segment display as an output } Loop Function: The loop function is where the main logic happens. It constantly checks if the button is pressed using the digitalRead() function. When the button is pressed, the counter increments, and the program then updates the seven-segment display using a function to convert the count into the corresponding digit pattern.

void loop() { if (digitalRead(buttonPin) == LOW) { // Button is pressed count++; displayCount(count); // Display the count on the seven-segment display delay(200); // Debounce delay } } Debouncing: Mechanical push buttons can produce multiple signals when pressed due to the bouncing of the internal contacts. A debounce delay (usually a small pause, such as 200 milliseconds) is implemented to ensure that only one count is added for each press.

Displaying the Count: A function like displayCount() is used to convert the numeric count into the corresponding pattern for the seven-segment display. This function sends signals to each of the segments, turning the appropriate LEDs on and off to form the correct digit.

Benefits of the Project: Hands-On Learning: The project offers practical experience with hardware and programming. It teaches users how to wire up basic components and interface them with a microcontroller like the Arduino. Introduction to Arduino: The project introduces the basics of Arduino programming, including reading input, controlling output, and writing code in the Arduino environment. Simulation in Tinkercad: Tinkercad’s simulation capabilities allow users to test and debug their circuits and code in a virtual environment before moving to physical hardware. This reduces the risk of making errors and helps in understanding how the components interact. Circuit Design Skills: Users learn how to design circuits with push buttons, displays, and resistors, while also understanding how to use a breadboard for temporary setups. Debouncing and Code Optimization: Users gain experience in handling common issues like button debouncing and optimizing code for smoother operation. Conclusion: The Push Button Counter project in Tinkercad is a fun, interactive, and educational project that helps beginners grasp fundamental electronics and programming concepts. By combining an Arduino microcontroller, a push button, and a seven-segment display, users can learn how to create a basic interactive system that counts button presses. Tinkercad provides an accessible and efficient platform to simulate and refine the project, making it an ideal starting point for anyone looking to dive into the world of electronics and microcontroller programming.

OUTPUT of the task Image
