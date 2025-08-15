# 🧠 Age Detection — CNN on IMDB-WIKI  

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)  
[![TensorFlow](https://img.shields.io/badge/TensorFlow-2.x-orange)](https://www.tensorflow.org/)  
[![Keras](https://img.shields.io/badge/Keras-Deep%20Learning-red)](https://keras.io/)  
[![Dataset](https://img.shields.io/badge/Dataset-IMDB--WIKI-green)](https://data.vision.ee.ethz.ch/cvl/rrothe/imdb-wiki/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

> Predicting human age from faces using ML models.

---

## 📌 Overview  
This project is a **Convolutional Neural Network (CNN)** built to predict ages using the **IMDB-WIKI dataset** — one of the largest publicly available datasets of human faces with age labels.  

The model is trained and tuned for **low Mean Absolute Error (MAE)**, making it accurate and efficient for real-world use.

---

## 🚀 Features  
- 📂 Works on preprocessed IMDB-WIKI face images  
- 🧮 CNN architecture optimized for regression  
- 📊 Achieved **MAE ~4–5** on test data  
- 🎯 Supports grayscale & RGB  
- ⚡ Google Colab + GPU ready  

---

## 🛠 Tech Stack  
- **Python 3.x**  
- **TensorFlow / Keras**  
- **NumPy, Pandas**  
- **Matplotlib** for visualization  
- **PIL** for image preprocessing  

---

## 📂 Dataset  
- **Source:** [IMDB-WIKI Dataset](https://www.kaggle.com/datasets/abhikjha/imdb-wiki-faces-dataset)  
- **Format Used:** Pre-cropped faces in folders (`00`–`99`) + `.mat` metadata  

---

## 📜 Training Details  
- **Loss Function:** Mean Squared Error (MSE)  
- **Optimizer:** Adam  
- **Metrics:** Mean Absolute Error (MAE)  
- **Batch Size:** 32  
- **Image Size:** 128×128  

---

## 📈 Results  
| Metric | Value |
|--------|-------|
| MAE    | ~4–5  |
| Dataset Size | ~500k images |
| Epochs | 30–50 |

---

## 🖼 Example Predictions  
| Image | True Age | Predicted Age |
|-------|----------|---------------|
| 👩 | 25 | 26 |
| 👨 | 45 | 43 |
| 🧓 | 68 | 70 |

---
path/to/image.jpg
