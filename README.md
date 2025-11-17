# Realtime Emotion Detection Using Keras

### This model has been trained for 40 epochs and runs at 71.69% accuracy.

## How to Run the Model
Install these dependencies using pip:
- pip install numpy
- pip install pandas
- pip install tensorflow
- pip install keras
- pip install opencv-python
- pip install future

### Download HAAR Cascade File
https://github.com/opencv/opencv/blob/master/data/haarcascades/haarcascade_frontalface_default.xml

### Download Dataset
https://www.kaggle.com/c/challenges-in-representation-learning-facial-expression-recognition-challenge/data

## Training the Model
python main.py

## Running the Emotion Detection UI
python UI.py

## Overview
This project performs real-time facial emotion detection using CNN (Keras/TensorFlow backend) and OpenCV.

## Dataset
FER2013 dataset with 48x48 grayscale images and 7 emotion classes.

## Result
Model achieved 71.69% accuracy.

## Future Work
Improve detection models, use advanced face detectors, expand dataset, and enhance UI.
