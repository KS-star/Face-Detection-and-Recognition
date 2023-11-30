# Face-Detection-and-Recognition
Overview:
Welcome to the Face Detection and Recognition repository! This project showcases advanced techniques in computer vision, specifically focusing on two major aspects: Image Detection using MTCNN and Image Recognition in three comprehensive steps.

1. Image Detection using MTCNN (Folder: Part 1):
In this section, we delve into sophisticated face detection employing the MTCNN (Multi-task Cascaded Convolutional Networks) model. The MTCNN is a cutting-edge solution for detecting faces in images, and the code in this folder provides a detailed implementation. The process involves loading an image, utilizing the MTCNN library to detect faces, and visually presenting the results with bounding boxes.

Usage:
Explore the Image_Detection_MTCNN folder to access the code, resources, and examples demonstrating the prowess of MTCNN in accurately detecting faces in various images.

2. Image Recognition (Folder: Part 2):
This section outlines a comprehensive three-step approach to image recognition, covering dataset generation, model training, and real-time recognition using the trained model.

Step 1: Dataset Generation
The dataset.py script captures real-time images from a webcam, applies Haar cascades for efficient face detection, and saves the cropped faces as individual images. This step ensures the creation of a diverse and comprehensive dataset for subsequent model training.

Step 2: Training the Face Recognition Model
The training.py script processes the generated dataset. Images are converted to grayscale, and the LBPH (Local Binary Pattern Histogram) Face Recognizer is employed for training. The resulting model, capturing unique facial features, is saved as "classifier.xml" for later use.

Step 3: Real-time Face Recognition
The checking.py script implements real-time face recognition using the trained model. The code captures video frames from a webcam, detects faces, and identifies individuals based on the learned facial patterns. Recognition results are visually displayed, contributing to a seamless and accurate user experience.

Usage:
Navigate to the Part 2 folder to explore the code, datasets, and resources associated with each step of the image recognition process.
