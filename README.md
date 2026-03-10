# Arduino-DCC-servo-decoder-
A simple low cost Arduino based DIY DCC decoder.

A simple low cost Arduino based DIY DCC decoder has been done many times before, but I couldn't find one that did exactly what I wanted, so I created my own.

Currently the code has been tested with 12 servos, but it is technically scalable up to 89 servos, although this may be limited by SRAM size.

## Features
- Two configurable positions per servo
- Per servo configurable speed
    -Currently implemented as the time (ms) between degree steps, making the speed dependent on the movement length
- Killing servos after reaching position after a globally configurable time
- Checking servos after a configurable time for a configurable duration

## Goal

The goal is to use widely available parts for the physical decoder and avoid the need for a custom PCB.

A perfboard PCB will always remain an option, although a custom PCB may be developed in the future.
