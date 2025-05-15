# CAPSTONE-PROJECT
# Plant Disease Detection using CNN

##  Project Objective

This project aims to develop a Convolutional Neural Network (CNN) model capable of accurately identifying plant diseases from leaf images. Early detection of plant diseases is crucial for ensuring crop health and optimizing agricultural productivity. By automating the diagnosis process, this tool can assist farmers and agronomists in making informed decisions promptly.

---

## 📁 Dataset

The dataset used in this project is sourced from **Kaggle**:
- **Source**: [PlantVillage Dataset by abdallahalidev](https://www.kaggle.com/datasets/abdallahalidev/plantvillage-dataset)
- **Description**: The dataset comprises over 50,000 images of healthy and diseased plant leaves across 38 different classes. Each image is labeled with the corresponding plant species and disease status, providing a comprehensive resource for training and evaluating machine learning models.
- It contains thousands of images categorized into multiple classes representing different types of plant diseases and healthy leaves.
- The dataset is divided into training and testing sets, and includes images of various plant species.

---

## ⚙️ Implementation Details

- The project is implemented using **Python** and the **TensorFlow/Keras** deep learning library.
- A **Convolutional Neural Network (CNN)** is built from scratch with several layers:
  - Convolutional + MaxPooling
  - Dropout layers for regularization
  - Fully connected dense layers for final classification
- Image preprocessing and real-time augmentation are done using `ImageDataGenerator`.
- Dataset is downloaded directly via Kaggle API inside the Google Colab environment.
- The images are resized, normalized, and fed into the CNN for training and validation.

---

## 📊 Results and Conclusions

- The CNN model demonstrated strong performance with high accuracy on both the training and testing datasets.
- Training and validation accuracy curves show stable convergence.
- The classification report and confusion matrix confirm that the model can differentiate between healthy and diseased leaves with high precision.
- This project proves the potential of deep learning in plant disease detection and can be extended to mobile or edge devices for real-time use in the field.

---
