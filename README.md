# Image_Classification_CNN
This project showcases Convolutional Neural Networks (CNNs) for image classification using TensorFlow/Keras. It covers data preprocessing for Fashion-MNIST and CIFAR-100, building two CNN models, comprehensive training, evaluation with classification reports and confusion matrices, and hyperparameter tuning for optimal performance.

# Convolutional Neural Network (CNN) for Image Classification

This repository contains a Google Colab notebook demonstrating the application of Convolutional Neural Networks (CNNs) for image classification. The project focuses on two distinct datasets: Fashion-MNIST (grayscale, 10 classes) and CIFAR-100 (RGB, 100 classes), utilizing the TensorFlow/Keras framework.

## Project Overview

The notebook guides through the complete machine learning workflow for image classification with CNNs, including:

1.  **Data Loading & Preprocessing**: Efficient loading, normalization, and splitting of the Fashion-MNIST and CIFAR-100 datasets into training, validation, and testing sets.
2.  **CNN Model Architecture**: Design and implementation of two specialized CNN models—a simpler architecture for Fashion-MNIST and a deeper, more complex one for CIFAR-100 to handle its higher classification complexity.
3.  **Model Training**: Compilation and training of both CNN models, incorporating best practices such as `Adam` optimizer, `sparse_categorical_crossentropy` loss, and callbacks like `ReduceLROnPlateau` and `EarlyStopping` for optimized learning.
4.  **Performance Evaluation**: Comprehensive assessment of model performance using test accuracy, loss, detailed classification reports (precision, recall, F1-score), and visual confusion matrices for insights into classification errors.
5.  **Hyperparameter Tuning**: An experimental section dedicated to exploring the impact of different learning rates, batch sizes, and dropout rates on the Fashion-MNIST model's performance, providing a comparative analysis of various configurations.

## Key Features

*   **Two Datasets**: Demonstrates CNNs on both grayscale (Fashion-MNIST) and color (CIFAR-100) image datasets.
*   **Custom CNN Architectures**: Illustrates how to build sequential CNN models with convolutional layers, batch normalization, max-pooling, and dropout.
*   **Training Visualizations**: Plots of training and validation loss/accuracy curves to monitor model learning.
*   **Evaluation Metrics**: Utilizes `classification_report` and `confusion_matrix` for in-depth model performance analysis.
*   **Hyperparameter Experimentation**: Provides a systematic approach to tuning key hyperparameters and visualizing their effects on validation accuracy.

## Setup and Usage

1.  **Open in Google Colab**: Click the "Open in Colab" badge or upload the `.ipynb` file to your Google Drive and open it with Colab.
2.  **Run Cells**: Execute the cells sequentially. The notebook will automatically download the required datasets and install any necessary libraries.
3.  **Explore Results**: Review the generated plots for training history, confusion matrices, and hyperparameter tuning outcomes.

## Visualizations

The notebook generates several plots, including:

*   Sample images from Fashion-MNIST and CIFAR-100.
*   Training and validation loss/accuracy plots for both models.
*   Confusion matrix for the Fashion-MNIST model.
*   Bar chart summarizing the results of hyperparameter tuning experiments.

## Technologies Used

*   Python
*   TensorFlow / Keras
*   NumPy
*   Matplotlib
*   Seaborn
*   Scikit-learn

```
