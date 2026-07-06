# Loan Default Prediction using Machine Learning and Deep Learning

## Overview

This project develops an end-to-end machine learning pipeline to predict whether a borrower is likely to repay a loan using historical Lending Club loan data. The project demonstrates the complete data science workflow, including data preprocessing, exploratory data analysis (EDA), feature engineering, model training, evaluation, and comparison of multiple classification algorithms.

The primary objective is to build predictive models that assist in credit risk assessment, enabling financial institutions to identify high-risk loan applications and make informed lending decisions.

---

## Dataset

**Source:** Lending Club Loan Dataset

The dataset contains historical loan information with borrower financial details and loan characteristics.

### Target Variable

- **loan_repaid**
  - 1 → Loan Repaid
  - 0 → Loan Default

### Important Features

- Loan Amount
- Interest Rate
- Installment
- Annual Income
- Employment Length
- Home Ownership
- Debt-to-Income Ratio (DTI)
- Credit Grade
- Purpose
- Mortgage Accounts
- Revolving Balance

---

## Project Workflow

- Data Collection
- Exploratory Data Analysis (EDA)
- Missing Value Analysis
- Data Cleaning
- Feature Engineering
- Categorical Encoding
- Feature Scaling
- Model Development
- Model Evaluation
- Model Comparison

---

## Exploratory Data Analysis

The following analyses were performed:

- Distribution of numerical features
- Loan repayment class distribution
- Correlation Heatmap
- Missing Value Analysis
- Boxplots for outlier detection
- Feature relationship analysis

---

## Data Preprocessing

The preprocessing pipeline includes:

- Removing irrelevant features
- Handling missing values
- Encoding categorical variables
- Feature scaling using MinMaxScaler
- Train-Test Split

---

## Machine Learning Models

The following classification models were implemented and compared:

- Logistic Regression
- Random Forest Classifier
- Neural Network (TensorFlow/Keras)

---

## Model Evaluation Metrics

Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix
- ROC Curve
- Precision-Recall Curve

---

## Model Performance

| Model | Accuracy | Precision | Recall | F1 Score | ROC-AUC |
|-------|---------:|----------:|--------:|---------:|--------:|
| Logistic Regression | 0.8878 | 0.8799 | 0.9960 | 0.9343 | 0.9028 |
| Random Forest | 0.8880 | 0.8810 | 0.9947 | 0.9344 | 0.8900 |
| Neural Network | 0.8870 | 0.8769 | 0.9994 | 0.9341 | 0.9034 |

---

## Key Findings

- All three models achieved comparable performance with an accuracy of approximately **89%**.
- The Neural Network achieved the highest ROC-AUC score, indicating slightly better discriminative capability.
- Random Forest produced the highest Accuracy, Precision, and F1 Score.
- Logistic Regression performed competitively while remaining computationally efficient and highly interpretable.
- Loan amount, interest rate, annual income, debt-to-income ratio, and credit grade were among the most influential factors affecting loan repayment.

---

## Output
<img width="631" height="547" alt="image" src="https://github.com/user-attachments/assets/6f84e5fa-c00c-4f8e-a496-4a2aea41b467" />
<img width="567" height="455" alt="image" src="https://github.com/user-attachments/assets/87579a14-dd4a-431d-a391-09dc99634e0a" />
<img width="938" height="701" alt="image" src="https://github.com/user-attachments/assets/3d5538c5-0ad5-4461-a793-445678759b3d" />



## Technologies Used

### Programming Language

- Python

### Libraries

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- TensorFlow / Keras

### Development Environment

- Jupyter Notebook

---

## How to Run

1. Clone the repository

```
git clone https://github.com/srisathvika/Loan-Default-Prediction-using-Machine-Learning-and-Deep-Learning.git
```


2. Open the notebook

```
jupyter notebook
```

3. Run all cells.

---

## Future Improvements

- Hyperparameter tuning using GridSearchCV
- Implement XGBoost and LightGBM models
- Model explainability using SHAP
- Address class imbalance using SMOTE
- Deploy the model using Streamlit or Flask
- Containerize the application using Docker

---

## Results

This project demonstrates an end-to-end implementation of a loan default prediction system using machine learning and deep learning techniques. The comparative evaluation shows that all three models provide strong predictive performance, with the Neural Network achieving the highest ROC-AUC score and Random Forest obtaining the highest overall classification accuracy. The developed pipeline can support financial institutions in improving credit risk assessment and loan approval decisions.

---

## Author

**Sri Sathvika Mudari**

MSc Artificial Intelligence  
University of East London

LinkedIn: https://www.linkedin.com/in/sri-sathvika-mudari-531b9b240/

GitHub: https://github.com/srisathvika
