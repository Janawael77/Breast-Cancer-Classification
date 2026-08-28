# 🎗️ Breast Cancer Classification Model

## 📌 Project Overview
This project focuses on building a Machine Learning classification model to predict whether a breast tumor is **Malignant** or **Benign** based on medical diagnostic measurements.

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries Used:**
  - `pandas` & `numpy` for data manipulation
  - `matplotlib` & `seaborn` for data visualization
  - `scikit-learn` for data scaling, model building, and evaluation

## ⚙️ Workflow & Steps
1. **Data Preprocessing & Scaling:** Standardized features using `StandardScaler` to bring all values to a uniform scale.
2. **Model Training:** Trained a **Random Forest Classifier** on the dataset.
3. **Model Evaluation:** Evaluated accuracy, precision, recall, and confusion matrix metrics.
4. **Model Export:** Saved the trained model (`breast_cancer_model.pkl`) and scaler (`scaler.pkl`) for deployment.

## 📁 Repository Structure
- `Untitled0 (2).ipynb`: Jupyter notebook containing full EDA, training, and evaluation code.
- `breast_cancer_model.pkl`: Serialized Random Forest machine learning model.
- `scaler.pkl`: Fitted StandardScaler instance for input preprocessing.
- `README.md`: Project description and guidelines.
