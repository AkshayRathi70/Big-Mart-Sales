The goal of this project was to predict the sales of products at Big Mart stores using 2013 sales data. 
We began by importing essential libraries such as numpy, pandas, matplotlib, and seaborn for data manipulation and visualization.
The train and test datasets were combined for a comprehensive analysis. We performed univariate analysis to understand
the distributions of numerical data like Item MRP and the counts of categorical data such as Item Type.
Bivariate analysis was conducted to explore relationships between variables, such as Item Weight and Sales, using box plots and scatter plots.
Data cleaning involved fixing missing values, where Item Weight was imputed using the average weight for each item, and missing values in Outlet Size were replaced with "Small". 
Feature engineering included creating new features like item categories and outlet performance levels, and encoding categorical variables into numerical ones for modeling. 
We then split the data back into train and test sets, building and evaluating models using Linear Regression and Random Forest with cross-validation.
Finally, sales predictions were made and saved as CSV files for submission. This process ensured a thorough understanding, preparation, and robust modeling of the data to predict sales effectively.
