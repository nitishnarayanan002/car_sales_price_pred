# 🚗 Car Purchase Amount Prediction using Artificial Neural Network (ANN)

Note- This is done to practice ANN (may be it can be improved more) 

This project builds a regression model using an Artificial Neural Network (ANN) to **predict the amount a customer is likely to spend on a vehicle** based on personal and financial features.

---

## 📌 Problem Statement

> As a vehicle salesperson, you would like to estimate the overall amount that consumers would spend given the following characteristics:
>
> - Customer Name
> - Customer Email
> - Country
> - Gender
> - Age
> - Annual Salary
> - Credit Card Debt
> - Net Worth

Our goal is to create a predictive model that takes in these features and outputs an estimated car purchase amount.

---

## 🧠 Model Architecture

- Input Layer: 216 features (after preprocessing)
- Hidden Layer 1: Dense(64 neurons, ReLU)
- Hidden Layer 2: Dense(32 neurons, ReLU)
- Output Layer: Dense(1 neuron, Linear)

**Loss Function:** Mean Squared Error (MSE)  
**Optimizer:** Adam  
**Evaluation Metric:** Mean Absolute Error (MAE)

---

## 📉 Model Performance

- ✅ MAE: ~₹24,792  
- ✅ Test MSE: ~709 million  
- ✅ Validation loss decreases steadily — no overfitting observed  
- ✅ Stable and smooth training curve

<p align="center">
  <img src="path_to_your_training_loss_plot.png" width="400" alt="Training vs Validation Loss">
</p>

---

## 🔧 Preprocessing Steps

- Dropped: `Customer Name`, `Customer Email`, `Country` (non-numeric or irrelevant to prediction)
- Converted `Gender` to binary (already pre-encoded)
- Scaled numerical features using `StandardScaler`
- Train-test split: 80-20

---

## 🛠️ Tech Stack

- Python
- TensorFlow / Keras
- NumPy, Pandas, Matplotlib
- Google Colab

---
## Contact 

- Email - nitishnarayanan002@gmail.com
- Linkedin - https://www.linkedin.com/in/nitish-narayanan/
- Github - https://github.com/nitishnarayanan002
