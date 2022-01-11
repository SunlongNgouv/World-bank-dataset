# World Bank Data Analysis with Python

### Introduction
This project covered *some strategies*, including *data wrangling, engineering and reporting*, with dataset from **World Bank Demography and Census** to identify key influential factors against GDP growth of each countries. The project scoped to 13 countries in Central Asia including:
1. Bangladesh
2. Bhutan
3. China
4. India
5. Kazakhstan
6. Kyrgyzstan
7. Maldives
8. Mongolia
9. Myanmar
10. Nepal
11. Sri Lanka
12. Tajikistan
13. Thailand	


### Python Libraries being used:
1. pandas
2. matplotlib.pyplot
3. seaborn   
4. numpy
5. math
6. statsmodels.api
7. pylab
8. statsmodels.stats import diagnostic
9. statsmodels.stats.outliers_influence import variance_inflation_factor
10. sklearn.linear_model import LinearRegression
11. sklearn.model_selection import train_test_split
12. sklearn.metrics import mean_squared_error, r2_score, mean_absolute_error
13. scipy import stats


### Data management strategy:
1. Data Wrangling 
* Find nulls through sum-nulls and correlation plot techniques.
* Replace null with proper values, like means, median or mode of each column, or drop rows containing nulls.
* Consult internet for key information to manipulate nulls.

2. Data Engineering
* Run correlation matrix to indenify relationship among columns.
* Plot out distributions of each attribute to find central tendency, skewness and outliers in the dataset. 
* Run linear regression to highly correlated varibles influencing the GDP growth.

3. Reporting
* Bar plots of high correlated attributes influencing a country's GDP growth
* Pie charts of industrial shares to a country's GDP
* Scatter plots of correlation and residue between middle-class income and tax revenue gain
* Bar charts representing different percentages of population particiapting in each industry
* Residual plots to reveal outliers
