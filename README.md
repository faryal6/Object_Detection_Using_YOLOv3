# Object-detection-using-YOLO
YOLO is a state-of-the-art, real-time object detection algorithm. In this notebook, we will apply the YOLO algorithm to detect objects in images, videos and webcam.

# YOLOv3-Object-Detection-with-OpenCV

This project implements an image and video object detection classifier using pretrained yolov3 models. 
The yolov3 models are taken from the official yolov3 paper which was released in 2018. The yolov3 implementation is from [darknet](https://github.com/pjreddie/darknet). Also, this project implements an option to perform classification real-time using the webcam.

## How to use?

1) Clone the repository

```
git clone https://github.com/faryal6/Object_Detection_Using_YOLOv3.git
```
2) Move to the directory
```
cd Object_Detection_Using_YOLOv3
```
3) download yolov3 weights and place it inside weights directory [YOLOv3 Pre-trained Model Weights (yolov3.weights)(237 MB)](https://pjreddie.com/media/files/yolov3.weights)
``` 
4) To infer on an image that is stored on your local machine
```
run image.ipnyb notebook
```
5) To infer on a video that is stored on your local machine
```
run video.ipnyb notebook
```
6) To infer real-time on webcam
```
run webcam.ipnyb notebook
```
