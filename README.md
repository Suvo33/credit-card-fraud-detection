# 💳 Credit Card Fraud Detection using Machine Learning

This project focuses on detecting fraudulent credit card transactions using supervised machine learning techniques. The original dataset is highly imbalanced, with a small percentage of fraudulent cases, which is addressed using under-sampling techniques.

---

## 📌 Project Overview

- **Objective**: To build a machine learning model that can accurately classify transactions as normal or fraudulent.
- **Dataset**: A CSV file containing credit card transaction data with labeled outcomes (`0` for normal, `1` for fraud).
- **Challenge**: The dataset is highly imbalanced, leading to biased model performance if not handled correctly.

---

## 🧰 Features

- Exploratory Data Analysis
- Handling class imbalance with under-sampling
- Model training using Logistic Regression
- Evaluation using accuracy and other metrics

---

## 🧪 Technologies Used

- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- streamlit

---

## 📁 Dataset

- Filename: `creditcard.csv`
- Features: Includes anonymized features `V1` to `V28`, `Amount`, `Time`, and `Class`
- Class Distribution:  
  - `0` → Normal transactions  
  - `1` → Fraudulent transactions

---

## 🚀 How to Run the Project

### 1. Clone the Repository

```bash
git clone https://github.com/Suvo33/credit-card-fraud-detection.git
cd credit-card-fraud-detection
```

### 2. Install Dependencies

Make sure you have Python and Jupyter installed. You can set up a virtual environment and install required libraries:

```bash
pip install -r requirements.txt
```

Or manually install:

```bash
pip install numpy pandas matplotlib seaborn scikit-learn jupyter streamlit
```

### 3. Run the Notebook

Launch Jupyter Notebook:

```bash
jupyter notebook model.ipynb
```

Open the notebook and execute the cells in order.

---add

## ✅ Output

- Displays evaluation metrics like accuracy
- Visualizes correlation and class distribution
- Demonstrates model performance before and after hyperparameter tuning


