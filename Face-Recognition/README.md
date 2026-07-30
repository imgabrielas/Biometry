# Face Recognition

A simple face detection demo built with OpenCV (`cv2`). It uses a pre-trained
Haar cascade classifier (`haarcascade_frontalface_default.xml`) to detect
faces in an image, crop each detected face, and save the crops individually.

## How it works

1. Load the image and convert it to grayscale (Haar cascades operate on
   grayscale input).
2. Run `cv2.CascadeClassifier.detectMultiScale` to find face bounding boxes.
3. Crop each detected face and save it to `stored_faces/`.
4. Display the original image and a grid of the cropped faces with
   `matplotlib`.

## The picture

The sample image, `modernfamily.jpg`, is a promotional cast photo from the
TV show *Modern Family*, which premiered on ABC on September 23, 2009.