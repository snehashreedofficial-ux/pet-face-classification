# Pet Face Classification using Deep Learning

A deep learning project that uses **TensorFlow, Keras, and ResNet50 transfer learning** to classify pet face images.

## Project Overview

This project applies a pretrained ResNet50 convolutional neural network (CNN) to image classification. The model uses ImageNet pretrained weights, data augmentation, and a custom classification head to learn visual features and classify pet face images.

## Technologies Used

- Python
- TensorFlow
- Keras
- ResNet50
- Deep Learning
- Transfer Learning
- Image Classification
- Data Augmentation

## Model Architecture

- **Base model:** ResNet50 pretrained on ImageNet
- **Approach:** Transfer learning
- **Training enhancement:** Data augmentation
- **Classification head:** Custom neural network layers

## Results

- **Test accuracy:** 89.58%
- **Validation accuracy:** 89.92% reached during training

These results are from the model's recorded evaluation and training history.

## Project File

- `Pet_Classification.ipynb` — Jupyter Notebook containing the project code and workflow.

## How to Run

1. Download or clone this repository.
2. Open `Pet_Classification.ipynb` in Jupyter Notebook or Google Colab.
3. Install the required dependencies if they are not already available.
4. Follow the notebook cells in order.

**Note:** The dataset used by the notebook must be available in the expected location for the code to run successfully.

## Learning Outcomes

- Understanding transfer learning with pretrained CNN models.
- Applying data augmentation to image classification.
- Training and evaluating a deep learning model.
- Interpreting validation and test accuracy.

---

**Author:** Snehashree De
