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

### 5. Gravity: Huskylens - An Easy-to-use AI Camera | Vision Sensor


Huskylens is a compact, user-friendly AI camera and vision sensor designed for rapid prototyping and development. It simplifies AI and computer vision tasks, offering pre-trained models for object tracking, face detection, line following, and more.
Source: https://www.dfrobot.com/product-1922.html
**Challenge:** Currently, there is no Python API available for the LIDAR sensor. We plan to develop and share our own API soon.

## Upcoming Features
- Development of a Python 3 compatible API for Picon Zero.
- Creation of a Python API for the LIDAR LDS-01 sensor.

We appreciate your interest in our project, and we will update this repository as we make progress on our APIs. Stay tuned!
 ![image](https://github.com/user-attachments/assets/9095fbab-5405-4873-a3f0-7f27611e9bfb)

 ![image](https://github.com/user-attachments/assets/fecef43d-f67d-4c24-9a6a-7d49dd61dc4d)
 ![image](https://github.com/user-attachments/assets/1645e785-47bd-46e1-84ac-e7c079d3227d)
 ![image](https://github.com/user-attachments/assets/e50b4178-c828-47d0-ae18-02135736a63b)
 ![image](https://github.com/user-attachments/assets/57e810e7-7079-4f59-aac0-70ebdb65b395)
 ![image](https://github.com/user-attachments/assets/8388a151-ad38-4859-a7c5-f4be99a24dd3)
 ![image](https://github.com/user-attachments/assets/bcf5d401-ccd5-4de5-a6c5-3213aa91ea6d)
 ![image](https://github.com/user-attachments/assets/1dfeff01-31a1-45ac-bdb2-0f6f4ec813b2)





 

 

