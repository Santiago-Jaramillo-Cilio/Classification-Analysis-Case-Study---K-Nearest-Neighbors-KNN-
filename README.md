# Classification-Analysis-Case-Study

# Heart Disease Prediction Using K-Nearest Neighbors (KNN)

## 📌 Project Overview
This repository provides a Google Colab notebook that implements the **K-Nearest Neighbors (KNN)** algorithm to predict heart disease risk. The dataset consists of patient medical records, including vital signs, cholesterol levels, and ECG results. The goal is to classify patients into **low risk (0)** or **high risk (1)** categories based on medical attributes.

## 📂 Contents
- 📄 **Heart_Disease_Prediction_KNN.ipynb** – Jupyter Notebook containing the full implementation.
- 📊 **heart_disease_dataset.csv** – The dataset used for training and testing.
- 📘 **README.md** – Project documentation (this file!).

## 📊 Dataset Description
The dataset contains key patient health features:

- **Demographics:** Age, Sex
- **Vital Signs:** Resting Blood Pressure, Cholesterol Levels
- **Symptoms & Tests:** Chest Pain Type, ECG Results
- **Exercise Data:** Maximum Heart Rate, Exercise-Induced Angina
- **Target Variable:**
  - `0` – Low Risk
  - `1` – High Risk

## 📝 Objective
Develop a predictive model that determines whether a patient is at **high risk (1)** or **low risk (0)** for heart disease based on medical attributes.

## 🏆 Key Steps in the Notebook

### 🔹 Data Preprocessing
- Handling missing values
- Feature scaling using **StandardScaler**

### 🔹 KNN Model Implementation
- Splitting data into training and testing sets
- Choosing the optimal **K (number of neighbors)**
- Evaluating model performance using **Precision, Recall, and F1-Score**

### 🔹 Model Evaluation
- **Confusion Matrix** – Visualizing model predictions
- **Accuracy Score** – Measuring overall performance

## 📌 Future Improvements
- Hyperparameter tuning for KNN
- Comparison with other models (Logistic Regression, Decision Trees, etc.)
- Feature selection techniques to improve model performance





