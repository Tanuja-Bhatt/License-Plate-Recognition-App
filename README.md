# License-Plate-Recognition-App

This project is a web app that lets a user upload a photo of a car, and it tries to:
1.Find the license plate in the image.
2.Read the text (like the number) on the plate.
3.Display the result.

Key Technologies Used:-
Streamlit-	To build the web interface (upload image, show output).
OpenCV-	For image processing and contour detection (to locate the plate).
EasyOCR- To read the characters (like a human eye).
NumPy-	For array operations (images are arrays).
imutils-	To make some OpenCV tasks easier (like sorting contours).
PIL (Pillow)-	To convert image formats if needed.

