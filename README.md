# Blood Donation Prediction

## Project Overview
Blood Donation Prediction is a machine learning project developed to identify whether a donor is likely to donate blood in the future based on their previous donation history. This project can help blood banks focus on potential donors and improve blood collection strategies.

## Problem Statement
The objective of this project is to build a predictive model that can predict whether a person will donate blood in the future using historical donation data.

## Dataset Information
The dataset contains donor-related information such as:

- Recency (Months since last donation)
- Frequency (Total number of donations)
- Monetary (Total blood donated in c.c.)
- Time (Months since first donation)
- Target Variable (Whether the donor donated blood)

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Exploratory Data Analysis (EDA)

The following analyses were performed:

- Data overview and summary statistics
- Missing value analysis
- Distribution plots
- Box plots for outlier detection
- Correlation heatmap
- Target variable distribution
- Feature relationship analysis

## Data Preprocessing

- Data cleaning
- Feature selection
- Train-Test Split
- Feature Scaling (if required)

## Machine Learning Models

The following models were evaluated:

- Logistic Regression
- Decision Tree Classifier
- Random Forest Classifier

## Model Evaluation Metrics

The models were evaluated using:

- Accuracy Score
- Precision Score
- Recall Score
- F1 Score
- Confusion Matrix

## Results

The best-performing model was selected based on evaluation metrics and its ability to accurately predict future blood donors.

## Project Structure

Blood-Donation-Prediction/
│
├── data/
├── notebooks/
├── images/
├── reports/
├── README.md
└── requirements.txt

## Key Insights

- Donors who donated recently were more likely to donate again.
- Donation frequency strongly influenced future donation behavior.
- Regular donors showed higher chances of returning for donation.
- Historical donation patterns were effective predictors.

## Future Improvements

- Hyperparameter tuning
- Advanced ensemble models
- Deployment using Streamlit
- Integration with blood bank management systems

## Author

Likhitha  
Aspiring Data Analyst | Data Science Enthusiast
