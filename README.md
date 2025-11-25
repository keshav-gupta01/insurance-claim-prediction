📈 Predictive Modeling for Policyholder Behavior

This project aims to analyze and model insurance claim likelihood based on the behavioral and demographic attributes of policyholders using machine learning techniques. The project is built by a second-year actuarial science student as part of a public modeling portfolio.

🔍 Problem Statement

The goal of this project is to predict whether a policyholder is likely to file an insurance claim based on their behavioral and demographic features. Key features include:

- Age
- Smoking status
- BMI (Body Mass Index)
- Region

By understanding the likelihood of claims, insurers can improve pricing strategies, risk management practices, and customer engagement.

🧪 Key Features

- Raw Data Preprocessing and Cleaning: We process and clean the raw dataset, ensuring it's ready for model training.

- One-hot Encoding: Categorical variables like region and sex are encoded using one-hot encoding to prepare them for machine learning models.

- Binary Encoding: The smoker status is binary encoded (1 for smoker, 0 for non-smoker) to work with the model effectively.

- Standardization of Numerical Features: Features like age, BMI, and charges are standardized to ensure the model trains effectively and avoids skewed predictions.

- Model Training: We use Random Forest and Decision Trees for training the model and predicting claim likelihood.

- Model Evaluation: The performance of the model is evaluated using a confusion matrix to understand the true positives, true negatives, false positives, and false negatives.

