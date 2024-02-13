This project is created by me in my btech final semester under the guidance of Prof. Anup Nandy from Dept. of Computer Science and Engineering of NIT, Rourkela.
Project Title: An Efficient Object Detection and Localization Framework using Modified YOLOv5

Object detection is the process of identifying and classifying objects within an image or
video stream, while localization involves determining the precise location and extent of the
detected objects. The dependence on other computer vision techniques for support in many
object detection systems, which results in slow and subpar performance, is a significant
challenge. Image recognition, image generation, and object detection are just a few of the
many components that make up computer vision. The major challenging task of object
detection is to recognise items in a semi-structured environment with inadequate lighting,
tiny, crowded objects, objects that are obscured by other objects, low light, reflecting
surfaces, amorphous bodies and partial views of an object. Here, we’ve focused on single
stage object detection techniques like YOLO and experimented on modification of YOLOv5
architecture to improve accuracy of the model as conventional YOLOv5 model fails to
achieve it. In this project, we take an end-to-end approach to solving the object detection
problem that is entirely based on deep learning. We have applied various image processing
techniques and a proposed feature extraction method which is a hybrid of Autoencoder,
Canny edge extraction and SIFT (Scale Invariant Feature Transform) to improve the accuracy
of tiny and low light images. We have obtained best fit anchor box sets using genetic
algorithm and kmean clustering which play a major role in enhancing efficient object
detection with better precision. The suggested modified YOLOv5 model achieves mean
Average Precision (mAP) of 95.8% and a total loss of 0.015% which is a very satisfying
result. Modified YOLOv5 gives better mAP score, loss and fps (frames per second)
compared to SSD Mobilenetv2 making it a better choice for efficient object detection.

Keywords: Object Detection; YOLOv5; Image Processing; Canny Edge
Extraction; SIFT; Autoencoder


Objective
1. To design an efficient and improved model for object detection with high precision
and fast execution.
2. To investigate and analyze the impact of different images processing and feature
extraction techniques on the proposed model’s performance.

Thesis and PPT presenations are attached in this repository.
