# chest-x-ray-disease-classification
A medical imaging project that uses Deep Learning to automatically detect pneumonia from chest X-ray images. The system compares three different neural network architectures—VGG16, ResNet50, and EfficientNetB0—to identify the most accurate model for clinical diagnosis.

**Project Overview**
This project focuses on the binary classification of chest radiographs into "Normal" and "Pneumonia" categories to assist healthcare professionals in faster screening.

**Multi-Model Benchmarking**: I implemented and fine-tuned three state-of-the-art Transfer Learning models (VGG16, ResNet50, and EfficientNetB0) using TensorFlow/Keras to evaluate which architecture best captures subtle lung abnormalities.

**Data Pipeline & Augmentation**: To improve model robustness, I built a data pipeline using ImageDataGenerator that applies real-time transformations like horizontal flips, rotations, and zooms, compensating for the limited size of medical datasets.

**Comprehensive Evaluation**: The models are rigorously tested on a separate test set, with performance measured using Precision, Recall, F1-Score, and Confusion Matrices to ensure a low rate of false negatives (crucial for medical diagnostics).

**Visual Diagnostics**: The project includes custom utility functions to visualize training trends and overlay model predictions on sample X-ray images, providing a clear view of the model's confidence in its results.

**Technical Features**
Frameworks: TensorFlow, Keras, Scikit-learn.

**Preprocessing**: Image rescaling, normalization, and dynamic validation splitting.

**Visualizations**: Training history plots (Accuracy/Loss), Confusion Matrices, and interactive sample prediction grids.
