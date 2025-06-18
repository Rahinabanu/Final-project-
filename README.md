> Black Friday Sales Prediction:
> 
> Project Objective
>   
This project aims to build a machine learning model to predict the purchase amount of customers during Black Friday sales using demographic and transaction data. The objective is to help businesses understand purchase behavior and make informed decisions in personalized marketing and inventory planning.

 Dataset
Description: Contains purchase data of customers from a retail store during Black Friday. Includes features like Gender, Age, Occupation, City, and Product Categories.

🛠️ Workflow
> Data Preprocessing

Handled missing values

Encoded categorical variables (Gender, Age, City_Category, etc.)

Treated outliers in numerical features

> Exploratory Data Analysis (EDA)

Visualized purchase trends across demographics

Analyzed category-wise buying behavior

> Feature Engineering

Converted categorical variables using Label Encoding and One-Hot Encoding

Prepared final dataset for modeling

> Model Building

 *Compared multiple regression models:

 *Linear Regression

 *Random Forest

 *LightGBM

 *XGBoost
*Evaluated using R² Score, Mean Squared Error (MSE), and Root Mean Squared Error (RMSE)

> Model Selection

 *XGBoost performed the best with highest R² and lowest RMSE

> Model Improvement

 *Applied hyperparameter tuning using GridSearchCV

 *Final model showed improved R² and generalization on the test data



🧪 Final Evaluation Metrics

| Metric                  | Score            |
|-------------------------|------------------|
| R² Score                | 0.6687635813291015  
| Mean Absolute Error     | 2142.6571329819726   
| Mean Squared Error      | 8248070.503266843   
| Root Mean Squared Error | 2871.945421359334  



📦 Libraries Used
This project uses the following Python libraries:

- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn
- xgboost
- lightgbm
- catboost
- joblib

> Key Insights
 Age, Gender, and Product Categories play a significant role in purchase behavior.

Tuned XGBoost model outperformed all others, showing strong predictive capability.


> Future Enhancements
 *Apply more advanced techniques like Stacking or Neural Networks

 *Use recent data for real-time predictive modeling

 *Deploy the model using a Flask/Django web interface or Streamlit app



> Author
Name: Rahina Banu (Aspiring Data Analyst & UGC-NET Aspirant)

