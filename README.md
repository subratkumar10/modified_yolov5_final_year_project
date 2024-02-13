# Object Detection and Localization Framework using Modified YOLOv5

## Project Overview

This project was created during my B.Tech final semester under the guidance of Prof. Anup Nandy from the Department of Computer Science and Engineering at NIT, Rourkela.

### Project Title
An Efficient Object Detection and Localization Framework using Modified YOLOv5

## Introduction

Object detection and localization are crucial tasks in computer vision, involving the identification, classification, and precise location determination of objects within images or video streams. Existing object detection systems often rely on various computer vision techniques, leading to slow and subpar performance.

This project addresses the challenges by focusing on single-stage object detection techniques like YOLO and experimenting with the modification of YOLOv5 architecture to enhance accuracy. Traditional YOLOv5 models may struggle with accuracy, especially in challenging environments with factors such as inadequate lighting, tiny or crowded objects, obscured views, low light, reflections, and partial object views.

### Methodology

In our approach, we take an end-to-end deep learning-based solution to the object detection problem. We utilize a hybrid feature extraction method incorporating Autoencoder, Canny edge extraction, and Scale Invariant Feature Transform (SIFT) to enhance accuracy, particularly for tiny and low-light images. The project introduces a novel approach for obtaining optimal anchor box sets using genetic algorithms and k-means clustering, significantly contributing to efficient object detection with improved precision.

### Results

The modified YOLOv5 model achieved a mean Average Precision (mAP) of 95.8% and a total loss of 0.015%, showcasing a satisfying result. The proposed model outperforms traditional YOLOv5 and SSD Mobilenetv2 in terms of mAP score, loss, and frames per second (fps), making it a preferred choice for efficient object detection.

## Keywords
Object Detection, YOLOv5, Image Processing, Canny Edge Extraction, SIFT, Autoencoder

## Objective

1. Design an efficient and improved model for object detection with high precision and fast execution.
2. Investigate and analyze the impact of different image processing and feature extraction techniques on the proposed model's performance.

## Additional Information

Thesis and PowerPoint presentations related to this project are available in this repository.

Feel free to explore and contribute to the development of this project!
