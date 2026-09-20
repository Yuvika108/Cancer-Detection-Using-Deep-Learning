# 🧠 Cancer Detection Using Deep Learning

A deep-learning project focused on **brain tumor detection from MRI images** using the [Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset).

The current version of the project sets up the dataset automatically using `kagglehub`, providing the foundation for building and training an image-classification model for brain tumor detection.

## 📌 Project Overview

Brain tumors can be detected and classified from MRI scans using computer vision and deep learning techniques.

This project starts with obtaining a structured MRI dataset that can be used to develop a deep-learning classification pipeline.

### Current Workflow

```text
Kaggle Brain Tumor MRI Dataset
            ↓
      Dataset Download
            ↓
      Local Dataset Path
            ↓
   Deep Learning Pipeline
       (Next Phase)
```

## ✨ Current Features

* 📥 Automatic dataset download using `kagglehub`
* 🧠 Brain tumor MRI dataset integration
* 🐍 Python-based implementation
* 🔬 Foundation for deep-learning image classification

## 🛠️ Tech Stack

* **Python**
* **KaggleHub**
* **Deep Learning** — planned model-development stage
* **Computer Vision** — MRI image classification

## 📂 Project Structure

```text
Cancer-Detection-Using-Deep-Learning/
│
├── Cancer Detection Using Deep Learning.py
└── README.md
```

## 🚀 Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/Yuvika108/Cancer-Detection-Using-Deep-Learning.git
cd Cancer-Detection-Using-Deep-Learning
```

### 2. Install Dependencies

Install KaggleHub:

```bash
pip install kagglehub
```

### 3. Run the Script

```bash
python "Cancer Detection Using Deep Learning.py"
```

The script downloads the latest version of the Brain Tumor MRI Dataset and prints the path where the dataset is stored.

## 📊 Dataset

The project uses the **Brain Tumor MRI Dataset** available on Kaggle.

The dataset contains MRI images organized into multiple brain-tumor categories and can be used for image classification tasks.

Dataset source:

[Kaggle — Brain Tumor MRI Dataset](https://www.kaggle.com/datasets/masoudnickparvar/brain-tumor-mri-dataset)

## 🔮 Planned Development

The project can be extended into a complete end-to-end deep-learning system with:

* Image preprocessing and normalization
* Training/validation/test split
* CNN-based tumor classification
* Transfer learning using architectures such as ResNet, EfficientNet or VGG
* Data augmentation
* Model evaluation
* Accuracy, precision, recall and F1-score
* Confusion matrix
* MRI image prediction
* Model saving and loading
* Streamlit-based prediction interface

## 🎯 Goal

The goal is to develop a computer-vision system capable of **classifying brain MRI images using deep learning**, providing a foundation for automated medical-image analysis.

> **Note:** This project is intended for educational and research purposes. It is not a medical diagnostic system and should not be used for clinical decision-making.

## 👩‍💻 Author

**Yuvika108**

GitHub: https://github.com/Yuvika108
