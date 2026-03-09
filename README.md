# Deep Learning Lung Cancer Detection using AlexNet (MATLAB)
## Project Overview

This project implements a deep learning based medical image classification system to detect lung cancer from chest X-ray images using Convolutional Neural Networks (CNNs).

The model leverages transfer learning using AlexNet architecture to classify X-ray images into four categories:

- Adenocarcinoma
- Large Cell Carcinoma
- Squamous Cell Carcinoma
- Normal Lung Tissue

The system was developed using MATLAB Deep Learning Toolbox.

## Dataset

- Chest X-ray dataset
- 1000 images
- 4 classes

Images are split into:

- Training dataset
- Test dataset
- Validation dataset

## Model Architecture

CNN Architecture (AlexNet Transfer Learning)
```
Input Chest X-ray Image
        ↓
Convolution Layers
        ↓
Pooling Layers
        ↓
Feature Extraction
        ↓
Fully Connected Layer
        ↓
Softmax Classification
        ↓
Lung Cancer Type Prediction
```
## Training Configuration

- Optimizer: SGDM
- Epochs tested: 8, 10, 12
- Learning rate: 0.0001

## Results
| Epochs | Accuracy |
| ------ | -------- |
| 8      | 84.33%   |
| 10     | 87%      |
| 12     | 90.67%   |

## Highest model accuracy achieved:

90.67%.

## Technologies Used

- MATLAB
- Deep Learning Toolbox
- AlexNet
- CNN
- Medical Image Processing

## Visual Results
<img width="608" height="478" alt="Screenshot 2024-05-05 163654" src="https://github.com/user-attachments/assets/e83b8c91-5986-45e2-a9ef-77bc0dd84064" />
<img width="899" height="699" alt="Screenshot 2024-05-05 222356" src="https://github.com/user-attachments/assets/dae943e2-f337-42af-911a-04a557b69922" />
<img width="1854" height="740" alt="Screenshot 2024-05-05 222432" src="https://github.com/user-attachments/assets/d1b3d383-7fac-4c39-a00e-31161dad88ad" />
<img width="892" height="512" alt="Screenshot 2024-05-03 220812" src="https://github.com/user-attachments/assets/cacf2225-e3dd-4f48-819c-e121b635cde9" />


## Key Features

- Developed a Convolutional Neural Network (CNN) based medical image classification system for lung cancer detection using chest X-ray images.
- Implemented transfer learning using the AlexNet architecture to improve classification performance.
- Performed image preprocessing and dataset organization using MATLAB ImageDatastore for efficient training and validation.
- Applied deep learning techniques for automatic feature extraction from medical images.
- Evaluated model performance using accuracy metrics and confusion matrix analysis.
- Achieved up to 90.67% classification accuracy across four lung cancer categories.
