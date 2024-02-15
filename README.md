# Face Recognition with MTCNN

## Overview

This project explores the implementation of face recognition using the Multi-task Cascaded Convolutional Neural Network (MTCNN), a deep learning model that significantly outperforms traditional computer vision techniques in identifying and verifying individuals by their facial features. Leveraging large datasets, MTCNN learns rich representations of faces, enabling applications in security, social media, and beyond with enhanced accuracy and efficiency.

## System Design and Implementation

Utilizing Python and libraries such as TensorFlow, Scikit-learn, SciPy, Numpy, and OpenCV, we designed a facial recognition system centered around MTCNN. The model operates in three stages, beginning with proposing candidate facial regions, refining bounding boxes, and finally, identifying facial landmarks. Our implementation covers four key functionalities:
- **Bounding Box Regression**: Drawing boxes around detected faces.
- **Facial Landmark Detection**: Identifying key facial features.
- **Blur the Face**: Anonymizing faces for privacy.
- **Real-Time Image Bounding Box**: Implementing facial detection in live video feeds.

The project demonstrates these capabilities through a test image, showcasing how MTCNN can accurately detect faces and their features, even applying real-time detection using a webcam.

## Results and Discussion

The project successfully implements facial recognition with MTCNN, demonstrating not only face detection but also the application of blurring faces for privacy protection. Through rigorous testing, the model showcased its capability to accurately identify facial features and landmarks, providing a robust solution for real-time and static image facial recognition.
