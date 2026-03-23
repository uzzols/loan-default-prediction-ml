# loan-default-prediction-ml
Machine Learning models for predicting loan default using borrower financial attributes
# Loan Default Prediction using Machine Learning

This project applies machine learning techniques to predict loan default risk using borrower financial attributes.

## Models Used
- Logistic Regression
- Random Forest
- Gradient Boosting

## Dataset Features
- Age
- Income
- Credit Score
- Loan Amount
- Debt-to-Income Ratio
- Interest Rate

## Results
The Gradient Boosting model achieved the highest accuracy of approximately 88.7%.

## Project Structure
- notebooks/: Jupyter notebook with analysis
- data_sample/: sample dataset
- figures/: visualizations (ROC, feature importance, etc.)
- paper/: full research paper

## Tools Used
- Python
- Pandas
- Scikit-learn
- Matplotlib
## Project 2: Class Imbalance Study

This project investigates the effect of class imbalance handling techniques on loan default prediction.

### Techniques Used
- SMOTE
- Class Weighting

### Key Results
- Baseline Recall (Default Class): 0.05
- Gradient Boosting + SMOTE Recall: 0.17
- Logistic Regression + Class Weight Recall: 0.66

### Figures

#### Recall Comparison
![Recall Comparison](figures/project2/project2_recall_comparison.png)

#### Confusion Matrix
![Confusion Matrix](figures/project2/project2_confusion_matrix_smote.png)

### Paper
[Download Paper 2](paper2/loan_default_class_imbalance_study.pdf)
