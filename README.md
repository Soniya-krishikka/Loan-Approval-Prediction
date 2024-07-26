# Loan-Approval-Prediction

This project aims to predict loan approvals using machine learning techniques. The dataset contains various features related to loan applicants, and the goal is to build a predictive model to determine the likelihood of loan approval.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Preprocessing](#preprocessing)
- [Visualization](#visualization)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)

## Introduction

This project utilizes a dataset containing information about loan applicants to predict whether a loan will be approved or not. The project involves data cleaning, feature engineering, exploratory data analysis, and model building.

## Dataset

The dataset used in this project is `loan_approval_dataset.csv`, which contains the following features:

- Applicant Income
- Coapplicant Income
- Loan Amount
- Loan Amount Term
- Credit History
- Property Area
- And other relevant features

## Installation

To run this project, you need to have Python installed along with the following libraries:

```python
pandas
numpy
matplotlib
seaborn
scikit-learn
```

You can install these dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage

1. Clone the repository:

```bash
git clone https://github.com/Soniya-krishikka/loan-approval-prediction.git
```

2. Navigate to the project directory:

```bash
cd loan-approval-prediction
```

3. Open the Jupyter notebook:

```bash
jupyter notebook Loan_Approval_Prediction.ipynb
```

## Project Structure

- `Loan_Approval_Prediction.ipynb`: Main notebook containing the entire workflow.
- `loan_approval_dataset.csv`: Dataset used for prediction.

## Preprocessing

The preprocessing steps include:

1. Loading the dataset.
2. Handling missing values.
3. Encoding categorical variables.
4. Dropping unnecessary columns.

## Visualization

Several visualizations were created to understand the data better:

- Bar plots for categorical variables.
- Heatmap for feature correlations.
- Distribution plots for numerical features.

## Modeling

Machine learning models were built to predict loan approval status. The steps include:

1. Splitting the data into training and testing sets.
2. Training different models.
3. Evaluating model performance.

## Results

The results section includes model performance metrics such as accuracy, precision, recall, and F1 score.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or bug fixes.
