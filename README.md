
This GitHub repository contains a data science project focused on assessing loan repayment using machine learning models. The project aims to predict whether a customer will repay a loan based on various features and historical data.

Project Overview
In this project, we leverage data science techniques to analyze banking data and build predictive models to determine the likelihood of loan repayment. By utilizing historical loan data, we aim to develop models that assist in making informed lending decisions.

The code provided is a detailed implementation of a loan repayment assessment model using Python libraries like Pandas, NumPy, Matplotlib, Seaborn, and scikit-learn. The code performs data preprocessing, feature engineering, model training, and evaluation. Here's a brief summary:

1. Data Preprocessing:
   - Loads the train and test datasets from CSV files.
   - Checks for missing values and imputes them with the mean for numerical features and mode for categorical features.
   - Handles outliers using the IQR method.
   - Encodes categorical features.
   - Scales numerical features using StandardScaler.

2. Feature Selection:
   - Uses a Random Forest classifier to select the most important features based on their importance weights.

3. Model Training:
   - Trains a Random Forest classifier and XGBoost classifier on the resampled training data after handling class imbalance with SMOTE.
   - Performs cross-validation and grid search to evaluate and optimize the models.

4. Model Evaluation:
   - Evaluates the performance of the trained models using metrics like accuracy, precision, recall, and F1 score.

5. Model Saving:
   - Saved the trained Random Forest and XGBoost models as pickle files for future use.

Overall, the code provides a complete solution for building and evaluating a loan repayment assessment model using various data preprocessing techniques, feature selection, and machine learning algorithms.
