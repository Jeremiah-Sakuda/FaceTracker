# Face Tracker

A simple face tracker application using Python and OpenCV. This program detects faces in real-time from a webcam feed and displays bounding boxes around detected faces.

## Features
- Real-time face detection using OpenCV's Haar Cascade classifier
- Draws bounding boxes around detected faces on the video feed

## Requirements
- Python 3.x
- OpenCV library

## Installation

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/yourusername/FaceTracker.git
   ```

2. **Navigate to the Project Directory:**
   ```bash
   cd FaceTracker
   ```

3. **Install Required Libraries:**
   ```bash
   pip install opencv-python
   ```

## Usage

1. Run the face tracker program:
   ```bash
   python face_tracker.py
   ```

2. A new window will open showing the webcam feed with bounding boxes around detected faces.

3. To exit the program, press `q` on your keyboard.

## How It Works

- The program uses OpenCV's **Haar Cascade** classifier, a pre-trained model for face detection.
- Each frame from the webcam is converted to grayscale and analyzed for faces.
- Detected faces are highlighted with bounding boxes.

## Troubleshooting

- If the webcam feed doesn’t open, ensure you have granted camera access to Python.
- For issues with OpenCV, ensure it is correctly installed (`pip install opencv-python`) and check compatibility with your Python version.


