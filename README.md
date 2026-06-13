> 98.31% accuracy | 5,630 customers | Random Forest
# E-Commerce Customer Churn Prediction

A machine learning project that predicts which customers are likely to stop using an e-commerce platform. By identifying at-risk customers early, businesses can take action to retain them and reduce revenue loss.

## Problem Statement

E-commerce platforms lose customers every day without knowing why or who is next. This project solves that by analyzing customer behavior and building a model that predicts churn before it happens — so businesses can focus their retention efforts on the right people.

## Dataset

- Source: Kaggle E-Commerce Dataset
- 5,630 customer records
- 20 features including Tenure, Cashback Amount, Order History, Satisfaction Score, and Warehouse Distance

## Models Compared

| Model | Accuracy |
|-------|----------|
| Logistic Regression | 89.08% |
| Decision Tree | 96.36% |
| Random Forest | 98.31% |

Random Forest gave the best accuracy of 98.31% and was selected as the final model.

## Key Findings

These are the top features that influence whether a customer churns:

1. Tenure — 23.0% importance. Newer customers are far more likely to churn.
2. Cashback Amount — 10.6% importance. Customers who receive less cashback tend to leave.
3. Warehouse to Home Distance — 7.1% importance. Longer delivery distances increase churn risk.

## Project Steps

1. Data Loading and Exploration
2. Data Cleaning and Missing Value Treatment
3. Exploratory Data Analysis
4. Feature Engineering and Encoding
5. Model Training and Comparison
6. Feature Importance Analysis
7. Real-time Churn Prediction

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- Matplotlib and Seaborn
- Google Colab

## How to Run

1. Open the notebook in Google Colab
2. Upload the E Commerce.xlsx dataset
3. Run all cells from top to bottom
4. The last cell lets you predict churn for any customer

## Business Impact

- Know which customers are about to leave before they actually do
- Run targeted retention offers instead of wasting budget on everyone
- Improve cashback strategies and delivery experience based on real data
- Reduce customer acquisition costs by keeping existing customers happy

## Author

Sanivarapu Deekshitha
3rd Year B.Tech CSE — Vignan University, Guntur
GitHub: github.com/deekshitha875
Email: vu.241fa04797@gmail.com
