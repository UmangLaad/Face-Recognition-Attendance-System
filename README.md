# Face-Recognition-Attendance-System
IBM_Industrial Training

Face Recognition Based Attendance System

This project implements a Face Recognition Based Attendance System using Python and OpenCV. The system allows users to register students, capture their facial images, and track their attendance during class sessions.
Table of Contents

    Description
    Features
    Requirements
    Installation
    Usage
    Contributing
    License
    Contact

Description

The Face Recognition Based Attendance System is an automated attendance tracking tool that uses facial recognition techniques to recognize registered students and record their presence during class. The system provides an easy-to-use graphical user interface (GUI) built with tkinter library, allowing users to perform various tasks:

    Register new students with their ID and names.
    Capture facial images of registered students for training the recognition model.
    Save the trained model to recognize faces during attendance tracking.
    Automatically record attendance in a CSV file.

Features

    Face detection using Haar Cascades.
    Facial recognition using Local Binary Patterns Histogram (LBPH) algorithm.
    Real-time attendance tracking and recording.
    Password protection to ensure secure access.

Requirements

Make sure you have the following installed:

    Python (3.6+)
    OpenCV (cv2)
    NumPy
    Pandas
    Pillow (PIL)

You can install the required libraries using the following command:

bash

pip install opencv-python numpy pandas pillow

Installation

    Clone this repository to your local machine:

bash

git clone https://github.com/YourUsername/FaceRecognitionAttendanceSystem.git
cd FaceRecognitionAttendanceSystem

    Install the required dependencies (see Requirements).

    Run the main script to launch the Face Recognition Based Attendance System:

bash

python attendance_system.py

Usage

    Upon running the script, the graphical user interface will be displayed.
    Use the "Register New Student" section to register new students by entering their ID and names.
    Use the "Take Images" section to capture facial images of registered students for training the recognition model.
    After capturing images for all registered students, click on "Save Profile" to train the recognition model and save it.
    Use the "Take Attendance" button to start real-time attendance tracking using the trained model. The system will automatically detect registered students and record their attendance in a CSV file.
    The attendance records can be viewed in the table provided on the GUI.

Contributing

Contributions to this project are welcome! If you find any bugs or have ideas for improvements, please open an issue or create a pull request. For major changes, please discuss the proposed changes with the repository owners.
