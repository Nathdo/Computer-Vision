# Computer-Vision

This repository contains various Computer Vision projects, including my work on Emotion Recognition using Convolutional Neural Networks (CNNs). These projects explore image preprocessing, feature extraction with MaxPooling, and techniques like Dropout to handle overfitting. Each project highlights practical solutions to challenges such as handling different image sizes and improving model performance.

## Projects

### CatDog Recognition
This project focuses on classifying images of cats and dogs using CNNs to extract key features distinguishing between the two. The model is trained on labeled images of cats and dogs, and incorporates data augmentation to improve generalization on unseen data. The project showcases techniques for handling imbalanced classes and tuning hyperparameters to enhance accuracy.

### Emotion Recognition
In this project, I developed a model to recognize facial emotions, such as happiness, sadness, and surprise, using CNNs. The model processes facial images, using layers like MaxPooling and Dropout to reduce overfitting while maintaining high accuracy across diverse facial expressions. This project also includes image resizing to standardize input sizes, enhancing the model’s robustness for real-world application.

### SignMNIST
The SignMNIST project focuses on recognizing American Sign Language (ASL) letters from images of hand gestures. This model is trained on the Sign Language MNIST dataset, where each image represents a single ASL letter (excluding J and Z due to motion). By using convolutional layers, the model effectively identifies hand gestures, presenting an opportunity to assist in ASL interpretation through computer vision.
