# 🔮 Churn Predictor: Decoding Customer Behavior in Telecom
# 🔮 ChurnMaster.AI

## Detailed Project Overview

This project focuses on predicting customer churn in the telecommunications industry using advanced machine learning and artificial intelligence techniques. Customer churn, the phenomenon where customers leave a service provider, is a critical concern in the telecom sector. By accurately predicting which customers are likely to churn, companies can take proactive measures to retain valuable customers.

### 📊 Dataset

The project uses a telecom customer dataset with the following key features:
- Customer demographics (gender, age range, partner status)
- Account information (tenure, contract type, payment method)
- Services used (phone, internet, streaming, security)
- Billing details (monthly charges, total charges)
- Churn status (target variable)

### 🧠 Methodology

1. **Data Preprocessing**: 
   - Handled missing values
   - Encoded categorical variables
   - Scaled numerical features

2. **Exploratory Data Analysis (EDA)**:
   - Visualized feature distributions
   - Analyzed correlations between features
   - Investigated churn rates across different customer segments

3. **Feature Engineering**:
   - Created interaction terms
   - Developed new features based on domain knowledge

4. **Model Development**:
   - Implemented multiple models:
     - Random Forest
     - XGBoost
     - LightGBM
     - Neural Network
   - Utilized ensemble methods (Voting, Bagging, Stacking)

5. **Time Series Analysis**:
   - Applied ARIMA and SARIMA models to analyze churn trends over time

6. **Deep Learning Approach**:
   - Designed a custom neural network architecture
   - Implemented using TensorFlow/Keras

## 🚀 Key Findings

- The neural network model achieved an accuracy of 81.41%
- Ensemble methods (Voting Classifier) improved accuracy to 81.19%
- Top factors influencing churn:
  1. Monthly Charges
  2. Tenure
  3. Contract Type
  4. Paperless Billing
  5. Total Charges
- Time series analysis revealed [your specific findings about churn trends]

## 📈 Model Performance

| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Neural Network | 80% | 0.84 (non-churn), 0.66 (churn) | 0.90 (non-churn), 0.52 (churn) | 0.87 (non-churn), 0.58 (churn) |
| [Other Models] | [Their respective performances] |

Neural Network
Accuracy: 81.41%
Precision (Churn): 0.68
Recall (Churn): 0.55
F1-Score (Churn): 0.61
XGBoost
Accuracy: 78.50%
Precision (Churn): 0.62
Recall (Churn): 0.47
F1-Score (Churn): 0.54
LightGBM
Accuracy: 80.13%
Precision (Churn): 0.66
Recall (Churn): 0.52
F1-Score (Churn): 0.58
Random Forest
Accuracy: 78.85%
Precision (Churn): 0.64
Recall (Churn): 0.45
F1-Score (Churn): 0.53

## 📁 Repository Contents

- `ChurnMaster_AI.ipynb`: Main Jupyter notebook containing all analysis and models
- `README.md`: This file, providing project overview and instructions
- `requirements.txt`: List of required Python packages


