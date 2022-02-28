# Human-Counting
In this python project, we are going to build the Human Detection and Counting System through Webcam or you can give your own video or images. This is an intermediate level deep learning project on computer vision, which will help you to master the concepts and make you an expert in the field of Data Science. Let’s build an exciting project.

# Installation
```
pip install opencv-python
pip install imutils
pip install numpy
```

# Steps To Build Human Detection Project
## Import the libraries
```
import cv2
import imutils
import numpy as np
import argparse
```

## Create a model which will detect Humans
``
HOGCV = cv2.HOGDescriptor()
HOGCV.setSVMDetector(cv2.HOGDescriptor_getDefaultPeopleDetector())
``

# Run the Human Detection Project
## To give video file as input
`python main.py -v ‘Path_to_video’`
## To give image file as input
`python main.py -i ‘Path_to-image’`
## To use the camera
`python main.py -c True`
## To save the output
`Python main.py -c True -o ‘file_name’`

# Project Output
Now, after running the human detection python project with multiple images and video, we will get:

![This is an image](https://data-flair.training/blogs/wp-content/uploads/sites/2/2020/07/human-counting-output.jpg)


