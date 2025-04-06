# Face Detection using OpenCV


## Project Description

This Python script demonstrates real-time face detection using OpenCV's Haar Cascade classifier. It captures video from your webcam and draws rectangles around detected faces.

## Features

- Real-time face detection from webcam feed
- Uses OpenCV's pre-trained Haar Cascade classifier
- Simple and efficient implementation
- Exit by pressing the SPACE key

## Requirements

- Python 3.6+
- OpenCV (cv2) library
- Webcam

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/kpoornasai121/Face_Recognition_System.git
   cd Face_Recognition_System
   ```

2. Install the required package:
   ```bash
   pip install opencv-python
   ```

## Usage

Run the face detection script:
```bash
python Face_Recognition_Systemn.py
```

- Press the **SPACE** key to exit the program
- Faces will be highlighted with green rectangles

## Code Structure

- `Face_Recognition_System.py`: Main script containing the face detection implementation
- `haarcascade_frontalface_default.xml`: Pre-trained Haar Cascade classifier (automatically included with OpenCV)

## Customization

You can adjust these parameters in the code:
- `scaleFactor`: How much the image size is reduced at each scale (default: 1.1)
- `minNeighbors`: How many neighbors each candidate rectangle should have (default: 5)
- `minSize`: Minimum possible object size (default: 30x30 pixels)

## Troubleshooting

If you encounter issues:
1. Verify your webcam is working
2. Check OpenCV is properly installed
3. Ensure the Haar Cascade file exists in your OpenCV installation

## Acknowledgments

- OpenCV for the Haar Cascade classifier
- Python community for excellent documentation
