# Deepfake Detection on Images using MobileNetV2

This project focuses on detecting **deepfake images** using a lightweight deep learning model based on **MobileNetV2**. The goal is to accurately distinguish between real and manipulated images while maintaining computational efficiency for real-time and low-resource environments.

## Overview
Deepfakes pose serious risks to media trust, privacy, and security. This system leverages **MobileNetV2’s depthwise separable convolutions and inverted residuals** to extract features that identify visual artefacts such as unnatural expressions, rough edges, and lighting inconsistencies.

## Methodology
- Image preprocessing (resizing, normalization, face alignment)
- Data augmentation (rotation, brightness adjustment)
- Transfer learning with MobileNetV2
- Binary classification (Real / Fake)

## Dataset
- Deepfake Face Dataset (DFFD)
- FaceForensics++
- Train / Validation / Test split: 70% / 20% / 10%

## Results
- **Epoch = 1:**  
  Accuracy: 78%, Precision: 78%, Recall: 79%
- **Epoch = 25:**  
  Accuracy: 93%, Precision: 93%, Recall: 94%, Loss: 22%

## Technologies Used
- Python
- TensorFlow, Keras
- OpenCV
- CNN, MobileNetV2
- HTML, CSS (Frontend)

## Conclusion
The project demonstrates that **MobileNetV2** is an effective and efficient backbone for deepfake image detection. Its lightweight design makes it suitable for deployment on mobile and edge devices while maintaining high accuracy.

