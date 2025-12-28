# 💰 Loan Status Prediction using Machine Learning

## 📌 Project Overview
This machine learning project predicts whether a loan application will be
**approved or rejected** based on applicant details and financial information.

The goal of the project is to build a **classification model** that can assist
financial institutions in assessing loan eligibility using historical data.

The project covers the complete machine learning pipeline including
data preprocessing, model training, evaluation, and prediction.

---

## 📊 Dataset Information
- **Dataset:** Loan Status Prediction Dataset  
- **Source:** Commonly used loan eligibility dataset  
- **Features Include:**
  - Applicant Income  
  - Coapplicant Income  
  - Loan Amount  
  - Loan Amount Term  
  - Credit History  
  - Gender  
  - Marital Status  
  - Education  
  - Self Employment  
  - Property Area  

- **Target Variable:**
  - `Y` → Loan Approved  
  - `N` → Loan Not Approved  

This dataset contains both numerical and categorical features,
making it suitable for classification and preprocessing practice.

---

## 🛠️ Technologies & Libraries Used
- Python  
- NumPy  
- Pandas  
- Matplotlib  
- Seaborn  
- Scikit-learn  
- Google Colab / Jupyter Notebook  

---

## ⚙️ Machine Learning Model
- **Problem Type:** Binary Classification  
- **Algorithm Used:** Logistic Regression  
- **Preprocessing Steps:**
  - Handling missing values  
  - Label encoding of categorical variables  
  - Feature scaling (where applicable)  
- **Data Split:** Train–test split  

Logistic Regression is chosen due to its simplicity, interpretability,
and suitability for binary classification problems.

---

## 📈 Model Performance
The model is evaluated using classification accuracy on unseen test data.

- **Training Accuracy:** 79.86% 
- **Test Accuracy:** 83.33% 

The results indicate that the model learns meaningful patterns
from the data and generalizes reasonably well.

---

## 📊 Data Visualization
The project includes:
- Distribution plots for numerical features  
- Count plots for categorical features  
- Insights into feature influence on loan approval  

These visualizations help in understanding the dataset
and the factors affecting loan approval decisions.

---

## 🚀 How to Run the Project
1. Clone this repository  
2. Open the notebook in **Google Colab** or **Jupyter Notebook**  
3. Install required libraries  
4. Run all cells sequentially  

---

## 📁 Project Structure
loan-status-prediction/
│── loan_status_prediction.ipynb
│── load_dataset.csv
│── README.md

## 📌 Conclusion
This project demonstrates how machine learning can be applied to
financial decision-making systems such as loan approval prediction.
With proper preprocessing and evaluation, even simple models like
Logistic Regression can provide useful insights.

---

## 👩‍💻 Author
**Anjali Sevkani**
