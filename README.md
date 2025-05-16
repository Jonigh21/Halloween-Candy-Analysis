Halloween Candy Project

Overview

This project explores the 2017 Halloween Candy Hierarchy survey data to uncover insights about candy preferences and their correlation with demographic information like gender and age. The primary objective of the analysis is to clean and preprocess the dataset for machine learning readiness, as well as explore patterns in candy joy, despair, and neutrality ratings. The final goal is to predict gender based on candy preferences using machine learning.

Dataset

The dataset used for this analysis is the 2017 Halloween Candy Hierarchy survey, which contains survey responses about participants' candy preferences, demographic information, and more.

Key Columns:

Q2: GENDER: Gender of the survey participant.

Q3: AGE: Age of the participant.

Q4: COUNTRY: Country of the participant.

Candy Preferences Columns: These include responses for different candy types categorized as JOY, MEH, or DESPAIR.

Project Steps

Import & Data Exploration:

Loaded the dataset and performed initial exploration.

Data Cleaning & Preprocessing:

Removed irrelevant columns, handled missing values, and standardized country names.

Filtered rows to include only responses with gender specified as Male or Female.

Feature Engineering

Analyzed candy preferences and demographic distributions.

Data Transformation & Encoding

Created a new feature net_feelies to capture the difference between JOY and DESPAIR ratings for each candy type.

Transformed categorical features into numerical representations suitable for machine learning.

Conclusion

Model Selection

Logistic Regression was used to predict gender based on candy preferences. Evaluation metrics included:

Accuracy

Confusion Matrix

Classification Report

Results

The model successfully identified patterns in candy preferences that align with gender, providing a baseline for prediction accuracy.

Future Improvements

Implement more advanced models (e.g., Random Forest, SVM) for improved accuracy.

Integrate more demographic features for deeper analysis.

Author

Jonigh McGee
