# ***📝 Insurance_Cost_Prediction***(PRCP-1021-InsCostPred)

The Insurance Cost Prediction project is a machine learning application designed to estimate medical insurance expenses based on individual demographic and lifestyle factors. By analyzing historical insurance data, the model identifies patterns and relationships between variables such as:

Age 🧑‍🦳 – Older individuals often face higher costs.

Gender ⚧ – Used as a categorical feature.

BMI (Body Mass Index) ⚖️ – Indicates health risks linked to obesity or underweight.

Number of Children/Dependents 👨‍👩‍👧‍👦 – Impacts family coverage costs.

Smoking Status 🚬 – A major driver of higher premiums.

Region 🌍 – Geographic differences in healthcare costs.


## Problem Statement
Task 1:- Prepare a complete data analysis report on the given data.

Task 2:-
1.Prepare the data, identifying and extracting key features (both input and output parameters) relevant to the problem you will solve.
2.Build and train a machine learning model. Here you can evaluate different algorithms, settings and see which model is best for your scenario.

Task 3:-  Create a machine learning model to predict the insurance price charged to the customer. The charge depends on various features such as age, type of coverage, amount of coverage needed, gender, body mass index (BMI), region, and other special factors like smoking to determine what health risks the person possesses.

## Project Type
Project Type: Predictive Analytics / Regression

Goal: Estimate medical insurance costs based on demographic and lifestyle features.

Approach: Uses regression models (Linear Regression, Random Forest, Gradient Boosting,XGBoost etc.) to learn from historical insurance data and predict continuous numerical values (insurance charges).

Output: A numeric prediction of expected insurance cost for a given individual profile.

## Contents
* Insurance_Datasets.csv  — Complete Historical Dataset
* Insurance Cost Prediction Model.ipynb  — Full analysis notebook: EDA,visualizations (Univariate/Bivariate/Multivariate), hypothesis testing, feature engineering, and 4 ML models (Linear Regression, Random Forest,Gradient Boosting, XGBoost) with hyperparameter tuning.
* Insurance_Cost_Data_Analysis_Report.docx :  — Report of Entire Work
* Model_Comparison_and_Production_Report.docx  — Performance comparison across all three models and final model recommendation.
* Data_Challenges_Faced_and_Techniques.docx  —  Data and modeling challenges encountered, techniques used, and reasoning.

## Model Performance Summary
| Model              | RMSE   | MAE    | R² Score | Adjusted R² |
|--------------------|--------|--------|----------|-------------|
| Linear Regression  | 0.4526 | 0.2991 | 0.7722   | 0.7687      |
| Random Forest      | 0.4174 | 0.2358 | 0.8062   | 0.8033      |
| Gradient Boosting  | 0.3858 | 0.2177 | 0.8344   | 0.8319      |
| XGBoost            | 0.3970 | 0.2245 | 0.8247   | 0.8221      |


 | Model              | R² Before Tuning | R² After Tuning | Change                          |
|--------------------|------------------|-----------------|---------------------------------|
| Linear Regression  | 0.7722           | 0.7722          | No change                       |
| Random Forest      | 0.8062           | 0.8117          | +0.0055 (small improvement)     |
| Gradient Boosting  | 0.8344           | 0.8313          | −0.0031 (essentially unchanged) |
| XGBoost            | 0.8247           | 0.8318          | +0.0071 (improved)              |

## Tech Stack
Python · Pandas · NumPy · Scikit-learn · Matplotlib · Seaborn · SciPy
