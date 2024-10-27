# Morse Code Detection Using Eye Tracking

## Overview
This project implements a system that detects Morse code input through eye blinks using computer vision techniques. By tracking eye movements via a webcam, users can communicate using Morse code, making it a potential accessibility tool for individuals with disabilities.

## Features
- Real-time video streaming of the user's webcam.
- Detection of eye blinks to interpret Morse code (dots and dashes).
- Conversion of Morse code to text.
- Web-based interface for easy access.
- Logging of detected Morse code events.

## Technologies Used
- Python
- OpenCV
- Dlib
- Flask
- NumPy
- SciPy
- imutils

## Installation

### Prerequisites
Make sure you have Python installed on your machine. It is recommended to use a virtual environment.

1. Clone this repository:
   ```bash
   git clone https://github.com/KevinJugal/MorseCode-EyeBlinks.git
   cd morse-code-eye-tracking
2. Install the required packages:
   ```bash
   pip install -r requirements.txt

###Code Structure

morse_converter.py: Contains the function for converting Morse code to text.
morse_eyes.py: Implements the Detectmorse class for processing video frames and detecting Morse code.
morse_flask.py: Sets up the Flask web server and handles video streaming.
morse_log.py: Handles logging of Morse code events.
