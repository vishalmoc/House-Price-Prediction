# House-Price-Prediction
Predicting House Sale Prices (SalePrice) using Multiple Linear Regression in R 
House price prediction is a crucial task in real estate and finance. This project aims to develop a Multiple Linear Regression (MLR) model to predict house prices based on various factors such as lot area, building type, and condition. The dataset used contains multiple attributes affecting sale price.
Methodology
1. Data Preprocessing
•	Loading the dataset from a CSV file.
•	Handling missing values by removing rows with null entries.
•	Dropping irrelevant columns (e.g., ID).
•	Encoding categorical variables appropriately.
2. Exploratory Data Analysis (EDA)
•	Visualizing sale price distribution using histograms.
•	Identifying outliers using scatter plots.
•	Computing correlations between numeric variables using heatmaps.
•	Removing extreme values in Lot Area to prevent skewed predictions.
3. Model Development
•	Splitting the dataset into 70% training and 30% testing data.
•	Implementing a Multiple Linear Regression Model.
•	Checking for multicollinearity using Variance Inflation Factor (VIF).
4. Model Evaluation
•	Making predictions on test data.
•	Computing evaluation metrics: 
o	Root Mean Square Error (RMSE)
o	R-Squared & Adjusted R-Squared
•	Visualizing model performance using residual plots.
Findings
•	Correlation analysis showed strong relationships between sale price and factors like lot area and building type.
•	Outlier removal improved model performance.
•	Multicollinearity check (VIF) ensured that independent variables were not highly correlated.
•	Multiple Linear Regression model provided good predictive accuracy with an acceptable RMS

Conclusions
•	The model successfully predicts house prices based on available data.
•	Features such as Lot Area, Building Type, and Year Built significantly influence sale price.
•	MLR model performance is acceptable but could be improved by including advanced regression techniques.
•	Future work may involve feature engineering and hyperparameter tuning to enhance predictions.
