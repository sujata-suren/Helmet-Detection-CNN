# Helmet-Detection-CNN
CNN-based helmet compliance detector using VGG16, achieving 99.6% accuracy for automated safety monitoring.

This project presents a deep learning solution for automatically detecting helmet compliance among workers in hazardous environments such as construction sites and industrial settings. The system uses a **CNN-based binary image classifier** to identify whether a person is wearing a safety helmet, helping improve safety enforcement by replacing manual monitoring with an accurate, automated vision-based approach.

## Project Highlights

**Model**: Built a Convolutional Neural Network (CNN) using transfer learning with **VGG16** to classify images into two categories: **helmet** and **no helmet**.
**Performance**: Achieved **99.6% accuracy**, recall, precision, and F1-score on test data.
**Automation**: Provides a scalable computer vision system for real-time or batch safety compliance monitoring.
**Data Pipeline**: Used **ImageDataGenerator** for training and validation splits, along with **data augmentation** to improve model robustness.

## Tools & Technologies

**Deep Learning**: TensorFlow, Keras
**Computer Vision**: OpenCV, VGG16
**Model Architecture**: CNN, Feed Forward Neural Network
**Data Handling**: ImageDataGenerator, Data Augmentation
