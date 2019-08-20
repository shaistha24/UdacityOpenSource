# Real Time Object Detection Using Pytorch 

## INTRODUCTION:
This project is an attempt, to implement Real Time Object Detection using Yolo v3 and OpenCv and Pytorch from scratch. The aim is to create an android app which can be used to detect object in real time with an option to detect specific object from within the set of images or video, and maybe on later stages use the object to reverse search the internet for information and facial recognition.

Most of the code has been inspired from the awesome tutorial by @ayooshkathuria (https://blog.paperspace.com/how-to-implement-a-yolo-object-detector-in-pytorch/ ) and the paper by @pjreddie ( https://pjreddie.com/media/files/papers/YOLOv3.pdf ). The code is based on the official code of YOLO v3 ( https://pjreddie.com/darknet/yolo/ ) , as well as a PyTorch port of the original code, by @marvis (https://github.com/marvis/pytorch-yolo2 ).

## WHY CHOOSE YOLO?
YOLOv3 is the latest variant of a popular object detection algorithm YOLO – You Only Look Once, a state-of-the-art, real-time object detection system. The published model recognizes 80 different objects in images and videos, but most importantly it is super fast and nearly as accurate as Single Shot MultiBox (SSD).

Starting with OpenCV 3.4.2, you can easily use YOLOv3 models in your own OpenCV application.

On a Pascal Titan X it processes images at 30 FPS and has a mAP of 57.9% on COCO test-dev. YOLOv3 is extremely fast and accurate. In mAP measured at .5 IOU YOLOv3 is on par with Focal Loss but about 4x faster. Moreover, you can easily tradeoff between speed and accuracy simply by changing the size of the model, no retraining required! For more information visit this link. (https://pjreddie.com/darknet/yolo/)

![Comparison to Other Detectors](https://github.com/shaistha24/UdacityOpenSource/blob/Shaistha/Shaistha/2019-08-21%2002_07_25-YOLOv3.pdf.png)
