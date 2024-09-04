# Heart Disease Prediction Model

This project involves building and evaluating multiple machine learning models to predict heart disease using a dataset from the UCI Machine Learning Repository. The dataset includes various features related to patient health and is used to classify the presence or absence of heart disease.

## Steps and Methodology

### 1. Data Loading and Preprocessing
- **Loaded the dataset** using Pandas.
- **Handled missing values** with mean imputation.
- **Managed outliers** using the Interquartile Range (IQR) method.

### 2. Exploratory Data Analysis (EDA)
- **Visualized feature relationships** using pairplots.
- **Analyzed correlations** among features using a heatmap.

### 3. Model Selection and Training
- **Split the dataset** into training and testing sets.
- **Standardized features** using `StandardScaler`.
- Implemented and evaluated several classifiers, including:
  - Logistic Regression
  - K-Nearest Neighbors
  - Support Vector Classifier
  - Decision Tree
  - Random Forest
  - Gradient Boosting
  - AdaBoost

### 4. Model Evaluation
- **Compared model performance** using accuracy scores.
- **Identified the best-performing model** based on accuracy.

### 5. Hyperparameter Tuning
- Applied **GridSearchCV** for hyperparameter optimization on the best model.
- Evaluated the **tuned model** with updated accuracy and classification metrics.

### 6. Results
- Provided a **detailed classification report** and **confusion matrix** for the best model.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn


## Conclusion
This project demonstrates a comprehensive approach to building and tuning machine learning models for predicting heart disease, including data preprocessing, exploratory data analysis, model evaluation, and hyperparameter tuning.
