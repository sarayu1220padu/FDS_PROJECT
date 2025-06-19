# 🧬 Thyroid Cancer Risk Prediction using Machine Learning

This project aims to predict the risk level of thyroid cancer (Low, Medium, High) using supervised machine learning techniques. It is built using a dataset obtained from Kaggle and includes multiple health-related features.

## 📌 Dataset Source

The dataset is available on Kaggle:

🔗 [Kaggle - Thyroid Cancer Risk Prediction (by gagandeep44489)](https://www.kaggle.com/code/gagandeep44489/thyroid-cancer-risk-prdictionbyg/output)

It includes patient demographic and health indicators like:
- Age, Gender, Ethnicity, Country
- TSH, T3, T4 hormone levels
- Family history, Obesity, Diabetes, Smoking
- Radiation exposure, Iodine deficiency, Nodule size
- Target: **Thyroid_Cancer_Risk** (Low, Medium, High)

## 🎯 Objective

- Clean and preprocess raw health data
- Visualize key patterns using Seaborn & Matplotlib
- Train and evaluate classification models (Logistic Regression, Random Forest, etc.)
- Predict the thyroid cancer risk level for new patients

## 🧰 Tools & Technologies

- **Language:** Python 3.x
- **Libraries:** Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn
- **Notebook:** Jupyter

## 📈 Model Performance

- The best-performing model was **Random Forest Classifier**.
- Achieved high accuracy and precision in predicting the correct risk category.
- The model supports multi-class classification for:
  - 🟢 Low Risk
  - 🟡 Medium Risk
  - 🔴 High Risk

## 🧪 Sample Prediction

A new patient with:
  Age: 45, TSH: 0.3, T3: 1.9, T4: 130, Nodule Size: 2.5
Family History: Yes, Obesity: No, Diabetes: Yes

csharp
Copy
Edit

Was predicted as: **🔴 High Risk**

## 📂 Folder Structure

├── FDS_PROJECT.ipynb # Main Jupyter notebook
├── thyroid_cancer_risk_data.csv # Dataset file
├── thyroid_cancer_cleaned.csv # Cleaned dataset after preprocessing
├── README.md # Project description

## 🙋‍♀️ Author

**Marri Sarayu**  
B.Tech, Artificial Intelligence & Data Science  
Stanley College of Engineering and Technology for Women

## 📄 License

This project is for academic and educational use only.
