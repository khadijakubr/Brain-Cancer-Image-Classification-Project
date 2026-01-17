# Brain Cancer Image Classification Project

This project is a **Brain Cancer Image Classification** model developed as part of a **Dicoding Deep Learning** class. The main objective of this project is to build a deep learning model capable of classifying medical images related to brain cancer using image-based classification techniques.

The trained model is exported into multiple formats to support different deployment environments:
- **TensorFlow SavedModel**
- **TensorFlow Lite (TFLite)** for mobile or edge devices
- **TensorFlow.js (TFJS)** for web-based applications

---

## 📂 Dataset

The dataset used in this project was obtained from **Kaggle**:

- **Dataset Name:** Multi Cancer Dataset  
- **Author:** Obuli Sai Naren  
- **Year:** 2022  
- **Source:** Kaggle  
- **Link:** https://www.kaggle.com/datasets/obulisainaren/multi-cancer  
- **Citation:**  
  > Obuli Sai Naren. (2022). *Multi Cancer Dataset* [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/3415848

This dataset contains medical images from multiple cancer types and was processed specifically for brain cancer image classification in this project.

---

## ✨ Features

- Image preprocessing and data augmentation
- Convolutional Neural Network (CNN)-based classification
- Model training and evaluation
- Model export in multiple deployment-ready formats
- Ready-to-use for inference and further development

---

## 🧠 Model Structure

This repository includes:
- **Jupyter Notebook** (`proyek-klasifikasi-gambar-brain-cancer.ipynb`) containing data preprocessing, training, and evaluation steps
- **Saved models** in different formats:
  - `saved_model/` — TensorFlow SavedModel format
  - `tflite/` — TensorFlow Lite model
  - `tfjs_model/` — TensorFlow.js model for web deployment
- **requirements.txt** — list of required Python dependencies

---

## 📊 Methodology
The model was trained using deep learning techniques with a Convolutional Neural Network (CNN). The training pipeline includes:
- Image resizing and normalization
- Train-validation data split
- Data augmentation
- Model training and performance evaluation

---

## 📄 License
This project is intended for educational purposes.
You may add an appropriate license (e.g., MIT License) if you plan to reuse or distribute this project.
