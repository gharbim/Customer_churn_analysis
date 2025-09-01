# Customer_churn_analysis  

This project predicts **customer churn in the telecom industry** using machine learning. The goal is to identify customers likely to leave so that the company can take retention actions.  

##  Models  
- Logistic Regression  
- Decision Tree  
- Random Forest  
- AdaBoost  
- Gradient Boosting  
- XGBoost  

## Results  
- On the **original dataset** (imbalanced), models had high accuracy but failed to detect churners.  
- On the **undersampled dataset**, performance improved significantly.  
- **Best models:** Random Forest, Gradient Boosting, and XGBoost with **F1-Scores ≈ 0.90**.  

##  Tech Stack  
- Python, pandas, numpy  
- scikit-learn, xgboost, imbalanced-learn  
- matplotlib, seaborn  
