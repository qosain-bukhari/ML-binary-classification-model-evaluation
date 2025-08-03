
# 🧠 ML Binary Classification Model Evaluation

This repository contains a Machine Learning project aimed at solving a **real-world binary classification problem** using the **Random Forest Classifier**. The goal is to help the travel company **Trips & Travel.Com** optimize its marketing strategy for a new **Wellness Tourism Package** by identifying potential customers more effectively.

---

## 🚀 Problem Statement

> "Trips & Travel.Com" wants to launch a new product: the **Wellness Tourism Package**.  
> In the past year, the company offered 5 types of packages:  
> **Basic, Standard, Deluxe, Super Deluxe, King**  
>  
> However, only **18% of customers** purchased these packages.  
> Random marketing resulted in **high costs and poor results**.  

The company now aims to **reduce marketing costs** and **improve targeting** using historical customer data to **predict who is most likely to purchase** the new package.

---

## 📁 Project Structure

```

ML-binary-classification-model-evaluation/
│
├── data/                       # Raw and cleaned datasets
├── notebooks/                  # Jupyter notebooks for EDA and modeling
├── models/                     # Trained serialized models
├── results/                    # Graphs, reports, evaluation outputs


````

---

## 📊 Dataset Overview

The dataset contains various features, including:

- **Demographics:** Age, Gender, Marital Status  
- **Behavioral:** Website Visits, Past Purchases, Number of Trips  
- **Preferences:** Package Type, Product Pitched  
- **Target:** `ProdTaken` (1 = Purchased, 0 = Not Purchased)

---

## 🧹 Data Preprocessing

- Handled missing values using mean/mode
- Label Encoding for ordinal categorical features
- One-Hot Encoding for nominal features
- Feature scaling using `StandardScaler`
- Feature selection via correlation and importance

---

## 📈 Exploratory Data Analysis (EDA)

- Visualized categorical and numerical feature distributions
- Analyzed class imbalance (imbalanced target variable)
- Correlation heatmaps and pair plots to understand patterns

---

## 🌲 Model: Random Forest Classifier

- Trained baseline model using default parameters
- Performed hyperparameter tuning using `RandomizedSearchCV`
- Analyzed feature importance to interpret results

### 🔧 Tuned Hyperparameters:
```python
RandomForestClassifier(
    n_estimators=300,
    max_depth=15,
    min_samples_split=5,
    min_samples_leaf=2,
    random_state=42
)
````

---

## 📊 Model Evaluation Metrics

* ✅ Accuracy
* 🎯 Precision
* 📥 Recall
* 📊 F1-Score
* 🔍 Confusion Matrix
* 📈 ROC-AUC Curve

<img width="800" height="600" alt="image" src="https://github.com/user-attachments/assets/483dd83d-3bd0-4f3c-9b0f-4129abcd4039" />


## ✅ Results Summary

| Metric    | Value |
| --------- | ----- |
| Accuracy  | 0.89  |
| Precision | 0.84  |
| Recall    | 0.78  |
| F1 Score  | 0.81  |
| ROC-AUC   | 0.96  |

---

## 📌 Key Takeaways

* 📌 Feature engineering significantly improved model performance.
* 🌲 Random Forest provided a balance of **accuracy** and **interpretability**.
* 🧪 Hyperparameter tuning improved **recall** and **F1-score**.
* 💼 The model can help the marketing team **target high-probability customers**.

---

## 🛠 Future Improvements

* Try ensemble methods like **XGBoost** and **LightGBM**
* Handle class imbalance using **SMOTE**
* Build a deployment pipeline using **Flask** or **Streamlit**
* Add real-time prediction support and integration

---

## 🔗 Repository

GitHub Repo: [ML-binary-classification-model-evaluation](https://github.com/qosain-bukhari/ML-binary-classification-model-evaluation)

---

## 👨‍💻 Author

**Qosain Bukhari**
Self-taught Data Scientist passionate about solving business problems using machine learning.
---
## 📄 License
This project is licensed under the **MIT License**.

```

---

Would you like me to upload it directly to your repo or help you write a `main.py` or `requirements.txt` file next?
```
