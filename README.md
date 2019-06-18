# Ames-House-price-prediction
The main aim of this project is to predict the house price based on the data available in Ames house price data set. The data set is also available in Kaggle. The tasks are divided into three parts.

1. Estimate the sale price of the properties based on their fixed characteristics, such as neighborhood, lot size, number of stories, etc.
2. Estimate the value of possible changes and renovations to properties from the variation in sale price not explained by the fixed characteristics. The goal is to estimate the potential return on investment when making specific improvements to properties.


The first part, to predict the price of properties based on their fixed characteristics involves the following steps,

- Data cleaning and detailed EDA for the fixed characteristics to identify the features that can affect the property prices
- Visualization of data using pandas, matplotlib and seaborn
- Find the features having low variance and also the features which are highly correlated and remove them
- Apply linear regression and tune hyperparameter to improve model performance.


For the second part, to predict the property prices based on renovatable features which were not explained by the fixed features involves following steps,

- Count the residuals(difference of the actual price and predicted price) and make them as a target instead of taking property price as a target.
- Considered only renoavtable features to estimate the sale price difference which is not explained by the model having fixed characteristics.
- Apply feature engineering to make new features which are more relevant to the sales price
- Apply feature selection by eliminating low variance and highly correlated features
- Apply linear regression and tune the hyperparameter to see how accurately your model can explain the variance which is not explained by the first model.
