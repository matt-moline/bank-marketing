# bank-marketing
# Bank Marketing Campaign Classifier Comparison

This repository contains a Jupyter Notebook that compares the performance of various classifiers (k-nearest neighbors, logistic regression, decision trees, and support vector machines) using a dataset related to the marketing of bank products over the telephone. The dataset is sourced from the UCI Machine Learning Repository.

## Business Understanding

The objective of this analysis is to increase the efficiency of directed marketing campaigns by predicting the likelihood of a client subscribing to a term deposit. This will help in better management of resources by targeting the most promising clients.

## Dataset

The dataset used is the Bank Marketing dataset from the UCI Machine Learning Repository. It contains information on multiple marketing campaigns conducted by a Portuguese bank.

- [Dataset URL](https://archive.ics.uci.edu/ml/datasets/bank+marketing)

## Methodology

The analysis follows the CRISP-DM (Cross-Industry Standard Process for Data Mining) methodology, which includes the following phases:

1. **Business Understanding**
2. **Data Understanding**
3. **Data Preparation**
4. **Modeling**
5. **Evaluation**
6. **Deployment**

## Steps

### 1. Business Understanding

The goal is to predict whether a client will subscribe to a term deposit based on their characteristics and the campaign data.

### 2. Data Understanding

- Load the dataset.
- Explore the data (check for missing values, data types, basic statistics).

### 3. Data Preparation

- Handle missing values.
- Encode categorical variables.
- Normalize numerical features if necessary.
- Split the data into training and testing sets.

### 4. Modeling

Four classifiers are used for comparison:
- K-Nearest Neighbors (KNN)
- Logistic Regression
- Decision Trees (DT)
- Support Vector Machines (SVM)

### 5. Evaluation

The models are evaluated based on the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC

### 6. Deployment

The best model and insights are documented, and recommendations for improving marketing campaigns are provided.

## Results

The Support Vector Machine (SVM) classifier provided the highest ROC AUC score, indicating it is the best model for this dataset.

## Findings and Recommendations

1. **Model Performance:**
   - The SVM classifier showed the highest performance in terms of ROC AUC score.

2. **Actionable Insights:**
   - Increasing the duration of phone calls may improve success rates.
   - Conduct marketing campaigns during the last month of each trimester to improve success rates.

## Dependencies
The following Python libraries are required:

- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Contributing
Contributions are welcome! Please feel free to submit a Pull Request.

## License
This project is licensed under the MIT License.

## Authors
Matt Moline

## Acknowledgements
This analysis is based on the CRISP-DM methodology as outlined in the provided article by Sérgio Moro, Raul M. S. Laureano, and Paulo Cortez.
