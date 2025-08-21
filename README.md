# Age Detection on IMDB-WIKI  

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)         
[![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green)](https://opencv.org/)               
[![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)](https://keras.io/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

> Predicting human age from faces using a CNN model.

---

## 📌 Overview  
This project is a **Convolutional Neural Network (CNN)** built to predict ages using the **IMDB-WIKI dataset** — one of the largest publicly available datasets of human faces with age labels.  

---

## 📂 Repository Structure

```

real-time-senior-citizen-identifier/
├── notebooks/
│ ├── age_detection.ipynb (model training file)
│ └── evaluation.ipynb
│
├── model/
│ └── imdb_wiki_age_detection_model.keras
│
├── results/
│ ├── Actual_vs_Predicted.png
│ └── Visualization.ipynb (outputs)
│
├── evaluation/
│ ├── Accuracy.png
│ ├── Classification Report.png
│ ├── Confusion Matrix.png
│ ├── Evaluation Metrics.png
│ ├── Residual Histogram.png
│ └── Scatter plot.png
│
├── requirements.txt
└── README.md

```
---

## 🚀 Features  
- 📂 Large dataset (3,00,000+ images)
- 🧮 CNN architecture optimized for regression
- 🧠 Built using pre-trained model (MobileNetV3)  
- 📊 Achieved **MAE ~4–5** on test data   
- ⚡ Google Colab + GPU ready  

---

## 📂 Dataset  
- **Source:** [IMDB-WIKI Dataset](https://www.kaggle.com/datasets/abhikjha/imdb-wiki-faces-dataset)  
- **Format Used:** Pre-cropped faces in folders (`00`–`99`) + `.mat` metadata  

---

## 📜 How It Works  

**Dataset Preparation** → IMDB-WIKI dataset cleaned & preprocessed (faces resized to 128×128, normalized)  
**Data Pipeline** → Image data generators handle batching, shuffling & augmentation  
**Training Setup** → Model trained with Adam optimizer, MSE loss & MAE as evaluation metric  
**Learning Process** → Trained in batches of 32, with checkpointing & early stopping.

---

## 🖼 Example Predictions  
![visuals](/results/Actual_vs_Predicted.png)

---

## 📈 Results  
<p align="center">MAE : 4.78</p>

<p align="center">
  <img src="/evaluation/MAE.png" alt="mae" width="800"/>
</p>
