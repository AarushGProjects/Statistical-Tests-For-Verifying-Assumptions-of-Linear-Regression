# Real Estate Valuation (Verifying Assumptions of Linear Regression)

Linear Regression is a statistical technique that assesses a linear relationship between response variable and explanatory variables. To use linear regression, the data must meet the below assumptions.

The dataset provides real estate valuations which are collected from Bonston, Massachusetts.

CRIM: Per capita crime rate by town

ZN: Proportion of residential land zoned for lots over 25,000 sq.ft.

INDUS: Proportion of non-retail business acres per town.

CHAS: Charles River dummy variable (1 if tract bounds river; 0 otherwise)

NOX: Nitric oxides concentration (parts per 10 million)

RM: Average number of rooms per dwelling

AGE: Proportion of owner-occupied units built prior to 1940

DIS: Weighted distances to five Boston employment centers

RAD: Index of accessibility to radial highways

TAX: Full-value property-tax rate per $10,000

PTRATIO: Pupil-teacher ratio by town

LSTAT % lower status of the population

MEDV Median value of owner-occupied homes in $1000's

# Assumptions:

1. Linear Relationship: Scatter plot between target and response
2. Zero mean of residuals 
3. Homoscedasticity: Residual plot with Goldfeld Quandt test
4. No Multicollinearity: Heatmap with Variance inflation factor
5. Normal Residual distribution: QQ plot with Shapiro Wilk and Anderson Darling test
6. No Autocorrelation: ACF and PACF with Durbin Watson test

# View Notebook Here:
https://nbviewer.jupyter.org/github/AarushGProjects/Statistics-For-Verifying-Assumptions-of-Linear-Regression/blob/main/Assumptions_Linear_Regression.ipynb
