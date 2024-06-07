# Serviliance Security Camera Project

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Components](#components)
- [Setup](#setup)
- [Usage](#usage)
- [License](#license)

## Overview
Serviliance is a security camera project built with Python for IoT applications. Utilizing a Raspberry Pi, PIR sensor, and camera module, this project detects motion, records video, and sends the footage via email.

## Features
- Motion detection using a PIR sensor
- Video recording triggered by motion detection
- Automatic email notification with video attachment

## Components
- Raspberry Pi
- PIR Sensor
- Camera Module
- Python
- SMTP for email notifications

## Setup
To get started with the Serviliance security camera project, follow these steps.

### Prerequisites
- Raspberry Pi with Raspbian OS
- Python 3 installed on Raspberry Pi
- Camera module and PIR sensor connected to Raspberry Pi

### Installation

1. **Clone the repository**
    ```sh
    https://github.com/Sagardharaglkar/SurveillanceSecurityCamera-.git
    ```

2. **Navigate to the project directory**
    ```sh
    cd serviliance
    ```

3. **Install required Python packages**
    ```sh
    pip install -r requirements.txt
    ```

4. **Configure the email settings in the Python script**
    Open the script file and update the email configuration section with your email details.

## Usage

1. **Run the Python script**
    ```sh
    python serviliance.py
    ```

2. **Functionality**
    - The PIR sensor detects motion.
    - Upon motion detection, the camera records a video.
    - The recorded video is sent to the specified email address via SMTP.
