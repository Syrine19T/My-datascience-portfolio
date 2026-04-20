
# 📧 Email Spam Detection

## 📌 Project Overview

This project aims to build a machine learning system that can automatically classify emails as **Spam or Not Spam (Ham)** using text classification techniques.
Multiple models were trained and evaluated to select the best-performing one.

---

## 📊 Dataset

The dataset contains labeled email messages classified as:

* **Spam**
* **Not Spam (Ham)**

---

## 🧹 Data Preprocessing

The following preprocessing steps were applied to clean and prepare the text data:

* Removed special characters and punctuation
* Cleaned and normalized text data
* Converted labels:

  * Spam → 1
  * Not Spam → 0

---

## 🔀 Data Splitting

The dataset was split into:

* **Training set**
* **Testing set**

---

## 🔤 Feature Engineering

Text data was transformed into numerical format using:

* **TF-IDF Vectorization**

---

## 🤖 Machine Learning Models

Several classification models were trained and compared:

* Support Vector Machine (SVM)
* Logistic Regression
* Random Forest
* Multinomial Naive Bayes
* Gradient Boosting

---

## 🔧 Hyperparameter Tuning

* Used **GridSearchCV** to optimize model parameters
* Evaluated models using cross-validation

---

## 📈 Model Evaluation

Models were evaluated using:

* Mean Cross-Validation Score
* Test Accuracy
* Classification Report (Precision, Recall, F1-score)
* Confusion Matrix

---

## 🏆 Best Model

The best-performing model was:

👉 **Support Vector Machine (SVM)**

It achieved the highest performance on the test set compared to other models.

---

## 🛠️ Technologies Used

* Python 🐍
* Pandas
* NumPy
* Scikit-learn
* NLTK
* Matplotlib / Seaborn

---

## 📊 Results Summary

The SVM model showed the best balance between accuracy and generalization, making it the most suitable model for spam detection in this project.

---

