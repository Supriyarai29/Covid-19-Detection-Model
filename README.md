# Covid-19-Detection-Model

Project Overview
This project focuses on the development of a deep learning model for ternary classification of chest X-rays. The model is designed to distinguish between three categories:
COVID-19 positive cases
Pneumonia cases
Normal (healthy) cases

Model Architecture
The model leverages transfer learning with ResNet-50, a powerful convolutional neural network (CNN), to ensure robust medical image classification.
Transfer learning allows the model to generalize well even with a limited dataset by using pre-trained weights from large-scale image datasets.

Performance
The model achieved 96% accuracy, demonstrating its effectiveness in distinguishing between COVID-19, other viral infections, and normal cases.
Evaluation was performed using standard metrics such as accuracy, precision, recall, and F1-score.

Dataset
The dataset consists of labeled chest X-ray images from publicly available medical imaging repositories.
Data augmentation techniques were applied to enhance model generalization and prevent overfitting.
