# airline-satisfaction


This project focuses on predicting airline passenger satisfaction based on multiple flight-related factors. Using machine learning models, we analyze customer feedback to classify passengers as satisfied or dissatisfied.

## Objective

The goal is to develop a model that accurately predicts customer satisfaction based on flight experience data.

## Dataset Overview

The dataset includes both numerical and categorical features:

- **Numerical Features**: Age, Flight Distance, Departure Delay, Arrival Delay, etc.  
- **Categorical Features**: Gender, Customer Type, Type of Travel, Class, etc.

## Data Processing Steps

- Handling missing values  
- Identifying and addressing outliers  
- Feature engineering (e.g., deriving Total Delay from delay columns)  

## Machine Learning Models

The following models were implemented and compared:

- Decision Tree  
- Random Forest  
- Support Vector Machine (SVM)  
- Neural Network  
- k-Nearest Neighbors (k-NN)  

## Model Performance

Evaluation metrics used:

- Accuracy  
- Precision  
- Recall  
- F1 Score  

Among all models, **Random Forest achieved the highest accuracy of 81%**.

## Running the Project

1. Clone the repository:  
   ```bash
   git clone https://github.com/safaeOulaja/airline-customer-satisfaction-prediction.git
   pip install scikit-learn seaborn matplotlib numpy scikit-plot
jupyter notebook

## Contributors

- [Benelfqih Aya](https://github.com/abenelfqih)  
- [Safae Oulaja](https://github.com/safaeOulaja)


