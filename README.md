# Hand Gesture Controlled Volume and Brightness Control using Python

# overview of the project

This project demonstrates a hand gesture recognition system using a webcam to control your system's volume and screen brightness in real time. It uses MediaPipe to detect hand landmarks and maps specific finger distances to volume and brightness levels. A right-hand gesture controls the system volume, while a left-hand gesture controls screen brightness.

# Features

Real-time hand tracking using a webcam

Gesture-based volume control using thumb–index finger distance

Gesture-based screen brightness control using the other hand

Smooth interpolation for a responsive experience

Works for both left and right hands simultaneously

# Technologies Used

Python

MediaPipe – for real-time hand tracking

OpenCV – for capturing video and visual feedback

NumPy – for numerical operations

screen-brightness-control – to adjust screen brightness

pycaw – for system volume control on Windows

Comtypes – for Windows audio device interaction

# Installation

Make sure you have Python installed. Then, install the required libraries:

!pip install opencv-python mediapipe screen-brightness-control pycaw comtypes numpy

# How to Run

Simply run the Python script:

python your_script_name.py
Ensure your webcam is enabled, and grant necessary permissions for screen/volume access.
