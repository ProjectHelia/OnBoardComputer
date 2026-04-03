# On Board Computer
This repository contains all the code that will be ran on the on board computer system. The OBC is made up on 6 ESP32 S3 microcontrollers, one for each subsystem.

Within the `src/` there is a folder for each subsystem:
- `OBDH-TTC`: 
- `EPS`:
- `Instrumentation`
- `Mechanisms`
- `Photonics`
- `Thermals`

Each ESP32 is connected by a CAN Bus for bi-directional communication. The code to send/receive data over the CAN Bus is avaliable in `libs/libcanbus` which provides the necessary abstractions for communication.

# Setting up

## Installation

## Setting up development environment

## Building 

## Deploying

# Contributing 
The repository is licenced under GPLv3 and is available to be used by any team or individual for future REXUSBEXUS, or other programme/competitions.

