# Anomaly Detection in Network Data

## Project Overview

This project focuses on detecting network intrusions using both **Supervised** and **Unsupervised Techniques** on the **KDD99 Dataset**. The goal is to identify anomalies and potential threats in network traffic by leveraging various machine learning models. The project explores **Binary Classification** for specific anomaly detection and unsupervised models for broader anomaly detection.

### Key Features

- **Supervised Learning**: Implemented **Binary Classification** with **XGBoost**, achieving an accuracy of **92.48%** for anomaly-specific detection.
- **Unsupervised Learning**:
  - Trained an **Autoencoder** to detect anomalies.
  - Used **Generative Adversarial Networks (GAN)** for anomaly detection, achieving the highest accuracy of **98.64%**.

## Dataset

- The project uses the **KDD99 Dataset**, which is a widely-used dataset for network intrusion detection. It contains both normal and attack traffic, making it ideal for training and evaluating anomaly detection models.

## Models and Techniques

### 1. Supervised Learning

- **Binary Classification with XGBoost**:
  - Built a **Binary Class Classification** model to detect anomalies using **XGBoost**.
  - Achieved an accuracy of **92.48%**, showing promising results for detecting specific network intrusions.

### 2. Unsupervised Learning

- **Autoencoder**:
  - Trained an **Autoencoder** to detect anomalous network traffic by learning to compress and reconstruct normal network behavior. It detects anomalies based on reconstruction errors.
  
- **Generative Adversarial Network (GAN)**:
  - Implemented a **GAN**-based model for anomaly detection.
  - The **GAN** achieved the highest accuracy of **98.64%** in detecting anomalies.

## Results

- **XGBoost Binary Classifier**: 92.48% accuracy in detecting specific anomalies in the network data.
- **GAN Model**: Achieved the best results with **98.64% accuracy** in detecting network anomalies.
- **Autoencoder**: Performed well in detecting anomalies through unsupervised learning, though the GAN outperformed it in this experiment.
