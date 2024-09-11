# Terro_Real_Estate
Terro's Real Estate Agency: Predicting House Prices

# Project Overview
The Terro's Real Estate Agency capstone project involves statistical analysis and predictive modeling to understand the factors influencing house prices in a given locality. By exploring and analyzing multiple variables, the project aims to provide actionable insights that will help the agency make data-driven decisions regarding property pricing.

# Key Objective
The primary objectives of this project are:

- Analyze house pricing data using statistical techniques.
- Generate summary statistics and visualize distributions to identify trends.
- Build regression models to predict average house prices using key variables.
- Provide recommendations for improving the accuracy of the agency’s pricing models and highlight any discrepancies in current pricing practices.

# Tools and Technologies Used
- Excel (Data Analysis Toolpak): For generating summary statistics, histograms, correlation, and covariance matrices.
- Regression Analysis: Built multiple linear regression models to predict house prices based on variables like LSTAT (percentage of lower status population) and AVG_ROOM (average number of rooms).

# Dataset
The dataset used in this project includes the following columns:

- CRIME_RATE: Crime rate in the locality.
- AGE: Proportion of owner-occupied units built before 1940.
- INDUS: Proportion of non-retail business acres per town.
- NOX: Nitrogen oxide concentration (air pollution).
- DISTANCE: Distance to employment centers.
- TAX: Property tax rate per $10,000.
- PTRATIO: Pupil-teacher ratio by town.
- AVG_ROOM: Average number of rooms per dwelling.
- LSTAT: Percentage of the lower-status population.
- AVG_PRICE: The average price of houses in the locality.

# Project Workflow
- Summary Statistics: Generated summary statistics for each variable to understand data distribution and identify outliers.
- Visualizations: Created a histogram of the AVG_PRICE variable and analyzed its distribution.
- Covariance and Correlation Analysis: Computed the covariance matrix and correlation matrix to identify the strongest positive and negative correlations between variables.
- Regression Modeling:
  - Model 1: Built a simple regression model with AVG_PRICE as the dependent variable and LSTAT as the independent variable.
  - Model 2: Created a multiple regression model using both LSTAT and AVG_ROOM to predict AVG_PRICE.
  - Model 3: Expanded the regression model to include all available variables.
 - Model 4: Refined the model by including only statistically significant variables.
Interpretation and Recommendations: Provided detailed insights from each model, along with recommendations for adjusting pricing strategies based on the regression outcomes.

# Conclusion
The project successfully identified key factors that significantly influence house prices. The models revealed:

- A strong negative correlation between the percentage of lower-status population (LSTAT) and average house prices.
- The number of rooms (AVG_ROOM) positively impacts house prices.
- Including more relevant variables in the regression model improves the prediction accuracy, as indicated by higher adjusted R-squared values.
