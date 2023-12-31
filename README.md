# Car Counting Yolo System
## Overview
You Only Look Once (YOLO) is a CNN architecture for performing real-time object detection. The algorithm applies a single neural network to the full image, and then divides the image into regions and predicts bounding boxes and probabilities for each region.

This project aims to count every vehicle (motorcycle, bus, car, cycle, truck, train) detected in the input video using YOLOv8 object-detection algorithm.
## Working
![Screen Recording - June 21, 2023](https://github.com/mayankmangalmourya/CarCounter/assets/87426167/c8c7b27c-2965-4737-b958-81a88b8cd847)

As shown in the image above, when the vehicles in the frame are detected, they are counted. After getting detected once, the vehicles get tracked and do not get re-counted by the algorithm.
You may also notice that the vehicles will initially be detected and the counter increments, but for a few frames, the vehicle is not detected, and then it gets detected again. As the vehicles are tracked, the vehicles are not re-counted if they are counted once.

## Execution Step :
 - Clone this repository in your preferable IDE : like VScode, pycham etc.
 - Firstly open the requirements.txt file and install all the dependencies.
 - Run defaultModel.py file in your IDE. Model is downloaded as name Yolov8s.pt
 - Now Open the carCounter.py file set all the addresses of model as well as vedio.
 - You can also use your own vedio but then you have to change mask and counterline.
 - You can successfully run it.
 - End.

## Technology Used :
 - Pycham
 - OpenCV
 - Ultralytics
 - cvZone

## IDE Used :
 - Pycham.
## Author : 
 - Mayank Mangal Mourya
 - Rajan Kumar
 - Abhishek kumar
 - Sagar deware
 - Raja Safi
 
### Contact : 
- 202051116@iiitvadodara.ac.in
- 202051003@iiitvadodara.ac.in
- 202051151@iiitvadodara.ac.in
- 202051166@iiitvadodara.ac.in
- 202051152@iiitvadodara.ac.in
   
