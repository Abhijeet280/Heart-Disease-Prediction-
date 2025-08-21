# ❤️ Heart Disease Prediction

This project predicts the **presence of heart disease** using **Machine Learning models**.
It involves **data preprocessing, exploratory data analysis (EDA), encoding, scaling, and model building** with classification algorithms.

---

## 🚀 Project Overview

The notebook performs the following steps:

1. **Importing Libraries** – Loading required Python libraries (pandas, numpy, sklearn, matplotlib, seaborn, etc.)
2. **Exploratory Data Analysis (EDA)** – Analyzing distributions and correlations of medical features.
3. **Encoding Data** – Converting categorical features into numerical values (Label Encoding / One-Hot Encoding).
4. **Scaling Data** – Applying normalization/standardization to improve model performance.
5. **Model Building** – Training machine learning models for heart disease prediction:

   * Logistic Regression
   * Random Forest Classifier
   * (Other models may also be compared depending on notebook content)
6. **Model Evaluation** – Comparing models using metrics such as **Accuracy, Precision, Recall, F1-Score, and ROC-AUC**.

---

## 🛠️ Technologies Used

* Python
* Pandas & NumPy
* Matplotlib & Seaborn
* Scikit-learn (Logistic Regression, Random Forest, etc.)
* Jupyter Notebook

---

## 📂 Dataset

The dataset `heart.csv` contains patient medical records with the following features:

* **Age** – Age of the patient
* **Sex** – Gender (M/F)
* **ChestPainType** – Type of chest pain (ATA, NAP, ASY, etc.)
* **RestingBP** – Resting blood pressure (mm Hg)
* **Cholesterol** – Serum cholesterol (mg/dl)
* **FastingBS** – Fasting blood sugar (>120 mg/dl: 1 = true, 0 = false)
* **RestingECG** – Resting electrocardiogram results (Normal, ST, LVH)
* **MaxHR** – Maximum heart rate achieved
* **ExerciseAngina** – Exercise-induced angina (Y/N)
* **Oldpeak** – ST depression induced by exercise relative to rest
* **ST\_Slope** – Slope of the peak exercise ST segment (Up, Flat, Down)
* **HeartDisease** – Target variable (1 = Presence, 0 = Absence)

---

## 📈 Expected Insights

* **Age, cholesterol, and blood pressure** are key indicators of heart disease.
* **Exercise-induced angina and ST\_Slope** show strong correlations with the presence of heart disease.
* **Random Forest Classifier** is expected to perform better than Logistic Regression due to handling non-linear patterns.

---

