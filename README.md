# 🛒 Shopping Project (CS50 AI)

This project is part of Harvard’s **CS50 Introduction to Artificial Intelligence with Python**. It implements a **k-nearest neighbors (k=1) classifier** to predict whether an online shopping session will result in a purchase.

---

## 📖 Overview
- **Goal**: Use session data to predict customer behavior (purchase or not).
- **Data**: Preprocessed from `shopping.csv` (17 features like page visits, durations, bounce rate, month, visitor type, weekend, etc.).
- **Model**: Trains a **k-NN classifier** (`k=1`) using scikit-learn.
- **Evaluation**: Reports overall accuracy and:
  - **Sensitivity (True Positive Rate)** → How well the model identifies buyers.
  - **Specificity (True Negative Rate)** → How well the model identifies non-buyers.

---

## ⚙️ Installation
Make sure you have **Python 3** installed, then install dependencies:
```bash
pip install scikit-learn
```

---

## 🚀 Usage
1. Save the project files (`shopping.py` and `shopping.csv`) in the same folder.
2. Run the program from the terminal:
   ```bash
   python shopping.py shopping.csv
   ```

---

## 📊 Example Output
```
Correct: 4325
Incorrect: 1592
True Positive Rate: 46.55%
True Negative Rate: 89.33%
```
*(Results may vary depending on the train/test split)*

---

## 🧠 Concepts Learned
- Data preprocessing and feature engineering
- Converting categorical values into numerical format
- Training and testing machine learning models
- Evaluating model performance with sensitivity and specificity

---

## 📂 Files
- **shopping.py** → Main program (data loading, training, evaluation)
- **shopping.csv** → Dataset provided by CS50

---

✅ This project demonstrates applying **machine learning** to real-world e-commerce data using **k-nearest neighbors classification**.
