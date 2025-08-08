Customer Churn Prediction with Machine Learning

This project builds a full machine learning pipeline to predict Customer Churn in a banking dataset.
It includes preprocessing, feature engineering, SMOTE for class imbalance, multiple models (XGBoost, Random Forest, Naive Bayes, etc.)
ensemble learning, SHAP explainability, and a Streamlit app for live predictions and retention advice.

---

Features

 Trained and compared multiple models
 Applied SMOTE and feature engineering
 Built a Voting Classifier for improved robustness
 Explained predictions using SHAP
 Streamlit app with personalized retention strategies

---

 Run locally:

   pip install -r requirements.txt
   python -m streamlit run main.py --server.port 8502

---

 Dataset

  Source: [Kaggle - Customer Churn Dataset](https://www.kaggle.com/)
  File: churn.csv


