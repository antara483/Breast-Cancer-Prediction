# 🩺 Breast Cancer Prediction

A machine learning project to predict whether a breast tumor is **benign (0)** or **malignant (1)** using the Breast Cancer Wisconsin Dataset. This project demonstrates the complete machine learning pipeline from data preprocessing to model evaluation and visualization.

## 🛠 Tech Stack

- **Python**
- **NumPy & Pandas** (Data manipulation)
- **Matplotlib & Seaborn** (Visualization)
- **Scikit-learn** (Machine Learning)
  
## 📋 Project Overview

This project implements and compares machine learning models for breast cancer classification, providing insights into model performance, feature importance, and prediction probabilities.

## 🚀 What I Did

### Data Preprocessing
- **🧹 Data Cleaning**: Removed unnecessary columns and handled missing values
- **🔢 Target Encoding**: Converted categorical labels (B → 0, M → 1)
- **⚖️ Feature Scaling**: Standardized features using `StandardScaler`

### Model Development
- **🤖 Algorithm Selection**: Trained Logistic Regression and Random Forest models
- **🔍 Hyperparameter Tuning**: Optimized Logistic Regression using `GridSearchCV`
- **📈 Model Evaluation**: Comprehensive performance assessment

### Analysis & Visualization
- **📊 ROC Curve**: Visualized model discrimination capability
- **🧮 Confusion Matrix**: Analyzed classification performance
- **📈 Feature Coefficients**: Explored feature importance in Logistic Regression
- **📉 Sigmoid Function**: Visualized probability mapping

## 📊 Key Results

- **Logistic Regression** achieved high ROC-AUC score
- **Random Forest** provided comparable performance
- **Threshold Analysis**: Experimented with different probability thresholds to optimize trade-offs between sensitivity and specificity

## 🧩 Highlights

- **Visualization Suite**: Comprehensive plots including ROC Curve and Confusion Matrix
- **Model Comparison**: Performance analysis across different algorithms
- **Probability Understanding**: Deep dive into how the Sigmoid Function maps linear outputs to probabilities
- **Practical Insights**: Understanding prediction trade-offs through threshold analysis

