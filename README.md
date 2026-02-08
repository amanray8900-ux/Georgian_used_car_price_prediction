It is a georgian used car price dataset. I took this data set from kaggle. This data set has 19237 rows and 18 columns.

Our goal is to predict the price of the car based on the features of the car. We will use ML model to predict the price of the car.

It is quite complex task because the data is often noisy and requires cleaning before it can be used for modeling. 
So, I went through the cleaning phase where I performed *String to Numeric conversions* , *Missing value Imputation* and *Outlier Detection*.

We also performed *EDA* and *Feature engineering* to ensure the models could capture the nuances of the Georgian market.

Then, We have to find the best model for our car price prediction. Our aim to get R2 score of 0.75 or more and MAE less than 5000.

So, I experimented with several regression algorithms to compare their performance and understand which architecture best fits the data:

*Linear Regression*

*Support Vector Regressor*

*Decision tree* 

*Random forest Regressor*

*Xgboost Regressor*

And came up with two best model over this data and those are: *Random Forest Regressor* And *Xgboost Regressor*.

I performed Hyperparameter Tuning using *GridSearchCV* to fine-tune the model parameters and we concluded Random Forest Regressor as the best model with Final Results:R² Score: 0.755 (Exceeded target) and MAE: 4,037 (Well below the 5,000 limit).

This project demonstrates the full lifecycle of a data science project—from cleaning "messy" real-world data to deploying a high-accuracy predictive model.

Thank you for visiting this project.

I would love to have suggestions from you. You can mail me to amanray8900@gmail.com
