# 148-jeepbot-team-01
Jeepbot
# Jeepbot

Jeepbot is an embedded robotics project focused on onboard perception, sensing, and future autonomy integration using a Raspberry Pi and OAK-D cameras.

## Current Progress

So far, this project includes:
- Raspberry Pi environment setup
- Python virtual environment for DepthAI
- OAK-D camera connectivity testing
- Basic RGB camera feed validation
- Initial depth/stereo experimentation
- Planning for multi-camera integration

## Hardware

- Raspberry Pi
- Luxonis OAK-D / OAK-D Pro cameras
- USB connection to Pi
- Optional future motor control / drive system hardware

## Software Stack

- Python 3
- DepthAI
- OpenCV
- Raspberry Pi OS
- Virtual environment (`venv`)

## System Schematic

![Jeepbot System Schematic](docs/system_schematic.jpeg)

## Repository Structure

```text
jeepbot/
├── README.md
├── requirements.txt
├── setup/
├── docs/
├── src/
├── scripts/
├── data/
├── images/
└── archive/
