# 📊 Customer Churn Prediction

This project uses machine learning models to predict customer churn using the [Telco Customer Churn dataset](https://www.kaggle.com/datasets/blastchar/telco-customer-churn). The objective is to identify customers likely to leave a telecom service, helping businesses take proactive measures to retain them.

---

## 🛠️ Tech Stack
- Python (Pandas, NumPy, Matplotlib, Seaborn)
- Scikit-learn (DecisionTree, RandomForest, Model Evaluation)
- Jupyter Notebook

---

## 📈 Project Overview

1. **Data Cleaning**: Handled missing values and converted categorical data into numerical format.
2. **Exploratory Data Analysis (EDA)**: Visualized key trends like tenure, monthly charges, and churn patterns.
3. **Model Building**:
   - Implemented **Decision Tree** and **Random Forest Classifier**
   - Used `class_weight='balanced'` to address class imbalance
4. **Model Evaluation**:
   - Compared models using accuracy, precision, recall, and F1-score
   - Random Forest outperformed Decision Tree with a 72% accuracy and better churn detection precision

---

## ✅ Key Results
- **Accuracy**: 72%
- **Precision for Churn**: 58%
- **Balanced Evaluation using Confusion Matrix & Classification Report**

---

## 💡 Reflections
- Learned how class imbalance impacts real-world classification.
- Improved confidence in building & tuning ML models using real datasets.
- Future scope includes: Hyperparameter tuning, SMOTE, deployment via Streamlit or Flask.

---

## 📁 Files
- `customer_churn.ipynb`: Jupyter Notebook with complete code and visualizations
- `telco_customer.csv`: Dataset used for training/testing



