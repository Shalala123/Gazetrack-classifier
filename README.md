# Gazetrack-classifier
Python script to classify 5 different gaze directions (top, bottom, middle, left, right) and blinking. Input image is taken from a camera connected to pc, each image is fed into two different machine learning models.  
First model is dlib facial landmark predictor to detect face and facial landmarks, second model is our custom CNN model to classify gaze directions
