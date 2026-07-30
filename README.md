# Biometry

A collection of small biometric identification/recognition projects, each in its own subfolder.

## Projects

### [Face Recognition](Face-Recognition/)

Face detection with OpenCV using a pre-trained Haar cascade classifier. Detects faces in an image, crops each one, and saves the crops individually. See the [subfolder README](Face-Recognition/README.md) for details.

### Fingerprint Identification (work in progress)

A convolutional neural network (CNN) that identifies a person from a fingerprint scan. This project is still under active development, so the code and dataset are not published in this repository yet. :/

## Requirements

See [`requirements.txt`](requirements.txt) for pinned package versions used across these projects (numpy, opencv-python, scikit-learn, tensorflow, matplotlib).