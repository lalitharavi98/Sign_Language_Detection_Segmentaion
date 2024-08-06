# Sign Language Detection and Hand Pose Cropping

## Overview

This repository contains a project for detecting sign language characters from images and cropping the hand poses. The project utilizes Detectron2 with a Faster R-CNN model for object detection and applies various image processing techniques to highlight the hand poses.

## Dataset

The dataset comprises 1,323 images of hand poses representing different alphabet characters (A-Z). The images are divided into training, validation, and test sets, and each image is annotated with bounding boxes in XML format. [Dataset Link](https://drive.google.com/drive/folders/1mBirzBBTImOVISP1aVricwlKB7y0areF?usp=drive_link)

## Tasks

1. **Object Detection for Sign Language Recognition**
   - Built an object detection model using Detectron2 and Faster R-CNN.
   - Evaluated the model's performance on the validation set.
   - Metrics: Mean Average Precision (mAP) and other relevant evaluation metrics.

2. **Hand Pose Cropping**
   - Processed images to crop and highlight the hand poses.
   - Applied image processing techniques such as background subtraction, color thresholding, and contour extraction.

Refer to the Jupyter Notebook [Sign\_Language\_Detection\_Segmentation.ipynb](Sign_Language_Detection_Segmentation.ipynb) for detailed implementation.




