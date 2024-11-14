# Arthritis Detection Model

A deep learning model for classifying the severity of osteoarthritis in knee joints from **X-ray images**. Built using **PyTorch**, this model uses Convolutional Neural Networks (CNN) to classify knee X-rays into five distinct grades, offering automated arthritis detection for clinical applications.

## Overview

This repository contains a machine learning model that classifies knee X-ray images into one of five categories, each corresponding to a different severity of osteoarthritis:

- **Grade 0: Healthy Knee**  
- **Grade 1: Doubtful**  
- **Grade 2: Minimal Osteoarthritis**  
- **Grade 3: Moderate Osteoarthritis**  
- **Grade 4: Severe Osteoarthritis**

The model helps healthcare professionals in early detection and personalized treatment planning by automatically assessing the grade of arthritis based on X-ray images of knee joints.

## Categories

The model classifies knee X-rays into the following 5 categories:

| **Label** | **Category**                          |
|-----------|---------------------------------------|
| `0`       | Healthy knee (Grade 0)                |
| `1`       | Doubtful (Grade 1)                    |
| `2`       | Minimal osteoarthritis (Grade 2)      |
| `3`       | Moderate osteoarthritis (Grade 3)     |
| `4`       | Severe osteoarthritis (Grade 4)       |

### Grades Explained:
- **Grade 0**: Healthy knee with no signs of arthritis.
- **Grade 1**: Doubtful or early-stage arthritis, showing mild joint changes.
- **Grade 2**: Minimal osteoarthritis with clear but limited damage.
- **Grade 3**: Moderate osteoarthritis, with significant damage and pain.
- **Grade 4**: Severe osteoarthritis, characterized by extensive damage and chronic pain.

## Features

- **Input**: X-ray images of knee joints.
- **Output**: Arthritis grade (0-4).
- **Framework**: Built using **PyTorch** for deep learning, leveraging pre-trained models (e.g., ResNet, VGG) or custom CNN architecture.
- **Model Performance**: High accuracy in classifying X-ray images based on arthritis severity.

## Inference

To use the trained model for inference:

1. Load the trained model and input X-ray image.
2. Preprocess the image (resize and normalize).
3. Perform inference to predict the arthritis grade.

## Results
The model is evaluated using accuracy and other relevant metrics. It performs well in classifying knee X-rays into the appropriate arthritis grade, with results showing good separation between different grades.

## License
This project is licensed under the MIT License - see the LICENSE file for details.
