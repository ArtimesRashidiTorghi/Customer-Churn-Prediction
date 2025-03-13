# Customer-Churn-Prediction
Overview  This project analyzes customer churn data to identify key factors influencing churn and build predictive models to improve customer retention. The analysis involves data exploration, preprocessing, statistical hypothesis testing, feature engineering, and machine learning modeling to predict churn probability.

## Dataset

The dataset consists of customer information with features such as demographics, service subscriptions, contract details, tenure, and billing information. The target variable is Churn, which indicates whether a customer has left the service.

## Steps & Methodology

1. Data Exploration & Cleaning

Loaded the dataset and checked for missing values, duplicates, and inconsistent data.

Performed descriptive statistics to understand feature distributions.

Conducted correlation analysis to examine relationships between variables.

2. Data Preprocessing

Encoded categorical variables using One-Hot Encoding and Label Encoding.

Standardized numerical features using MinMaxScaler.

Handled missing values through imputation techniques.

Split data into training (80%) and testing (20%) sets.

3. Exploratory Data Analysis (EDA)

Visualized churn vs. non-churn customers across different variables.

Identified key drivers of churn using histograms, box plots, and bar charts.

Conducted hypothesis testing (Chi-square, ANOVA, and t-tests) to validate statistical significance of features.

4. Feature Engineering

Created new features like customer tenure groups and interaction terms.

Selected relevant features using mutual information and feature importance scores.

5. Model Building

Trained multiple models:

Logistic Regression

Random Forest Classifier

Gradient Boosting (XGBoost, LightGBM)

Support Vector Machine (SVM)

Artificial Neural Networks (ANN)

Evaluated models using Accuracy, Precision, Recall, F1-score, and ROC-AUC.

Performed hyperparameter tuning using GridSearchCV.

6. Model Evaluation

Random Forest and XGBoost performed best with high AUC-ROC scores.

Feature importance analysis showed that contract type, tenure, and billing method were key predictors of churn.

Plotted Confusion Matrix, Precision-Recall Curves, and ROC Curves to assess model performance.

## Conclusion

Customers with month-to-month contracts, high monthly charges, and electronic check payments had a higher churn probability.

Retention strategies should target these customers with discounted long-term contracts and personalized offers.

The best predictive model (XGBoost with optimized hyperparameters) achieved an AUC-ROC score of 0.88, indicating strong predictive capability.
