## Face recognition application

This repo using the library face_recognition to build the application which can identify and recognize the human face from images as well as in real-time video stream

## Installation

Requirements

1. Python 3.3+ or Python 2.7
2. macOS or Ubuntu (Any Linux OS)


### Installing on Ubuntu 16.04 LST

1. Install dlib: You can install dlib from source on Ubuntu or for macOS using this [link](https://gist.github.com/ageitgey/629d75c1baac34dfa5ca2a1928a7aeaf)

2. Install face_recognition: ```sudo pip install face_recognition```

3. Install OpenCV using this [link](https://www.pyimagesearch.com/2015/06/22/install-opencv-3-0-and-python-2-7-on-ubuntu/)

4. `imutils - sudo pip install imutils`

## Run the code:

* face_detection_example.py 
    ```
    This script find the faces form the image. 
    This code can run on CPU
    Give the path of the image on which you want to run this code
    Command that you need to run: python face_detection_example.py 
    ```
 
* Real_time_face_detection.py 
   * This script identify the person names. If face is not fimiliar then it tags as unknown.
   * You need to provide sample image with person name So that machine can identify the person's name.
    ```
    You can run this code: python Real_time_face_detection.py 
    ```
## Demo of the real_time_face_detection
![demo](https://user-images.githubusercontent.com/12840374/36086221-f2b13c08-0ff0-11e8-85a0-11ef4a900c2f.gif)


![Another demo](https://cloud.githubusercontent.com/assets/896692/24430398/36f0e3f0-13cb-11e7-8258-4d0c9ce1e419.gif)
## Credit

Credit for the majority of code here goes to [Adam Geitgey](https://github.com/ageitgey/face_recognition). I've merely created a wrapper to get people started. His library has many other APIs which you can explore