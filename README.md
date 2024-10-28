# Customer Churn Prediction
## Overview

This project focuses on predicting customer churn for a telecommunications service provider using customer subscription data. The goal is to identify which customers are likely to discontinue their service (churn) based on various demographic and behavioral features.

The analysis involves utilizing a dataset containing 7,043 records and 21 features, such as customer tenure, monthly charges, and service usage patterns. By applying clustering techniques and machine learning models—like Naive Bayes, Logistic Regression, and Support Vector Machines—the project aims to develop effective strategies for customer retention based on the insights gained from the data.

Key findings highlight patterns related to customer demographics, service usage, and contract types, indicating how these factors influence churn behavior. The project ultimately seeks to provide actionable recommendations to reduce churn rates and enhance customer loyalty.


## Project Scope

This project aims to predict customer churn using advanced data analysis techniques. By leveraging clustering methods and machine learning models such as Naive Bayes, Logistic Regression, and Support Vector Machine, we propose strategies for customer retention based on insights derived from the dataset.

### Dataset

The dataset used for this analysis contains 7,043 rows and 21 columns, with the following key characteristics:
- **Target Column**: `Churn` (1 for "Yes", 0 for "No")
- **Index Column**: `customerID`
- **Data Types**:
  - **Binary Columns**: Gender, SeniorCitizen, Partner, Dependents, PhoneService, Paperless Billing, Churn
  - **Categorical Columns**: MultipleLines, InternetServices, OnlineSecurity, OnlineBackup, DeviceProtection, TechSupport, StreamingTV, StreamingMovies, Contract, PaymentMethod
  - **Numeric Columns**: Tenure, MonthlyCharges, TotalCharges

### Key Highlights

- **Data Quality**: The dataset is well-organized, with no missing values, making data cleaning a minimal effort.
- **Correlation Analysis**: Initial observations revealed significant correlations among various features, providing insights into relationships affecting customer churn.
- **Modeling Approaches**: Multiple machine learning algorithms were employed to model churn predictions, with a focus on accuracy and generalization.

## Methodology

1. **Data Exploration**: Analyzed data types, distributions, and relationships among features.
2. **Feature Engineering**: Encoded categorical variables and scaled numerical features to prepare for modeling.
3. **Modeling**: Implemented various machine learning algorithms, including:
   - **Naive Bayes**
   - **Logistic Regression**
   - **Support Vector Machine**
   - **Random Forest**

4. **Evaluation**: Assessed model performance using accuracy and cross-validation scores.

## Results

- **Random Forest** achieved the highest accuracy of **84.0%**.
- **Logistic Regression** demonstrated consistent performance with an accuracy of **80.0%** and a high cross-validation score of **0.81**.
- **Decision Tree** and **Random Forest** showed similar accuracies, while **Naive Bayes** yielded a moderate accuracy of **78.0%** but struggled with generalization.

### Observations
- Key features influencing churn rates were identified, including tenure, MonthlyCharges, and various service-related columns.
- The data showed imbalanced target classes, necessitating techniques to address this during modeling.

## Future Work

- Explore additional modeling techniques and ensemble methods to improve prediction accuracy.
- Investigate customer segmentation and personalized retention strategies based on churn predictors.
- Conduct further analysis on feature importance to refine insights into customer behavior.


