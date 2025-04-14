# Waste-Segregation-System-Using-Image-Classification

This project presents an automated waste segregation system using image classification models. The objective is to classify waste into appropriate categories such as **organic**, **recyclable**, and **hazardous**, supporting cleaner and more sustainable waste management through robotics and AI.

---

## Project Overview

Effective waste segregation plays a vital role in promoting environmental sustainability and efficient recycling processes. This system uses image classification to identify different waste types, which can then be physically segregated through robotic mechanisms. The project compares multiple machine learning and deep learning approaches to determine the most suitable model for real-time waste classification.

---

## Dataset

- **Dataset Used**: Waste Segregation Image Dataset
- **Categories**: Organic, Recyclable, Hazardous
- **Preprocessing**: Images were resized, normalized, and split into training and testing sets.

---

## Included Notebooks

This repository contains implementations and experiments using the following models:

- `cnn_model.ipynb` — Custom Convolutional Neural Network (CNN)
- `svm_model.ipynb` — Support Vector Machine (SVM)
- `vgg16_model.ipynb` — VGG16 using Transfer Learning

Each notebook includes:
- Data loading and preprocessing
- Model architecture and training
- Evaluation metrics and visualizations

---

## Results Summary

| Model    | Performance | Remarks |
|----------|-------------|---------|
| CNN      | High        | Good baseline performance with tuned parameters |
| SVM      | Moderate    | Simpler and faster but lower accuracy |
| VGG16    | Highest     | Best generalization and feature extraction due to transfer learning |

---

## Tech Stack

- Python
- TensorFlow / Keras
- Scikit-learn
- OpenCV
- NumPy & Matplotlib
- Jupyter Notebook / Google Colab

---
