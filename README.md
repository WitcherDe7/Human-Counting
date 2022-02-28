# Human-Counting
This is machine learning algorithm for human counting

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

