# Multiple Disease Prediction System (WebApp)

This repository hosts a **Multiple Disease Prediction Web Application** built with **Streamlit** and deployed on **Streamlit Cloud**. The app integrates four machine learning–based disease prediction systems to provide accurate and reliable predictions.

The diseases covered are:

1. **Diabetes**
2. **Heart Disease**
3. **Parkinson’s Disease**
4. **Breast Cancer**

---

## 📑 Table of Contents

* [Overview](#overview)
* [Installation](#installation)
* [Usage](#usage)
* [Datasets](#datasets)
* [Technologies Used](#technologies-used)
* [Model Development Process](#model-development-process)
* [Models Used](#models-used)
* [Model Evaluation](#model-evaluation)
* [Conclusion](#conclusion)
* [Deployment](#deployment)
* [Contributing](#contributing)
* [Contact](#contact)

---

## 🔎 Overview

The web application enables users to select a disease prediction system, provide necessary input features, and receive predictions instantly. Each model has been developed through detailed **data analysis**, **feature selection**, and **hyperparameter tuning** to ensure **high performance** and **reliability**.

---

## ⚙️ Installation

To run this project locally:

1. Clone this repository

   ```bash
   git clone <repo-url>
   cd multiple-disease-prediction
   ```
2. Install the dependencies

   ```bash
   pip install -r requirements.txt
   ```
3. Run the app

   ```bash
   streamlit run streamlit_app.py
   ```

---

## ▶️ Usage

Once launched, the app will open in your default browser. Use the sidebar to choose a **disease prediction system**, enter the required features, and get instant predictions.

---

## 📊 Datasets

1. **Diabetes** – 768 samples, 8 features (e.g., glucose, blood pressure, insulin).
2. **Heart Disease** – 1025 samples, 14 features (e.g., age, chest pain type, blood pressure).
3. **Parkinson’s Disease** – 195 samples, 22 features (e.g., vocal frequency, amplitude variation).
4. **Breast Cancer** – 569 samples, 30 features (e.g., radius, texture, perimeter, area).

---

## 🛠 Technologies Used

* **Programming:** Python
* **Framework:** Streamlit
* **ML Libraries:** Scikit-learn, XGBoost
* **Data Analysis & Visualization:** Pandas, NumPy, Matplotlib, Seaborn

---

## 📈 Model Development Process

1. Import dependencies
2. Perform **EDA (Exploratory Data Analysis)**
3. Data preprocessing:

   * Handle missing values and outliers
   * Apply encoding (Label/One-hot)
   * Standardize features
4. Train and evaluate multiple classifiers
5. Select best features via **RFE (Recursive Feature Elimination)**
6. Optimize with **GridSearchCV**
7. Build final models and evaluate with classification reports

---

## 🤖 Models Used

**Diabetes Prediction**

* Support Vector Classifier (SVC)
* Logistic Regression
* Random Forest Classifier

**Heart Disease Prediction**

* XGBoost
* Random Forest Classifier
* Logistic Regression

**Parkinson’s Disease Prediction**

* K-Nearest Neighbour (KNN)
* XGBoost
* Random Forest Classifier

**Breast Cancer Prediction**

* Logistic Regression
* XGBoost
* K-Nearest Neighbour (KNN)

---

## 📊 Model Evaluation

**Diabetes Prediction**

* SVC – 69.48%
* Logistic Regression – 70.13%
* Random Forest – 75.32%

**Heart Disease Prediction**

* XGBoost – 100%
* Random Forest – 100%
* Logistic Regression – 88.31%

**Parkinson’s Disease Prediction**

* KNN – 100%
* Random Forest – 94.87%
* XGBoost – 92.31%

**Breast Cancer Prediction**

* Logistic Regression – 97.37%
* XGBoost – 97.37%
* KNN – 96.49%

---

## ✅ Conclusion

This **Multiple Disease Prediction WebApp** offers a user-friendly interface and robust machine learning models to assist in **early diagnosis** and **decision-making** in healthcare. With well-validated models and high accuracy, it can serve as a reliable tool for predictive healthcare applications.

---

## 🚀 Deployment

The app is deployed on **Streamlit Cloud** and can be accessed online.

https://ml-multiple-diseases-predictions-shashank.streamlit.app/
---

## 🤝 Contributing

Contributions are welcome!

* Fork the repo
* Create a new branch
* Submit a pull request

---

## 📬 Contact

For questions or suggestions, reach out at:
📧 **[shashankshatraboina@gmail.com](mailto:shashankshatraboina@gmail.com)**
