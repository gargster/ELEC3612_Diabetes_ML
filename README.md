# ELEC3612_Diabetes_ML
This repository contains the code and notebooks for Assignment 1 in ELEC3612. A range of supervised, unsupervised and machine-learning models were applied to the CDC BRFSS 2015 diabetes dataset, to predict diabetes risk.
## Notebook Structure
The code was intially developed across Google Colab for preprocessing which is why file paths refer to /content/drive/... and the rest of the work (model implementations) was developed on Kaggle Notebook (file paths refer to /kaggle/input/...). All

- **01_preprocessing.ipynb**
  - Data loading
  - Data Quality Checks
  - Data Cleaning
  - Summary Statistics 
- **02_supervised_part1.ipynb**
- Contains the first set of supervised models:
  - Support Vecotor Machine (SVM)
  - Logistic Regression

- **03_supervised_part2.ipynb**
- Contains the remaining supervised and ensemble models:
  - Decision Tree
  - Random Forest
  - Gradient Boosting

- **04_unsupervised.ipynb**
- Contains the unsupervised model:
  - K-Means clustering
