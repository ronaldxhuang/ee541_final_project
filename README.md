# EE 541 Final Project

# CV for American Sign Language

# Group 2

# Ronald Huang and Tanvi Gandhi

# Model Overview
- This project uses two pretrained convolutional neural network architectures; ResNet18 and MobileNetv2 to classify the ASL alphabet. 
- ResNet18 contains around 11.7 million parameters and has a file size around 44 MB
- MobileNetv2 contains around 3.4 million parameters and has a file size around 14 MB
- The fine-tuned ResNet18 model had a test set accuracy of 99.71% 

# Dataset Description
The dataset contains 87,000 samples. There are a total of 29 classes, including the letters A to Z and gestures for "space", "delete", "Nothing". Details can be viewed using this link (https://www.kaggle.com/datasets/grassknoted/asl-alphabet)

# Requirements
- Python 3.8
- PyTorch 1.12
- Torchvision
- MatplotLib
- Scikit Learn
- Numpy 
- Pandas
- GPU access
