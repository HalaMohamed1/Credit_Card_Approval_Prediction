# Credit Card Approval Prediction

## Overview
This project uses Kaggle's **Credit Card Approval Prediction** dataset to predict whether clients are likely to repay loans on time (`Good`) or not (`Bad`). It involves data preprocessing, feature engineering, and training machine learning models to classify client repayment behavior.

## Dataset
The dataset consists of two tables:
1. **Table 1 (`application_record.csv`)**: Contains client demographic and financial information, such as marital status, gender, family size, and annual income.
2. **Table 2 (`credit_record.csv`)**: Contains client loan payment history.

The dataset is available on [Kaggle](https://www.kaggle.com/datasets/rikdifos/credit-card-approval-prediction/data).

## Project Workflow
### 1. Data Understanding
   - Explore the dataset structure and identify key features.
   - Understand the relationship between client attributes and loan repayment behavior.

### 2. Label Creation
   - Use loan payment history to classify clients as `Good` or `Bad` based on repayment behavior.

### 3. Data Integration
   - Merge the client demographic information with the generated repayment labels.

### 4. Data Preprocessing
   - Clean and preprocess the data.
   - Encode categorical variables and scale numerical features.

### 5. Model Training and Evaluation
   - Train supervised machine learning models such as:
     - Logistic Regression
     - Random Forest
     - Support Vector Machines (SVM)
   - Perform hyperparameter tuning using grid search and cross-validation.
   - Evaluate models using confusion matrix and classification reports.

### 6. Analysis and Justification
   - Select the best-performing model.
   - Provide insights and justifications for model performance.

## Technologies Used
- Python
- pandas, numpy
- scikit-learn
- Jupyter Notebook

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Credit-Card-Approval-Prediction.git
Install the required dependencies:
bash
Copy code
pip install -r requirements.txt
Usage
Open the Jupyter Notebook:
bash
Copy code
jupyter notebook Credit_Card_Approval_Prediction.ipynb
Run the notebook step by step to reproduce the analysis and predictions.
Results
The final model predicts client repayment behavior with high accuracy, providing valuable insights for financial decision-making.

License
This project is licensed under the MIT License - see the LICENSE file for details.
