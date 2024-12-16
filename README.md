# RealTimeHandGestureRecognition

A real-time hand gesture recognition system using MediaPipe and OpenCV. This project maps hand gestures to specific actions, such as moving forward, backward, left, right, and jumping.

## Features
- Detects hand gestures in real-time.
- Actions mapped to the relative positions of wrist and index finger.
- Uses MediaPipe for hand landmark detection and OpenCV for video capture.

## Requirements
- Python 3.x
- `opencv-python`
- `mediapipe`
- `numpy`

To install dependencies:
pip install opencv-python mediapipe numpy



## Usage

1) Clone the repository:
git clone https://github.com/yourusername/HandGestureControl.git
cd HandGestureControl



3) Run the script:
python hand_gesture_control.py



4) Perform gestures:
- Forward: Point index finger straight.
- Backward: Point index finger down.
- Left: Point index finger left.
- Right: Point index finger right.
- Jump: Point index finger up.

4) Press 'q' to exit.
