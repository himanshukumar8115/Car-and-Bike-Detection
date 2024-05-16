# Car-and-Bike-Detection

# demo




https://github.com/himanshukumar8115/Car-and-Bike-Detection/assets/154125962/bc12da42-7a95-402c-8072-e138c43dbce6


https://youtu.be/zMzsQcO2hEs



Overview
YOLO (You Only Look Once) is a state-of-the-art, real-time object detection system. Unlike traditional detection systems that apply a classifier to an image at multiple locations and scales, YOLO applies a single neural network to the full image. This network divides the image into regions and predicts bounding boxes and probabilities for each region. These bounding boxes are weighted by the predicted probabilities.

Features
Real-time detection: YOLO is fast and can process 45 frames per second on a Titan X GPU.
Unified detection: YOLO frames object detection as a single regression problem, straight from image pixels to bounding box coordinates and class probabilities.
End-to-end training: The entire model is trained jointly to minimize error.
Applications
Autonomous vehicles for detecting pedestrians, other vehicles, and obstacles.
Surveillance systems for real-time monitoring.
Robotics for object recognition and manipulation.
Augmented reality for identifying and interacting with real-world objects.
Installation
To get started with YOLO, you can use the Darknet framework. Here are the steps to install Darknet and YOLO:

Prerequisites
A computer with a GPU (for faster processing)
CUDA and cuDNN installed
