# Clap Switch Circuit

## Overview

This project simulates a **clap controlled toggle switch** using a potentiometer in Arduino.
Since real sound input is not available in simulation environments like Tinkercad, the potentiometer is used to mimic a **clap signal (sudden voltage spike)**.
Each time the input exceeds a defined threshold, the LED **toggles its state (ON ↔ OFF)** — similar to how a clap switch works.

## Objective

* Simulate clap detection using analog input
* Implement toggle logic using a threshold
* Understand signal spikes and event detection


## Components Used

* Arduino Uno
* Potentiometer
* LED
* 220Ω Resistor
* Breadboard & jumper wires

## Behavior

| Input Condition | Output      |

| Value ≤ 500     | No change   |

| Value > 500     | LED toggles |

## Limitations

* Does not use real sound input
* Requires manual adjustment of potentiometer

## Future Improvements

* Replace potentiometer with **sound sensor module (KY-038 / KY-037)**
* Implement **double clap detection**

## Simulation

This project can be built and tested using **Tinkercad Circuits**.
