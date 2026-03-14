# Real-Time Face Detection using OpenCV (Python)

## Project Description
This project detects human faces in real time using a webcam feed.  
It uses OpenCV's Haar Cascade classifier to identify faces in video frames and draw bounding boxes around them.

The system processes each frame from the webcam and detects multiple faces simultaneously.

---

## Technologies
- Python
- OpenCV (cv2)

---

## How It Works
1. The webcam captures live video frames.
2. Each frame is converted to grayscale to simplify processing.
3. OpenCV's Haar Cascade classifier scans the frame for faces.
4. When a face is detected, a bounding box is drawn around it.
5. The processed video frame is displayed in real time.

---

## How to Run

Install the required library:

pip install opencv-python

Run the program:

python main.py

---

## Example Output
The program opens the webcam and detects faces in real time.  
Detected faces are highlighted with a rectangle around them.

---

## Project Purpose
This project demonstrates basic computer vision techniques using OpenCV and Python.  
It is an introduction to face detection and real-time image processing.

---

## Future Improvements
Possible improvements for the project include:

- Adding face recognition functionality
- Detecting emotions or facial expressions
- Saving detected faces as images
- Improving detection accuracy

---

## Author
Sean Michaeli
