# Cat-Dog-Panda Classifier

## NAME: MOHAN S
## REG.NO: 212223240094

A PyTorch image classification project that uses Transfer Learning with a pretrained ResNet18 model to classify images into three categories: **Cat, Dog, and Panda**.

## Features

- Transfer Learning using pretrained ResNet18
- PyTorch-based image classification
- Image preprocessing and normalization
- Data augmentation
- Frozen ResNet18 backbone
- Custom classification head
- ReLU activation
- Dropout regularization
- CrossEntropyLoss
- Adam optimizer
- CUDA/GPU support
- Best model checkpoint saving
- Image prediction using a trained model
- Streamlit web interface for image classification

## Model Architecture

```text
Pretrained ResNet18
        |
Frozen Backbone
        |
Linear Layer
        |
ReLU
        |
Dropout
        |
Output Layer
        |
Cat / Dog / Panda
