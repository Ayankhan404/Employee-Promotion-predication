# Employee Promotion Prediction - End-to-End Machine Learning Project

## Overview

This project focuses on predicting employee promotions using the Employee Promotion dataset. The goal is to analyze employee data and help organizations make informed promotion decisions. The project follows a complete end-to-end machine learning pipeline, including data preprocessing, exploratory data analysis (EDA), feature engineering, model building, and evaluation.

## Dataset

The dataset contains various features related to employee demographics, performance ratings, education, and previous promotions. The target variable indicates whether an employee gets promoted or not.

## Steps Involved

### 1. Importing Libraries

We use essential libraries such as:

- `pandas` and `numpy` for data manipulation
- `matplotlib` and `seaborn` for data visualization
- `sklearn` for machine learning model implementation

### 2. Loading and Understanding the Dataset

- Load the dataset into a Pandas DataFrame.
- Check dataset structure, column names, and data types.
- Identify missing values and handle them appropriately.

### 3. Data Preprocessing

- Check dataset shape and basic info.
- Use a heatmap to visualize missing values.
- Handle missing values in 'education' and 'previous_year_rating'.

### 4. Exploratory Data Analysis (EDA)

- Check value counts for categorical columns.
- Analyze numerical column distributions.
- Perform univariate and bivariate analysis.
- Identify imbalanced target variable and handle it accordingly.
- Check correlations between features using a heatmap.

### 5. Feature Engineering

- Identify and handle outliers.
- Create new features based on existing data.
- Perform feature selection to remove unnecessary columns.

### 6. Encoding Categorical Variables

- Use Label Encoding and Ordinal Encoding to convert categorical variables into numerical values.

### 7. Handling Imbalanced Data

- Use Synthetic Minority Over-sampling Technique (SMOTE) to balance the dataset.

### 8. Model Building and Selection

- Split the dataset into training and testing sets using `train_test_split`.
- Normalize the data using `StandardScaler`.
- Train models using Decision Tree and Random Forest.
- Evaluate models using Confusion Matrix, Classification Report, and Cross-validation.
- Random Forest performs better and is selected as the final model.

## Results

- The model successfully predicts employee promotions with high accuracy.
- The dataset contains 50K+ records.
- The final model achieved 95% accuracy, outperforming the Decision Tree.
- Feature selection and SMOTE improved model performance.

## Conclusion

This project demonstrates an end-to-end machine learning pipeline, from data preprocessing to model evaluation. The insights gained from this analysis can help businesses make data-driven promotion decisions.

## How to Run the Project

1. Clone the repository.
2. Install dependencies using:
   ```bash
   pip install -r requirements.txt
   ```
3. Run the Jupyter Notebook or Python script to execute the pipeline.

## Future Enhancements

- Experiment with other models like XGBoost and Neural Networks.
- Implement hyperparameter tuning for better model performance.
- Deploy the model as a web application.

## Author

[Ayan Khan](https://github.com/Ayankhan404)

## Connect with Me

[LinkedIn](https://www.linkedin.com/in/ayan-khan-917611250/)

---

Feel free to contribute or provide feedback!

