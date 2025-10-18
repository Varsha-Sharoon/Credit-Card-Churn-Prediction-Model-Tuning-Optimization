# Credit-Card-Churn-Prediction-Model-Tuning-Optimization
This project aims to help Thera Bank identify customers likely to discontinue credit card services. By analyzing customer demographics, spending behavior, and engagement, predictive models were tuned to maximize accuracy and support customer retention strategies.

Tools & Technologies Used :- 
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Category Encoders, Imbalanced-Learn, RandomizedSearchCV

Steps / Workflow :- 
Imported and cleaned 10,127 records with 21 attributes using Pandas (missing value treatment and outlier capping).
Performed EDA (univariate & bivariate) to study patterns in customer demographics and spending.
Engineered features like Credit Utilization Ratio and encoded categorical variables using One-Hot Encoding.
Trained multiple regression models: Decision Tree, Random Forest, Gradient Boosting, AdaBoost, and Bagging Regressor.
Applied RandomOverSampler to handle imbalance and RandomizedSearchCV for hyperparameter tuning.

Results / Output :-

Best Model: Gradient Boosting

Mean Absolute Error (MAE): 349.68

Mean Squared Error (MSE): 333,224

R² Score: 0.97 (explains 97% of data variance)

Outperformed Random Forest (R² = 0.93) and AdaBoost (R² = 0.59).

Conclusion / Insights :-

Gradient Boosting provided the most accurate predictions with minimal errors.
Loyal and high-transaction customers are key contributors to bank profits.
Customers with low spending should be targeted with personalized offers, loyalty benefits, and engagement campaigns.
