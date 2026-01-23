# ❤️ Heart Disease Prediction

## 📌 Project Overview

Heart Disease Prediction is a **machine learning classification project** that predicts whether a person is likely to have heart disease based on medical attributes. The goal of this project is to build an accurate and reliable predictive model while understanding the complete ML workflow — from data loading to evaluation.

This project is suitable for **academic submissions, viva explanations, and interview discussions**.

---

## 🎯 Problem Statement

Cardiovascular diseases are among the leading causes of death worldwide. Early prediction can help in timely medical intervention. This project uses patient health data to predict the **presence or absence of heart disease**.

---

## 📂 Dataset

* **File name:** `heart_disease_data.csv`
* **Source:** Public heart disease dataset (commonly used in ML education)

### 🔑 Features (example)

* Age
* Sex
* Chest pain type
* Resting blood pressure
* Cholesterol level
* Fasting blood sugar
* Resting ECG results
* Maximum heart rate achieved
* Exercise-induced angina

### 🎯 Target Variable

* `0` → No Heart Disease
* `1` → Heart Disease

---

## 🛠️ Technologies & Libraries Used

* **Python 3**
* **Google Colab / Jupyter Notebook**
* **Pandas** – data handling
* **NumPy** – numerical operations
* **Scikit-learn** – model building & evaluation
* **Matplotlib / Seaborn** – visualization (optional)

---

## ⚙️ Project Workflow

1. Import required libraries
2. Load dataset using Pandas
3. Perform exploratory data analysis (EDA)
4. Handle missing values (if any)
5. Split data into training and testing sets

   * Used `train_test_split`
   * Applied `stratify` to preserve class balance
   * Used `random_state` for reproducibility
6. Train the ML model using `model.fit()`
7. Make predictions on test data
8. Evaluate model performance using accuracy

---

## 🤖 Machine Learning Model

* **Algorithm Used:** Logistic Regression *(can be replaced with other classifiers)*
* **Reason:**

  * Suitable for binary classification
  * Easy to interpret
  * Efficient for medical datasets

---

## 📊 Model Evaluation

* **Metric Used:** Accuracy Score
* **Reason:** Measures how well the model predicts correct outcomes

Example:

```python
accuracy_score(y_test, y_pred)
```

---

## 📁 Project Structure

```
Heart_Disease_Prediction/
│
├── Heart_Disease_Prediction.ipynb
├── heart_disease_data.csv
├── README.md
```

---

## 🚀 How to Run the Project

1. Open the notebook in **Google Colab or Jupyter Notebook**
2. Upload `heart_disease_data.csv`
3. Run all cells sequentially
4. View accuracy and predictions

---

## 🧠 Key Concepts Used

* Train-Test Split
* Stratified Sampling
* Random State (Reproducibility)
* Model Training (`fit`)
* Prediction (`predict`)
* Model Evaluation

---

## 🔮 Future Enhancements

* Use advanced models (Random Forest, SVM, XGBoost)
* Handle class imbalance using SMOTE
* Add ROC-AUC evaluation
* Deploy as a web application

---

## 👤 Author

**Viplav Kumar**
B.Tech CSE, Manipal University Jaipur

---

## 📜 License

This project is for **educational purposes only**.
