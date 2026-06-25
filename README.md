# 🌿 Plant Disease Detection using PyTorch

A Deep Learning-based image classification system that automatically detects and classifies plant diseases from leaf images using **Convolutional Neural Networks (CNN)** and **PyTorch**. This project aims to assist farmers and researchers by enabling fast, accurate, and automated disease diagnosis for improved crop management.

---

# Table of Contents

* Project Overview
* Problem Statement
* Features
* Dataset
* Technologies Used
* Project Workflow
* Model Architecture
* Results
* Project Structure
* Installation
* Usage
* Future Enhancements
* Author

---

# Project Overview

Agriculture is one of the most important sectors worldwide, and plant diseases are a major cause of reduced crop production. Traditional disease identification requires expert knowledge and manual inspection, which is often slow and expensive.

This project applies **Deep Learning** and **Computer Vision** techniques to classify plant diseases directly from leaf images. A Convolutional Neural Network (CNN) built using **PyTorch** learns disease patterns from thousands of training images and predicts the correct disease class for new leaf images.

---

# Problem Statement

Plant diseases can spread rapidly and cause significant crop damage if not detected early. Farmers often struggle to identify diseases accurately, especially in remote areas where agricultural experts are unavailable.

The objective of this project is to build an intelligent image classification system that can:

* Detect plant diseases automatically.
* Classify leaf images into multiple disease categories.
* Reduce manual inspection.
* Support early disease diagnosis.
* Improve agricultural productivity.

---

# Features

* Automatic Plant Disease Detection
* Deep Learning-based Image Classification
* CNN Model built using PyTorch
* Image Preprocessing and Augmentation
* Training and Validation Pipeline
* High Accuracy Disease Prediction
* Easy to Extend for New Disease Classes

---

# Dataset

The model is trained using a plant disease image dataset containing healthy and diseased plant leaves.

### Dataset Characteristics

* Healthy leaf images
* Diseased leaf images
* Multiple plant species
* Multiple disease categories
* RGB Images
* Training Dataset
* Validation Dataset
* Test Dataset

### Dataset Structure

```text
Dataset/
│
├── train/
│   ├── Healthy/
│   ├── Bacterial_Spot/
│   ├── Early_Blight/
│   ├── Late_Blight/
│   └── ...
│
├── valid/
│   ├── Healthy/
│   ├── Bacterial_Spot/
│   ├── Early_Blight/
│   ├── Late_Blight/
│   └── ...
│
└── test/
    ├── image1.jpg
    ├── image2.jpg
    └── image3.jpg
```

---

# Technologies Used

| Technology       | Purpose                   |
| ---------------- | ------------------------- |
| Python           | Programming Language      |
| PyTorch          | Deep Learning Framework   |
| Torchvision      | Dataset Handling          |
| NumPy            | Numerical Computing       |
| Pandas           | Data Processing           |
| Matplotlib       | Data Visualization        |
| Seaborn          | Statistical Visualization |
| Jupyter Notebook | Development Environment   |
| CNN              | Image Classification      |

---

# Project Workflow

### Step 1 — Data Collection

* Collect plant leaf images
* Organize dataset into folders

### Step 2 — Data Preprocessing

* Image Resizing
* Tensor Conversion
* Data Normalization
* Data Augmentation
* Data Loading using DataLoader

### Step 3 — Data Visualization

* Sample Images
* Disease Distribution
* Class Analysis

### Step 4 — Model Development

The CNN model consists of:

* Input Layer
* Convolution Layer
* ReLU Activation
* Max Pooling
* Fully Connected Layer
* Softmax Output Layer

### Step 5 — Model Training

* Forward Propagation
* Loss Calculation
* Backpropagation
* Weight Optimization
* Epoch-wise Training

### Step 6 — Model Evaluation

Evaluation Metrics:

* Training Accuracy
* Validation Accuracy
* Training Loss
* Validation Loss

### Step 7 — Prediction

The trained model predicts the disease category for unseen plant leaf images.

---

# Model Architecture

```text
Input Image
      │
      ▼
Convolution Layer
      │
      ▼
ReLU Activation
      │
      ▼
Max Pooling
      │
      ▼
Convolution Layer
      │
      ▼
Fully Connected Layer
      │
      ▼
Softmax
      │
      ▼
Predicted Disease Class
```

---

# Results

The trained model is capable of:

* Detecting plant diseases accurately.
* Classifying multiple disease categories.
* Predicting healthy and diseased leaves.
* Learning complex visual patterns automatically.
* Supporting early disease diagnosis.

---

# Project Structure

```text
Plant-Disease-Detection/
│
├── Dataset/
├── Models/
├── notebooks/
├── plant-diseases-detection-pytorch.ipynb
├── requirements.txt
├── README.md
└── LICENSE
```

---

# Installation

Clone the repository

```bash
git clone https://github.com/your-username/Plant-Disease-Detection-PyTorch.git
```

Go inside the project

```bash
cd Plant-Disease-Detection-PyTorch
```

Install required libraries

```bash
pip install torch torchvision numpy pandas matplotlib seaborn jupyter
```

---

# Usage

Launch Jupyter Notebook

```bash
jupyter notebook
```

Open

```text
plant-diseases-detection-pytorch.ipynb
```

Run all notebook cells sequentially to:

* Load Dataset
* Preprocess Images
* Train CNN Model
* Evaluate Performance
* Predict Plant Diseases

---

# Future Enhancements

* Real-time Camera Detection
* Streamlit Web Application
* Flask Deployment
* Mobile Application
* Cloud Deployment
* Disease Treatment Recommendation
* IoT Integration for Smart Farming

---

# Author

**Arif Ansari**

B.Tech – Artificial Intelligence & Machine Learning (AIML)

2026 Passout

Department of Artificial Intelligence and Machine Learning



 Author
 Arif Ansari  
 B.Tech – Artificial Intelligence & Machine Learning (AIML)  
 2026 Passout
