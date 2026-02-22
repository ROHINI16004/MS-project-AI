# 📰 Fake News Detection using Machine Learning

A Machine Learning project that detects whether a news article is **Fake News** or **Not Fake News** using Natural Language Processing (NLP) and classification algorithms.

---

## 🚀 Project Overview

This project uses:

- Text preprocessing techniques
- TF-IDF Vectorization
- Multiple Machine Learning models

The system classifies news articles as:

- 🟥 Fake News
- 🟩 Not Fake News

---

## 🛠 Technologies Used

- Python 3
- Pandas
- NumPy
- Scikit-learn
- Regular Expressions (re)

---

## 📊 Machine Learning Models Implemented

1. Logistic Regression
2. Decision Tree Classifier
3. Gradient Boosting Classifier
4. Random Forest Classifier

---

## 📂 Dataset

The dataset consists of two CSV files:

- `fake1.csv` → Fake news articles
- `true1.csv` → Real news articles

Each dataset contains:
- Title
- Text
- Subject
- Date

---

## ⚙️ How It Works

### 1️⃣ Data Loading
- Loads fake and real news datasets.
- Handles encoding issues and malformed rows.

### 2️⃣ Data Preprocessing
- Converts text to lowercase
- Removes punctuation
- Removes numbers
- Removes special characters
- Cleans unwanted tokens

### 3️⃣ Feature Extraction
- Converts text into numerical form using **TF-IDF Vectorization**

### 4️⃣ Model Training
- Trains four ML classification models

### 5️⃣ Model Evaluation
- Calculates accuracy for each model

### 6️⃣ Prediction
- Accepts a news sentence
- Outputs prediction from all models

---

## 📈 Example Output
