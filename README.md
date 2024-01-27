# Smart Surveillance System

## Overview
This project aims to develop a smart surveillance system that leverages advanced computer vision and machine learning techniques for real-time monitoring and analysis. The system is capable of age and gender detection, which can be vital for various applications such as security, demographic analysis, and targeted advertising.

## Models Used
The system utilizes several pre-trained models from OpenCV and Caffe for accurate detection and classification:

- **Face Detection Model**: 
  - Proto File: `opencv_face_detector.pbtxt`
  - Model File: `opencv_face_detector_uint8.pb`

- **Age Detection Model**: 
  - Proto File: `age_deploy.prototxt`
  - Model File: `age_net.caffemodel`

- **Gender Detection Model**:
  - Proto File: `gender_deploy.prototxt`
  - Model File: `gender_net.caffemodel`

These models are integral for the system's ability to detect and analyze faces in real-time, providing age and gender estimations.

## Features
- Real-time video surveillance
- Age and gender detection
- Customizable alert system
- Scalable architecture for various environments

## Hardware Requirements

To set up and use the smart surveillance system, the following hardware components are required:

- **Raspberry Pi**: This project is designed to run on a Raspberry Pi. Any model with sufficient processing power and connectivity options (such as Raspberry Pi 3 or 4) should be suitable.

- **Camera Module**: A compatible camera module is required for capturing video footage. This could be the official Raspberry Pi Camera Module or any compatible third-party camera module.

Ensure that your Raspberry Pi is set up with the necessary software (OS, drivers) to interface with the camera module.

## Installation
Provide instructions on how to set up and install your smart surveillance system. Include steps for cloning the repository, installing dependencies, and any necessary configuration.

```bash
git clone https://github.com/asma-hachaichi/Smart-Surveillance-System.git
cd Smart-Surveillance-System
pip install -r requirements.txt
```

## Dependencies
1. **gpiozero**: This library is used for interfacing with the GPIO (General Purpose Input/Output) pins on Raspberry Pi devices. It's essential if your project involves physical hardware interactions on a Raspberry Pi.
2. 
3. **opencv-python (cv2)**: OpenCV is a robust library for computer vision tasks. Since you're using cv2 in your project, this library is a necessary dependency for image processing and video analysis functionalities.

## Credits
This project is inspired by and utilizes substantial portions of code from the work of Mahesh Sawant. We acknowledge his significant contributions to the field of computer vision and express our gratitude for making his work accessible, which has greatly facilitated the development of this smart surveillance system.



