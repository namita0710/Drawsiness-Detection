# Drowsiness Detection App

This is a Python-based application designed to detect drowsiness in real-time using facial landmarks and computer vision. The app alerts users when signs of drowsiness are detected, improving safety and preventing accidents.

## Features
- Real-time video processing for drowsiness detection.
- Audio alerts for drowsy states.
- Easy to use with a user-friendly interface.
- Lightweight and efficient for desktop or embedded devices.

## Technologies Used
- **Python**: Core programming language.
- **OpenCV**: For video stream processing.
- **dlib**: For facial landmark detection.
- **winsound** (optional): For generating audio alerts.

## How It Works
1. **Facial Landmark Detection**: The app identifies the user's face and tracks eye and mouth movements using dlib's pre-trained models.
2. **Eye Aspect Ratio (EAR)**: Calculates the eye aspect ratio to monitor blinking and prolonged eye closure.
3. **Alert System**: Triggers an alert if the EAR remains below a threshold for a set duration, indicating drowsiness.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/namita0710/drowsiness-detection.git
   cd drowsiness-detection
