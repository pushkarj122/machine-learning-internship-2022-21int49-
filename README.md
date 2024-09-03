# Face Mask Detection Using OpenCV and Machine Learning

## Overview

This repository contains the code and resources for a face mask detection project developed during an internship. The goal of this project was to build a model capable of detecting whether a person is wearing a mask or not using a combination of OpenCV and machine learning techniques.

## Project Workflow

### 1. Learning Python Fundamentals

- **Objective**: Gain proficiency in Python programming.
- **Activities**:
  - Covered Python basics including variables, data types, typecasting, and conditionals.
  - Explored loops, break & continue statements, and operators.
  - Studied lists, dictionaries, and functions.
  - Practiced by solving basic problems (e.g., calculator, patterns, Fibonacci series, reverse integer).

### 2. Setting Up the Development Environment

- **Objective**: Familiarize with tools and setups for data analysis and machine learning.
- **Activities**:
  - Installed Anaconda and set up Jupyter Notebook.
  - Explored the Jupyter Notebook interface and functionalities.

### 3. Research and Initial Experimentation

- **Objective**: Understand the problem domain and relevant technologies.
- **Activities**:
  - Researched face detection techniques and the importance of OpenCV.
  - Gained insights into the process of face detection and the utility of machine learning libraries.

### 4. OpenCV Basics and Face Detection

- **Objective**: Learn and apply OpenCV for basic image processing tasks.
- **Activities**:
  - Explored OpenCV operations such as reading, color changes, resizing, flipping, drawing shapes, and adding text to images.
  - Implemented face detection using MTCNN and OpenCV.
  - Conducted live face detection using a laptop webcam.

### 5. Dataset Collection and Model Training

- **Objective**: Develop a face mask detection model.
- **Activities**:
  - Collected and prepared a dataset for training.
  - Started working on a face mask detection model.
  - Utilized libraries such as NumPy and scikit-learn for data splitting.
  - Initially trained the model using VGG16, encountering issues with accuracy.
  - Improved model accuracy through iterative training and testing.

### 6. Real-Time Face Mask Detection

- **Objective**: Enhance the model for real-time applications.
- **Activities**:
  - Integrated the trained model with a live video feed from the laptop webcam.
  - Achieved decent accuracy in real-time mask detection.

### 7. Advanced Features and Face Recognition

- **Objective**: Implement additional features and improve model performance.
- **Activities**:
  - Conducted research on face recognition techniques.
  - Implemented face recognition alongside face mask detection using Haar cascades and the `face_recognition` library.
  - Integrated face recognition with mask detection to display messages like “yes mask” and “no mask” based on the detection results.
  - Tested the integrated model on the provided dataset with satisfactory results.

## Technologies Used

- **Programming Languages**: Python
- **Libraries and Frameworks**:
  - OpenCV
  - TensorFlow/Keras
  - scikit-learn
  - NumPy
  - face_recognition
- **Tools**:
  - Jupyter Notebook
  - Anaconda
