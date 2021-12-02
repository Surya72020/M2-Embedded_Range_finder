# Requirements
## Introduction
Distance measurement using HC-SR04 and ATMEGA328p. In this project we are measuring distance in centimetres, with the help of HC-SR04 Ultrasound sensor, ATMEGA328p microcontroller, LCD Display.

## SWOT Analysis
-   This sensor can scan for objects upto 400cm.
-   It can be used to find distance between two objects if both objects are in direct line of sight.
-   This sensor cannot scan objects which are over 400cm away from its direct line of sight.
-   It doesn't take too much power for operating.

## 4W's and 1'H
What: This project is used to find range between the sensor and the object.
Where: Range between the sensor and the object which is in the line of sight.
When: All added and edited records are saved in a file.
Why: This project can help with navigation in foggy weather and in night where there is no light source available.
How: This project works by sending out a timed sound signal as a pulse and receiving the echo to measure the distance.

__High level requiremetns__
| ID | Description |
|----|-------------|
| HLR1 | Needs direct line of sight to work | 

__Low level requirements__
| ID | Description |
|----|-------------|
| LLR1 | Needs air as a medium |
