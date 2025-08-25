# Customer Churn Analysis and Prediction

## Overview
This project implements a complete machine learning pipeline for analyzing and predicting customer churn using a telecom dataset (e.g., Telco Customer Churn from Kaggle). It covers data preparation, splitting, feature selection, model selection, training, and evaluation.

Key tasks:
1. **Data Preparation**: Load data, handle missing values, encode categorical variables.

2. **Data Splitting**: Split into training (80%) and testing (20%) sets.

3. **Feature Selection**: Select top features influencing churn (e.g., contract type, monthly charges, tenure).

4. **Model Selection**: Compare Logistic Regression, Decision Tree, Random Forest, and Gradient Boosting.

5. **Model Training**: Train models on selected features.

6. **Model Evaluation**: Assess using accuracy, precision, recall, F1-score, ROC-AUC, confusion matrix, and visualizations.

The pipeline is encapsulated in a `ChurnAnalysis` class for easy reuse.

## Dataset
- Source: [Telco Customer Churn on Kaggle](https://www.kaggle.com/datasets/blastchar/telco-customer-churn)
- File: `WA_Fn-UseC_-Telco-Customer-Churn.csv` (or rename to match your CSV path in the code).
- Place the CSV in the project root or update the path in the notebook.

## Requirements
- Python 3.11+ (tested on 3.11.13)
- Dependencies: See `requirements.txt`.

## Installation
### 1. Clone the repository:
```bash
git clone https://github.com/sameshbajracharya0337/Customer_Churn_Analysis_and_Prediction.git
cd Customer_Churn_Analysis_and_Prediction
```

### 2. Create and activate a virtual environment (optional but recommended):
```bash
python -m venv venv
source venv/bin/activate  # On Windows: venv\Scripts\activate
```
### 3. Install dependencies:
```bash
pip install -r requirements.txt
```


## Usage
### 1. Download the dataset CSV and place it in the project root (e.g., as `telco-customer-churn.csv`).

### 2. Open the Jupyter Notebook:

```bash
jupyter notebook customer-churn-analysis-and-prediction.ipynb
```

### 3. Update the CSV path in the `__init__` method if needed (e.g., `self.csv_file_path = 'telco-customer-churn.csv'`).

### 4. Run the cells sequentially. The pipeline will:

- Load and preprocess data.

- Split data.

- Select features.

- Train and evaluate models.

- Output results, metrics, and plots.

## Results
1. Best model is selected based on ROC-AUC.

2. Visualizations include feature importance, model comparisons, ROC curves, etc.

3. Example output: Confusion matrix, classification report, and recommendations for churn prevention.


