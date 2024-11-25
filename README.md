# Sign-Language-Detection

## Objective
Computer Vision and Deep learning-based American sign language detection system using OpenCV and Tensoflow.

## Dataset
[Link to Dataset](https://drive.google.com/file/d/1ZDpr31LxLHgFsiKSIAXc3kQ9BHmrmmrV/view?usp=sharing)

## Feature Extraction and Pre processing
* Made use of Gaussian filter to make the image smooth and eliminate all the irrelevat noise.
* Intensity is analyzed and Non-Maximum suppression is implemented to remove false edges.
* Double thresholding is implemented to consider only the strong edges in the images for a better pre-processed image data.
* All the weak edges are finally removed and only the strong edges are consdered for the further phases.

##  Results 
Model has an accuracy of 99.6 %
