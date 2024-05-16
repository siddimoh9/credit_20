# Module 12 Report Template

## Overview of the Analysis

In this analysis, we aimed to build machine learning models to predict the risk associated with loans. The purpose of this analysis is to assist financial institutions in assessing the likelihood of a loan being high-risk based on various financial features. 

The dataset likely contained financial information such as credit scores, income levels, debt-to-income ratios, loan amounts, and possibly other relevant metrics. The target variable we needed to predict was the risk level of the loan, typically categorized as 0 for healthy loans and 1 for high-risk loans.

From the provided evaluation metrics:

- Label 0 (healthy loans) has a precision, recall, and F1-score of 1.00, indicating perfect performance in predicting healthy loans.
- Label 1 (high-risk loans) has a precision of 0.87, recall of 0.95, and an F1-score of 0.91, showing slightly lower performance compared to healthy loans.

The stages of the machine learning process likely involved:

1. **Data Preprocessing**: This involves handling missing values, encoding categorical variables, and scaling numerical features if necessary.
  
2. **Exploratory Data Analysis (EDA)**: Understanding the distribution of features, identifying correlations, and visualizing relationships between variables to gain insights into the data.

3. **Feature Engineering**: Creating new features or transforming existing ones to improve model performance.

4. **Model Selection**: Choosing appropriate algorithms for classification tasks. In this case, logistic regression was used, but other algorithms like decision trees, random forests, or gradient boosting could also be considered depending on the nature of the data and the problem at hand.

5. **Model Training and Evaluation**: Training the selected model on the training data, tuning hyperparameters if needed, and evaluating its performance using metrics like accuracy, precision, recall, and F1-score.

6. **Model Validation and Interpretation**: Validating the model's performance on unseen data (e.g., using cross-validation) and interpreting the results to make informed decisions.

Overall, the analysis aimed to develop a predictive model that could effectively differentiate between healthy and high-risk loans based on available financial information. The logistic regression model showed strong performance, particularly in predicting healthy loans, while still maintaining good performance for identifying high-risk loans.

## Results

* Machine Learning Model 1:
  * Accuracy: 99%
  * Precision:
    * Label 0 (healthy loans): 100%
    * Label 1 (high-risk loans): 87%
  * Recall:
    * Label 0 (healthy loans): 100%
    * Label 1 (high-risk loans): 95%

## Summary

Based on the results of the machine learning models:

- **Model Performance**: 
  - All models exhibit high accuracy, with Machine Learning Model 1 achieving 99% accuracy.
  - Machine Learning Model 1 demonstrates strong precision and recall scores for both healthy (label 0) and high-risk (label 1) loans, with precision scores of 100% and 87% respectively, and recall scores of 100% and 95% respectively.

- **Recommendation**:
  - Machine Learning Model 1 appears to perform the best overall, as it achieves the highest accuracy and maintains high precision and recall scores for both healthy and high-risk loans.

- **Problem Dependency**:
  - The importance of predicting healthy (label 0) loans versus high-risk (label 1) loans may vary depending on the specific goals and context of the problem. 
  - In a financial context, correctly identifying high-risk loans (label 1) may be of paramount importance to mitigate potential losses and manage risk effectively. However, misclassifying healthy loans (label 0) as high-risk could lead to missed opportunities and decreased profitability.
  
- **Recommendation Justification**:
  - Given the balanced performance across both classes and the high overall accuracy, Machine Learning Model 1 is recommended for predicting loan risk. Its ability to effectively identify both healthy and high-risk loans makes it a robust choice for financial institutions seeking to assess loan portfolios and manage risk effectively.