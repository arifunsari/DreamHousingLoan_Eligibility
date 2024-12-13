# Loan Eligibility Prediction using Machine Learning  

This project automates the **loan eligibility process** for Dream Housing Finance, enabling real-time predictions based on customer details such as gender, marital status, dependents, income, credit history, and property area.  

## Project Highlights  
- **Objective**: Identify eligible customers for home loans by analyzing demographic and financial data.  
- **Data Processing**:  
  - Comprehensive **EDA (Exploratory Data Analysis)** and data wrangling to prepare a clean dataset.  
  - Handled both categorical and continuous variables effectively for optimal ML model performance.  
- **ML Models Implemented**:  
  - Multiple algorithms were evaluated to ensure the best performance.  
  - **Accuracy Scores** for different models:  
    | ML Algorithm | Train Accuracy | CV Score | Test Accuracy |
    |--------------|----------------|----------|---------------|
    | Logistic Regression (LR) | 82%        | 82%      | 78%           |
    | K-Nearest Neighbors (KNN) | 77%        | 74%      | 74%           |
    | Support Vector Machine (SVM) | 82%    | 82%      | 78%           |
    | Decision Tree (DT)          | 82%      | 82%      | 78%           |
    | Random Forest (RF)          | 99%      | 82%      | 77%           |
    | AdaBoost (AB)               | 83%      | 83%      | 76%           |
    | Gradient Boosting (GB)      | 87%      | 82%      | 73%           |
    | Extreme Gradient Boosting (XGB) | 85%   | 82%      | 77%           |  

  - **Decision Tree (DT)** was selected as the best model with consistent accuracy across train, CV, and test datasets, balancing accuracy (82%) and computational efficiency.  

## Tools and Techniques  
- Data preprocessing and visualization: **Pandas, NumPy, Matplotlib, Seaborn**  
- Machine Learning: **Scikit-learn**  

## Key Takeaway  
This end-to-end project, developed from scratch, showcases the complete ML lifecycle—starting from data exploration and preprocessing to evaluating multiple models and selecting the best one. It automates loan eligibility prediction effectively, helping streamline the decision-making process.  

