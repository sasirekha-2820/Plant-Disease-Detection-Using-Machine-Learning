# Plant Disease Prediction using Deep Learning

## Overview

This project uses Deep Learning techniques to identify plant diseases from leaf images and assist farmers in early disease detection and crop management.

The model is trained using the PlantVillage dataset and leverages Transfer Learning with EfficientNetB3 to achieve high classification accuracy.

---

## Features

- Automatic plant disease classification
- Image-based disease detection
- Transfer Learning using EfficientNetB3
- Data augmentation for improved generalization
- Training, validation, and testing pipeline
- High accuracy image classification model

---

## Dataset

The project uses the **PlantVillage Dataset**, which contains thousands of labeled images of healthy and diseased plant leaves across multiple crop species.

Dataset Source:
https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset

---

## Technologies Used

- Python
- Google Colab
- TensorFlow
- Keras
- NumPy
- Matplotlib
- KaggleHub

---

## Model Architecture

- Base Model: EfficientNetB3
- Transfer Learning Approach
- Image Size: 224 × 224
- Batch Size: 32
- Data Augmentation Techniques:
  - Rotation
  - Zoom
  - Horizontal Flip
  - Width and Height Shift

---

## Project Workflow

1. Download and preprocess the PlantVillage dataset.
2. Perform data augmentation.
3. Split the dataset into training, validation, and testing sets.
4. Train the EfficientNetB3 model using transfer learning.
5. Evaluate model performance.
6. Predict plant diseases from input leaf images.

---

## Applications

- Smart Agriculture
- Precision Farming
- Early Disease Detection
- Crop Monitoring Systems

---

## Future Improvements

- Mobile application integration
- Real-time disease detection using a camera
- IoT-based field monitoring
- Cloud deployment for farmers

---

## Repository Structure

```
Plant-Disease-Prediction/
│
├── PDP.ipynb
├── README.md
├── requirements.txt
└── sample_images/
```

---

## Author

Developed by **SASI REKHA C**

Electronics and Communication Engineering (ECE)  
SSN College of Engineering, Chennai

---

## Skills Demonstrated

- Deep Learning
- Transfer Learning
- Computer Vision
- Image Classification
- TensorFlow and Keras
- Data Preprocessing
- Model Training and Evaluation
- Python Programming
