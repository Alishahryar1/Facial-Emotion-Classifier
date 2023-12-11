# Real-Time Webcam Facial Emotion Classifier

This repository contains the code for a real-time facial emotion classifier using a webcam. The classifier is built using Python and Keras, leveraging libraries like OpenCV, face-recognition, numpy, and dlib for facial detection and emotion classification.

## Requirements

The project depends on specific versions of libraries. Ensure you have the following versions installed:

- Keras==2.6.0
- opencv-python==4.5.3.56
- face-recognition==1.3.0
- numpy==1.21.2
- dlib==19.22.99

## Installation

To set up the project, follow these steps:

1. Clone the repository: git clone https://github.com/Alishahryar1/Realtime-Facial-Emotion-Classifier
2. Navigate to the cloned directory: cd Realtime-Facial-Emotion-Classifier
3. Install the required packages: pip install -r requirements.txt 

## Usage

To run the real-time facial emotion classifier:

1. Execute the main script: python main.py
2. Ensure your webcam is connected and permitted to be used by the script.

The script will open a window displaying the webcam feed. Faces detected in the feed will be analyzed for emotion, and the predicted emotion will be displayed on the screen.

## How It Works

The classifier uses `dlib` and `face-recognition` for detecting faces in the webcam feed. Once a face is detected, the region of interest is preprocessed and fed into a trained Keras model to classify the emotion.

The emotions classified can include happiness, sadness, anger, surprise, etc., depending on the trained model used.
