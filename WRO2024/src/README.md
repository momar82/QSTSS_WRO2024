# Autonomous RC Car for WRO Competition

This repository contains the Python code used to control our autonomous RC car, designed for participation in the **National World Robot Olympiad (WRO)**. The RC car uses a **LiDAR sensor** for environmental scanning and the **Picon Zero motor controller** for handling movement and steering.

## Table of Contents

- [Overview](#overview)
- [Hardware Requirements](#hardware-requirements)
- [Software Requirements](#software-requirements)
- [Installation](#installation)
- [How It Works](#how-it-works)
- [Code Explanation](#code-explanation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## Overview

The project leverages a **360-degree LiDAR sensor** to autonomously navigate the RC car, adjusting speed and direction based on real-time distance measurements. The system is designed to detect obstacles and avoid collisions, making it suitable for autonomous navigation challenges.

## Hardware Requirements

- RC Car chassis
- **LD06** LiDAR sensor (or compatible with `lds_driver`)
- **Picon Zero** motor controller
- Raspberry Pi (or compatible microcontroller)
- USB Cable for LiDAR connection
- Battery pack for power supply
- Jumper wires for connections

## Software Requirements

- Python 3.x
- `lds-driver` (Python library for LiDAR control)
- `piconzero` (Python library for Picon Zero control)

### Python Library Installation

Make sure to install the necessary Python libraries:

```bash
pip install lds-driver piconzero
