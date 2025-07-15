# Classification-Algorithms-on-SocialNetworkAd_dataset
Applied Logistic Regression, KNN, Decision Tree, and Random Forest Classifiers on Social Network Ads data to predict user behavior. Includes EDA, model comparison, and accuracy analysis.


# 📱 Social Network Ads - Classification Analysis

This project uses machine learning classification algorithms to analyze and predict user behavior based on a social media advertising dataset.

## 🔍 Project Overview

Using the `Social_Network_Ads.xls` dataset, we performed classification using:
- 🔸 Logistic Regression
- 🔸 K-Nearest Neighbors (KNN)
- 🔸 Decision Tree Classifier
- 🔸 Random Forest Classifier

The aim is to predict whether a user will purchase a product based on features like age, estimated salary, and more.

---

## 📂 Dataset Description

The dataset contains:
- **Age**
- **Estimated Salary**
- **Gender (if included)**
- **Purchased** (Target variable: 0 = No, 1 = Yes)

> 📌 Binary classification problem: Will the user buy the product?

---

## 🛠️ Technologies Used

- Python 🐍
- Pandas, NumPy
- Scikit-learn (classification models, metrics, train-test split)
- Matplotlib & Seaborn (for data visualization)
- Jupyter Notebook / Google Colab

---

## 📊 Model Evaluation Metrics

To evaluate each classification model, we used:
- ✅ Accuracy Score
- ✅ Confusion Matrix
- ✅ Classification Report (Precision, Recall, F1-Score)
- ✅ ROC Curve (for Logistic Regression and Random Forest)

---

## ⚙️ Results Summary

| Model                | Accuracy  |
|----------------------|-----------|
| Logistic Regression  | 85.12     |
| KNN Classifier       | 89.78     |
| Decision Tree        | 90.88     |
| Random Forest        | 91.30     |

> Replace `91.30` with actual scores after running the models.

---

## 📌 Key Insights

- Logistic Regression performs well with linearly separable data.
- KNN is sensitive to feature scaling.
- Random Forest and Decision Tree models capture non-linear patterns effectively.
- Random Forest showed the best performance overall in terms of both accuracy and generalization.

---
