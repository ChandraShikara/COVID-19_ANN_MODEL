# 🦠 COVID-19 Prediction using Artificial Neural Networks (ANN)

This project applies **Artificial Neural Networks (ANN)** to predict COVID-19 cases and understand key patterns in the spread and severity of the virus.  
It demonstrates how machine learning models can support data-driven public health decision-making.

---

## 📘 Project Overview

The **COVID-19 Prediction Model** is designed to analyze and forecast infection trends using real-world datasets.  
By leveraging **ANNs**, the model learns from global COVID-19 data such as:
- Confirmed cases  
- Deaths  
- Recoveries  
- Geographical and temporal data  

This helps identify patterns and predict potential outbreak trends.

---

## 📊 Dataset

The dataset used for this project is available on **Kaggle**:  
👉 [COVID-19 Dataset – Global Forecasting (Kaggle)](https://www.kaggle.com/datasets/meirnizri/covid19-dataset)

This dataset includes:
- Daily level data of confirmed, death, and recovered cases  
- Country and province information  
- Time series format for temporal analysis  

---

## 🧠 Model Architecture

The project implements an **Artificial Neural Network (ANN)** built using **TensorFlow** and **Keras**, consisting of:

- Input Layer (features such as cases, deaths, recoveries)  
- Hidden Layers (Dense layers with ReLU activation)  
- Output Layer (predicting confirmed/death/recovery trends)  

The model is optimized using:
- **Adam Optimizer**
- **Mean Squared Error (MSE)** loss function

---

## ⚙️ Tech Stack

- **Python**
- **NumPy**, **Pandas**
- **Matplotlib**, **Seaborn**
- **TensorFlow**, **Keras**
- **Scikit-learn**
- **Jupyter Notebook**

---

## 🧩 Steps to Run Locally

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/COVID19_Prediction_ANN.git
   cd COVID19_Prediction_ANN
2. pip install -r requirements.txt
3. Download the dataset from the link
4. jupyter notebook ANN_COVID_DATA.ipynb

