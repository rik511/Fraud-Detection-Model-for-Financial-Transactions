# Fraud Detection Model for Financial Transactions

## Overview
This repository contains the solution to a project focused on detecting fraudulent transactions in a financial dataset. The solution includes data preprocessing, model development, and evaluation to predict and analyze fraudulent activities within a simulated financial environment.

## Project Structure
- `main.ipynb`: Jupyter notebook containing the full analysis, data preprocessing, model development, and evaluation.

## Business Context
The primary objective of this project is to develop a machine learning model to identify fraudulent transactions. The dataset consists of 6,362,620 rows and 10 columns, detailing various transaction types and their attributes.

## Data Dictionary
The dataset contains the following columns:
- **step**: Maps a unit of time in the real world (1 step is 1 hour of time, total steps: 744).
- **type**: Type of transaction (e.g., CASH-IN, CASH-OUT, DEBIT, PAYMENT, TRANSFER).
- **amount**: Amount of the transaction in local currency.
- **nameOrig**: Customer initiating the transaction.
- **oldbalanceOrg**: Initial balance before the transaction.
- **newbalanceOrig**: New balance after the transaction.
- **nameDest**: Recipient of the transaction.
- **oldbalanceDest**: Initial balance of the recipient before the transaction (Note: data for merchants, identified by 'M', is not available).
- **newbalanceDest**: New balance of the recipient after the transaction (Note: data for merchants is not available).
- **isFraud**: Indicates whether the transaction is fraudulent.
- **isFlaggedFraud**: Indicates illegal attempts (e.g., transferring more than 200,000 in a single transaction).

## Model Development
The fraud detection model was developed following standard procedures:
1. **Data Cleaning**: Addressing missing values, outliers, and multi-collinearity.
2. **Feature Selection**: Identifying significant variables to include in the model.
3. **Model Training**: Using various machine learning algorithms to train the model.
4. **Model Evaluation**: Assessing the model's performance using appropriate metrics.
5. **Insights & Interpretation**: Analyzing the key factors that predict fraudulent transactions and their practical implications.

## Key Insights
- Identification of key predictors of fraudulent transactions.
- Interpretation of these factors to understand the behavior of fraudulent activities.
- Recommendations for infrastructure updates to prevent fraud.
- Evaluation of the implemented actions to ensure their effectiveness.

## Instructions for Use
Clone this repository to your local machine.
   ```sh
   git clone https://github.com/yourusername/fraud-detection-model.git
```
   
## Installation

To run the notebook, you need to have Python and Jupyter Notebook installed. You can install the required packages using the following command:

```bash
pip install -r requirements.txt
