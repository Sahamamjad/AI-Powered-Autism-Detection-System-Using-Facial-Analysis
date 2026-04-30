# AI-Powered-Autism-Detection-System-Using-Facial-Analysis
AI-Based Autism Detection System Using Deep Learning
Overview

This project presents a deep learning-based system for detecting Autism Spectrum Disorder (ASD) using facial image analysis. The objective is to support early and accessible screening by leveraging computer vision and transfer learning techniques.

Traditional ASD diagnosis relies on manual clinical assessments, which are often time-consuming and subjective. This project explores an automated approach that classifies facial images to assist in early-stage screening.

Key Features
Automated ASD classification from facial images
Comparison of multiple deep learning models
High-performance model using transfer learning
Full-stack web application for user interaction
PDF report generation for results
Dataset
~2,940 labelled facial images (ASD vs Non-ASD)
Children aged approximately 2–12 years
Images collected from Kaggle ASD datasets
Methodology
Data Preprocessing
Image resizing and normalisation
Data augmentation:
Rotation
Flipping
Scaling
Shifting
Models Implemented
Baseline CNN
VGG16
VGG19
EfficientNetB3
EfficientNetB4
Evaluation Metrics
Accuracy
Precision
Recall
F1-score
Confusion Matrix
Results
Model	Accuracy
CNN	61%
Multilayer CNN	59%
VGG19	92.00%
VGG16	92.34%
EfficientNetB3	96.09%
EfficientNetB4	97.44%

Best Model: EfficientNetB4

Accuracy: 97.44%
Precision / Recall / F1-score: ~0.97
Reduced false positives and false negatives
System Architecture
Frontend
React.js
Tailwind CSS
Backend / AI Model
TensorFlow / Keras
OpenCV
Scikit-learn
Training Environment
Kaggle GPU (P100)
