# Face-Mask-Detection
Face Mask Detection system built with OpenCV, Keras/TensorFlow using Deep Learning and Computer Vision concepts in order to detect face masks in static images as well as in real-time video streams.
# Tech/framework used
* OpenCV
* Caffe-based face detector
* Keras
* TensorFlow
* MobileNetV2
# Features
This face mask detector didn't uses any morphed masked images dataset. The model is accurate, and since we used the MobileNetV2 architecture, it’s also computationally efficient and thus making it easier to deploy the model to embedded systems (Raspberry Pi, Google-Coral, etc.).

This system can therefore be used in real-time applications which require face-mask detection for safety purposes due to the outbreak of Covid-19. This project can be integrated with embedded systems for application in airports, railway stations, offices, schools, and public places to ensure that public safety guidelines are followed.

# Dataset
This dataset consists of 3835 images belonging to two classes:

* with_mask: 1916 images
* without_mask: 1919 images

The images used were real images of faces wearing masks. The images were collected from the following sources:

Bing Search API (See Python script)
Kaggle datasets
RMFD dataset (See here)
