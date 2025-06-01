# Face Recognition

A simple Python project for real-time face detection using OpenCV and Haar Cascade classifiers.

## Features

- Detects human faces in real time from your webcam.
- Draws bounding boxes around detected faces.
- Runs locally on your machine using your camera.

## Requirements

- Python 3.6+
- [OpenCV](https://opencv.org/) (cv2)

## Installation

1. **Clone this repository:**
   ```bash
   git clone https://github.com/adarshhinsodiya/face-recognition.git
   cd face-recognition
   ```

2. **Install dependencies:**
   ```bash
   pip install opencv-python
   ```

## Usage

Run the main script to start face detection:

```bash
python face_recognition.py
```

- A window will open showing your webcam feed.
- Detected faces are highlighted with rectangles.
- Press `q` to quit.

## How It Works

- Loads the Haar Cascade classifier for frontal face detection included with OpenCV.
- Captures video frames from your default camera.
- Converts each frame to grayscale and detects faces.
- Draws a colored rectangle around each detected face.

## License

This project is licensed under the MIT License.

---

Feel free to contribute or open issues if you have suggestions or encounter any problems!
