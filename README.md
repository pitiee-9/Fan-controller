
# Fan Controller PCB (KiCad Project)
<img width="1044" height="661" alt="image" src="https://github.com/user-attachments/assets/1defd923-d990-4ba0-adde-3b742d2a1d7d" />


## Overview

This project is a simple fan controller designed using KiCad as a beginner in PCB design. The goal of this circuit is to control the speed of a DC fan by adjusting the voltage supplied to it. It also helped me understand how different electronic components are connected and how they work together on a printed circuit board.

## How It Works

The circuit regulates the fan speed by controlling the electrical signal that passes through the main integrated circuit (IC). By adjusting the input (through a control component), the output voltage changes, which directly affects how fast the fan spins. Supporting components like resistors, capacitors, and diodes help stabilize, protect, and shape the signal.

## Components and Their Roles

* **_Integrated Circuit (IC)_**
  This is the brain of the circuit. It controls how the signal flows and determines the fan speed based on the input it receives.

* **_Resistors_**
  These limit and control the flow of current in different parts of the circuit. They ensure components receive safe levels of current and help set operating conditions for the IC.

* **_Capacitors_ (Electrolytic and Ceramic)**
  Capacitors store and release electrical energy. In this circuit, they help smooth voltage fluctuations and reduce noise, making the fan run more steadily.

* **_Diode_**
  The diode protects the circuit by allowing current to flow in only one direction. It helps prevent damage from reverse polarity or voltage spikes.

* **_Transistor_**
  Acts as a switch or amplifier. It helps control the amount of current delivered to the fan, especially when higher power is needed.

* **_LED_ (Light Emitting Diode)**
  This is a simple indicator that shows when the circuit is powered and operating.

* **_Connectors / Pins_**
  These are used to connect the power source and the fan to the PCB.

## PCB Design Learning Points

As a beginner, this project helped me learn:

* How to place components logically on a PCB
* How to route tracks (connections) between components
* The importance of proper spacing and clean layout
* Basic circuit design and how real components interact

## Conclusion

This fan controller is a simple but practical project that demonstrates the basics of electronics and PCB design. It is a great starting point for anyone learning KiCad and wanting to build functional hardware projects.
