# ROI_Car_detection

## Abstract
The problem statement is to detect the cars in a youtube video only in the certain region of interest and should not detect the cars in the sideways using yolov5 algorithm.

Yolov5 -  It is a novel convolutional neural network (CNN) that detects objects in real-time with great accuracy.

Here we are using the Yolov5 pretained model as the object to be detected is a car which was already pretrained in yolo v5.

We are using OpenCV for image and frame processing and pytbue for downloading the youtube video to local. Pytorch for for loading the pretrained yolov5 model and its weights.

The co ordinates which we are specify in this notebook to draw line is solely based on the video that we considered as input. For other videos the co-ordinates should change according to the use case.

The output video format is avi and the codec is ('M','J','P','G').

