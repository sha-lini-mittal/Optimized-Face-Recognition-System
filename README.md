
```text
This project implements face detection and face recognition using Python.
It identifies faces from images and matches them with known individuals.

Features:
-Detects faces from images
-Recognizes known faces using facial encodings
-Supports multiple known people
-Simple and easy-to-understand implementation

Technologies Used:
Python
OpenCV
face_recognition
NumPy

Folder Structure:
known/          → Images of known people  
unknown/        → Images to test recognition  
main.ipynb      → Face detection & recognition code  

How It Works:
-Load images of known people
-Generate face encodings
-Detect faces in unknown images
-Compare faces with known encodings
-Display name if a match is found

How to Run:
-Install required libraries:
 pip install face_recognition opencv-python
-Add known face images inside the known/ folder.
-Run the notebook or script.

Notes:
-Use clear, front-facing images for better accuracy.
-High-resolution images improve recognition results.

Output:
-Detected faces are highlighted with bounding boxes.
-Names are displayed for recognized faces.
-Unknown faces are labeled as Unknown.
