# Housing Price Prediction using Ridge and Lasso Regression

## General Information

This project is part of an academic assignment focused on predicting house prices using regression techniques with regularization. A US-based housing company, Surprise Housing, wants to enter the Australian market and is interested in understanding how different factors affect house prices. The idea is to build a predictive model that can estimate the actual value of a house and help the company decide whether to invest in a property or not.

The main business problem is to identify which variables play an important role in determining house prices and how well these variables explain the variation in prices. This understanding can help the management make informed decisions and focus on areas that can generate higher returns.

The dataset used for this project contains information related to house sales, including structural details, location-based features, and quality-related attributes. The target variable in the dataset is the sale price of the house.

## Approach

The analysis starts with loading the dataset and understanding the problem statement and data structure. Basic data cleaning is performed to handle missing values and remove columns with very high missing percentages. Exploratory Data Analysis (EDA) is carried out to understand the distribution of house prices and their relationship with key variables.

Categorical variables are converted into numerical form using one-hot encoding. The data is then split into training and testing sets to evaluate model performance on unseen data. Feature scaling is applied since Ridge and Lasso regression are sensitive to the scale of variables.

Both Ridge and Lasso regression models are built using cross-validation to find the optimal value of the regularization parameter (alpha). Model performance is evaluated using R-squared and RMSE metrics. Lasso regression is also used to identify the most important predictor variables.

## Conclusions

- Regularization techniques help in reducing overfitting and improving model generalisation.
- Lasso regression performs automatic feature selection, which makes the model easier to interpret.
- Variables related to overall quality, living area, and location have a strong influence on house prices.
- Even after removing some important variables, the model can still make reasonable predictions using other related features.

## Technologies Used

- Python - 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Acknowledgements

This project was completed as part of an academic learning exercise on regression and regularization techniques. The dataset and problem statement were provided as part of the coursework.

## Contact

Created by Kotresh T M

Email: tmkotresh@gmail.com
