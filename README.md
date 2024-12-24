# Face Recognition System

## Overview
This project is a Python-based face recognition system that utilizes the `face_recognition` and `opencv-python` (cv2) libraries to detect and recognize faces from a webcam stream and static images. It also includes functionality for attendance marking by recognizing faces and logging them with timestamps in a CSV file.

## Features
- Real-time face recognition from webcam feed.
- Attendance marking by logging recognized faces with date and time.
- Face comparison between static images for validation.

## Tech Stack
- **Python:** Core programming language.
- **face_recognition:** Library for facial recognition tasks.
- **OpenCV (cv2):** Library for image processing and computer vision.
- **NumPy:** Essential for data handling.

## Prerequisites
Before you begin, ensure you have Python installed along with pip (Python package installer). This project also requires a webcam connected to your computer.

## Installation
To get this project running on your local machine, follow these steps:
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/face-recognition-system.git
2. Navigate to the project directory:
   ```bash
   cd face-recognition-system
3. Install required Python libraries:
   ```bash
   pip install opencv-python face_recognition numpy

## Setup
Ensure all images used for recognition are stored in the `ImagesAttendance` directory with clear naming, as names are used for attendance marking.

## Usage
Run the main script to start the face recognition and attendance system:
```bash
python face_recognition_system.py
```
For static image comparision, use the script configured to compare specific images:
```bash
python compare_faces.py
```
Adjust the paths and names inside the script as necessary to reflect your image sources and targets.

## License
This project is distributed under the MIT License. See the `LICENSE` file for more information.
