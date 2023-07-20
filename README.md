# Face Recognition Attendance System

![Python](https://img.shields.io/badge/python-3.6%2B-blue.svg)
![License](https://img.shields.io/badge/license-MIT-blue.svg)

IBM Industrial Training Project

## Description

The Face Recognition Attendance System is an automated attendance tracking tool that uses facial recognition techniques to recognize registered students and record their presence during class sessions. The system provides an easy-to-use graphical user interface (GUI) built with the tkinter library, allowing users to perform various tasks:

- Register new students with their ID and names.
- Capture facial images of registered students for training the recognition model.
- Save the trained model to recognize faces during attendance tracking.
- Automatically record attendance in a CSV file.

## Features

- Face detection using Haar Cascades.
- Facial recognition using Local Binary Patterns Histogram (LBPH) algorithm.
- Real-time attendance tracking and recording.
- Password protection to ensure secure access.

## Requirements

Make sure you have the following installed:

- Python (3.6+)
- OpenCV (cv2)
- NumPy
- Pandas
- Pillow (PIL)

You can install the required libraries using the following command:

```bash
pip install opencv-python numpy pandas pillow
