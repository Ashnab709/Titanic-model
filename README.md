# 🚢 Titanic Survival Prediction

Predicting survival on the Titanic using Machine Learning (Logistic Regression).

A beginner-friendly project built with Python, Pandas, and Scikit-learn based on the classic Titanic dataset from Kaggle.

---

## 📌 Overview

This project aims to predict whether a passenger survived the Titanic disaster using features like:

- 🎫 Passenger class
- 👤 Gender
- 🎂 Age
- 👨‍👩‍👧‍👦 Family onboard
- 💰 Fare paid
- 🌍 Port of embarkation

We trained a **Logistic Regression** model and achieved approximately **80% accuracy** on the test set.

---

## 📁 Dataset

📦 Source: [Kaggle Titanic: Machine Learning from Disaster](https://www.kaggle.com/competitions/titanic)

- `train.csv` – used for training and evaluation
- *(Optional)* `test.csv` – for generating Kaggle submissions

---

## 🛠️ Tech Stack

| Tool/Library     | Purpose                      |
|------------------|------------------------------|
| **Python**       | Programming Language         |
| **Pandas**       | Data handling                |
| **NumPy**        | Numerical operations         |
| **Matplotlib**   | Data visualization           |
| **Seaborn**      | Beautiful charts             |
| **Scikit-learn** | ML model and evaluation      |

---

## 🧼 Data Preprocessing

- Dropped irrelevant features: `Cabin`, `Ticket`, `Name`, `PassengerId`
- Filled missing values (`Age` with median, `Embarked` with mode)
- Converted categorical variables to numeric (`Sex`, `Embarked`)
- Selected important features for training

---

## 🧠 Model: Logistic Regression

- **Training split:** 80%  
- **Test split:** 20%

### 📊 Evaluation

- ✅ **Accuracy:** `~80%`
- ✅ Metrics used:
  - Precision, Recall, F1-score
  - Confusion Matrix

---

## 💻 How to Run

### 1. Clone the repo
```bash
git clone https://github.com/yourusername/titanic-survival-prediction.git
cd titanic-survival-prediction

3. Run the notebook
Open the notebook in Jupyter or Google Colab

Upload your train.csv file

Execute each cell step-by-step
