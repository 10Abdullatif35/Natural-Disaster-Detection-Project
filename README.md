# Natural Disaster Detection Project

This project has been developed to detect natural disasters using deep learning. A user interface has been created using Keras and OpenCV, allowing for classification of uploaded images as well as webcam images.

## Table of Contents
- [Project Overview](#project-overview)
- [Installation](#installation)
- [Usage](#usage)
- [File Descriptions](#file-descriptions)
- [Developers](#developers)

## Project Overview
This project perfectly aims to develop a model that detects natural disasters. Users can view webcam images or upload a file for classification. The model processes the uploaded or webcam-captured images to identify which type of natural disaster is present and provides a confidence score for the prediction.

## Installation
#### Python and library versions that need to be installed
```bash
Python version: 3.9.13 
pip install tensorflow==2.10.0
pip install numpy==1.24.3
pip install opencv-python==4.5.5
pip install Pillow==10.4.0


```

Required files:
- `keras_Model.h5`: Pre-trained Keras model.
- `labels.txt`: File containing class labels.
- `Test_İmage.png`: An image file used for testing (optional).

## Usage
1. **Classifying with Webcam**:
   - When the application opens, click the "Turn On Camera" button to activate the webcam feed.
   - The model will classify natural disasters as it captures images from the webcam.

2. **Uploading an Image**:
   - Click the "Upload Image" button to select an image file from your computer.
   - The uploaded image will be classified, and the results will be displayed on the screen.

3. **Exiting the Program**:
   - Click the "Exit" button to close the application.

## File Descriptions

- **Image.py**: Code used to classify an uploaded image.
  
- **Opencv.py**: Code that captures webcam images and performs real-time classification.

- **App.py**: Tkinter-based user interface application. It includes options for webcam and file uploads.

## Developer
- Abdullatif Akkaya
