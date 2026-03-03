# 💎 Diamond Price Prediction

This project builds a Deep Learning model to predict diamond prices using the famous Seaborn Diamonds dataset.

The goal of this project was to practice a complete ML workflow including preprocessing, training, evaluation, and visualization.

---

# 📊 Dataset

Dataset: Seaborn Diamonds Dataset

Features:

- carat – weight of the diamond
- cut – quality of the cut
- color – diamond color grade
- clarity – clarity grade
- depth – total depth percentage
- table – width of top of diamond
- x – length in mm
- y – width in mm
- z – depth in mm

Target:

price

---

# ⚙️ Tech Stack

Python  
Pandas  
NumPy  
Scikit-learn  
TensorFlow / Keras  
Matplotlib  
Seaborn  

---

# 🚀 Project Workflow

## 1. Data Preprocessing

- Checked missing values
- Encoded categorical variables
- Train Test Split
- Feature Scaling using StandardScaler

## 2. Model Building

A Deep Learning Regression model was built using TensorFlow/Keras.

Example Architecture

Input Layer  
Dense Layer (ReLU)  
Dense Layer (ReLU)  
Output Layer  

Loss Function:
Mean Squared Error

Optimizer:
Adam

---

# ⏹ Early Stopping

Early stopping was used to avoid overfitting.

Training stops automatically when validation loss stops improving.

---

# 📈 Model Evaluation

Metrics used:

MAE (Mean Absolute Error)  
MSE (Mean Squared Error)  
R² Score  

Example Result

MAE  : ~336  
MSE  : ~378511  
R²   : ~0.97  

This means the model explains about **97% of the variance** in diamond prices.

---

# 📚 What I Learned

- Data preprocessing
- Feature scaling
- Neural network regression
- Early stopping
- Model evaluation metrics
- ML workflow

