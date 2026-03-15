# Smartphone Screen Glass Defect Detection using CNN

A deep learning project that detects defects in smartphone screen glass images using Convolutional Neural Networks (CNN) and MobileNetV2 transfer learning.

The system automatically classifies screen images as defective or non-defective to help improve automated quality inspection in manufacturing environments.





## DATASET

Dataset used in this project:

SSGD – Smartphone Screen Glass Dataset for Defect Detection

Dataset source:
https://github.com/VincentHancoder/SSGD

Dataset Details:
Total Images: 2,504

Classes:
- Defective Screen
- Non-Defective Screen


## MODEL ARCHITECTURE

The model uses Transfer Learning with MobileNetV2.

Architecture:

```
Input Image (224x224x3)
↓
MobileNetV2 Pretrained Layers
↓
Global Average Pooling
↓
Dense Layer
↓
Softmax Output Layer

```

CNN layers extract important visual features such as edges, patterns, and defect structures.



## PROJECT WORKFLOW

```
Dataset Collection
↓
Image Preprocessing
↓
Data Augmentation
↓
CNN Model Training
↓
Model Evaluation
↓
Defect Prediction
```


## MODEL PERFORMANCE

Accuracy: ~90.9%

Evaluation Metrics:
Precision: 0.91
Recall: 1.00
F1 Score: 0.95

The model demonstrates strong capability in detecting smartphone screen defects.


## AUTHOR

Abubakar Siddiq Sazzad

Department of Computer Science and Engineering
International University of Scholars

Email: siddiqsazzad001@gmail.com


LICENSE

This project is developed for academic and research purposes.
