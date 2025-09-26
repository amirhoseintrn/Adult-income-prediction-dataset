# Adult-income-prediction-dataset
Machine Learning project predicting income levels using census data. Compares Logistic Regression, Random Forest,a neural netork and XGBoost models with 86% accuracy.
# Income Prediction Machine Learning Project

## Project Description
I built a machine learning system that predicts whether a person's income exceeds $50K/year based on their demographic information. This project demonstrates my skills in data preprocessing, model selection, and performance evaluation using real-world data.

## Business Problem
Income prediction has important applications in marketing, loan eligibility assessment, and social research. classifying their income into more or less than 50k leads companies to know whether they need to lend a loan  or not or can they afford expensive goods or no

## Technical Approach
- **Data**: 30,000+ records with 14 features including age, education, occupation, and marital status
- **Preprocessing**: Handled categorical variables, created dummy variables, split data into train/validation/test sets
- **Models**: Implemented and compared four algorithms:
  - Logistic Regression (baseline)
  - Random Forest (ensemble method) 
  - XGBoost (gradient boosting)
  - PyTorch Neural Network (deep learning approach)(not so efficient here)
- **Evaluation**: Used accuracy, precision, recall, and F1-score with proper train-validation-test split

## Key Results
| Model | Accuracy | Precision | Recall | F1-Score |
|-------|----------|-----------|--------|----------|
| Logistic Regression | 83.2% | 0.68 | 0.55 | 0.61 |
| Random Forest | 85.1% | 0.72 | 0.58 | 0.64 |
| **XGBoost** | **86.3%** | **0.74** | **0.60** | **0.66** |
| PyTorch Neural Network | 84.0% | 0.70 | 0.57 | 0.63 |

## Skills Demonstrated
- **Data Preprocessing**: Handling missing values, categorical encoding, feature scaling
- **Machine Learning**: Model selection, hyperparameter tuning, cross-validation
- **Deep Learning**: Neural network implementation with PyTorch
- **Model Evaluation**: Metric selection, confusion matrices, performance interpretation
- **Programming**: Python, Pandas, Scikit-learn, XGBoost, PyTorch, Jupyter Notebooks

