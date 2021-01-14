# Bigmart-Sales-Prediction
ML Model to predict sales of items in different outlets of Big Mart based on the attributes of items and outlets.

# Predictor Variables
1. Item_Weight
2. Item_Fat_Content
3. Item_Visibility
4. Item_Type
5. Item_MRP
6. Outlet_Establishment_Year
7. Outlet_Size
8. Outlet_Location_Type

# Target variable
Item_Outlet_Sales

# Libraries used
pandas , numpy, seaborn, adaboost, xgboost, 

# Result

 1. Linear Regression              - 1270.74970867903
 2. Random Forest                  - 1270.74970867903
 3. Random Forest after tuning     - 1152.48942855172
 4. Gradient Boosting              - 1150.46970405464
 5. Gradient Boosting after tuning - 1149.43582203782
 6. AdaBoosting                    - 1216.36386353516
 7. AdaBoosting after tuning       - 1199.66740647093

 Minimum RMSE score is for  Gradient Boosting after hyperparameter tuning
 This has resulted in top 10.6% of all participants for Analytics Vidhya Hackathon on Big Mart Sales
