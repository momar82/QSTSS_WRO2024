# Car Project Hardware Overview

This repository details the hardware components used in our car project, highlighting the main parts and the challenges we face during development.

## Hardware Components

### 1. Raspberry Pi
The heart of our car project, the Raspberry Pi is a small, affordable computer that runs our software and manages communications between the various components.

![Raspberry Pi](https://www.raspberrypi.org/app/uploads/2020/11/Raspberry-Pi-4-Model-B.jpg)
*Source: [Raspberry Pi Foundation](https://www.raspberrypi.org/)*

### 2. USB HAT
The USB HAT provides additional connectivity options for our Raspberry Pi, allowing us to interface with multiple peripherals easily.

![USB HAT](https://www.waveshare.com/w/upload/3/3e/USB_HAT.jpg)
*Source: [Waveshare](https://www.waveshare.com/)*

### 3. Picon Zero
Picon Zero is a versatile GPIO and motor control HAT for the Raspberry Pi, which allows for easy control of motors and sensors.

![Picon Zero](https://piconzero.com/assets/img/piconzero1.jpg)
*Source: [Picon Zero](https://piconzero.com/)*

**Challenge:** The current API for Picon Zero does not support Python 3. We are working on creating an updated API that will be compatible.

### 4. LIDAR LDS-01
The LIDAR LDS-01 is used for obstacle detection and mapping, providing accurate distance measurements in real-time.

![LIDAR LDS-01](https://www.robotshop.com/media/catalog/product/cache/1/image/900x900/9df78eab33525d08d6e5fb8d27136e95/l/i/lidar-lds-01-3.png)
*Source: [RobotShop](https://www.robotshop.com/)*

**Challenge:** Currently, there is no Python API available for the LIDAR sensor. We plan to develop and share our own API soon.

## Upcoming Features
- Development of a Python 3 compatible API for Picon Zero.
- Creation of a Python API for the LIDAR LDS-01 sensor.

We appreciate your interest in our project, and we will update this repository as we make progress on our APIs. Stay tuned!
 ![image](https://github.com/user-attachments/assets/9095fbab-5405-4873-a3f0-7f27611e9bfb)
