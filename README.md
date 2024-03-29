# Hand gesture recognition model

***This repository contains implementation of model that can accurately identify and classify different hand gestures from image or video data, enabling intuitive human-computer interaction and gesture-based control systems.***

# Dataset
Kaggle dataset :https://www.kaggle.com/datasets/gti-upm/leapgestrecog

 # Getting Started 
 ### Prerequisites
 -   Python 3.x
 - Matplotlib:  `!pip install matplotlib`
-  NumPy:  `!pip install numpy`
- tensorflow:  `!pip install tensorflow`
-  sklearn:  `!pip install sklearn`

# Model implementation
A CNN was used to train the model on a large set of video clips containing a variety of hand gestures belonging to 10 different categories.
The activation function used for output layer is "softmax" with optimizer "rmsprop"

# Accuracy & Prediction
after training and validation with 10 epochs , accuracy reached  **100%** 
