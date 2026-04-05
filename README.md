# Enterprise Customer Churn Prediction with Explainable AI (SHAP)

This project demonstrates a production-grade Machine Learning pipeline designed to predict customer churn using the Telco dataset. It focuses not only on accuracy but also on **Model Interpretability** for business decision-making.

## 🚀 Key Technical Features
- **Senior-Level Pipeline:** Implemented `Scikit-learn Pipeline` and `ColumnTransformer` for automated data preprocessing (scaling, encoding, and imputation).
- **Advanced Modeling:** Utilized **LightGBM Classifier** with balanced class weights to handle data imbalance.
- **Explainable AI (XAI):** Integrated **SHAP (Lundberg et al.)** to visualize feature importance and understand the "Why" behind every prediction.
- **Business Metrics:** Evaluated using Precision-Recall curves and ROC-AUC to ensure the model aligns with real-world business costs.

## 📊 Results & Visuals
- **ROC-AUC Score:** High diagnostic ability for identifying potential churners.
- **SHAP Summary:** Identified key churn drivers such as Contract type and Tenure.
- **Confusion Matrix:** Optimized to balance False Positives and False Negatives.

## 🛠️ Tech Stack
- **Core:** Python, Pandas, NumPy.
- **ML/AI:** LightGBM, Scikit-learn, SHAP.
- **Visualization:** Seaborn, Matplotlib.
