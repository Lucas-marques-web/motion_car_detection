# Motion Object Detection in Video

This Python script uses OpenCV to perform motion object detection in a video stream. It applies background subtraction and contour detection to identify moving objects in the video. When motion is detected, it draws bounding rectangles around the moving objects in real-time.

## Requirements

- Python 3.x
- OpenCV library (you can install it using `pip install opencv-python`)

## How to Use

1. Make sure you have OpenCV installed.

2. Place the video file you want to process in the same directory as your script. The video file should be named 'FroggerHighway.mp4'.

3. Run the `main.py` script.

4. A window titled 'Detecção de Objetos em Movimento' will appear.

5. The script will process the video frame by frame, detecting and highlighting moving objects.

6. Detected objects will be outlined with yellow rectangles.

7. You can press the 'q' key or the 'Esc' key to exit the program.

## Features

- The script uses the BackgroundSubtractorMOG2 method to perform background subtraction.

- It applies a threshold to the result to create a binary mask.

- Contours are then detected in the binary mask to identify moving objects.

- Moving objects are outlined with yellow rectangles in real-time.


Feel free to use this script for various motion detection tasks or adapt it to suit your specific needs!

