# World Bank Data Analysis with Python

### Introduction
This project covered *some strategies* applied for *data wrangling, engineering and reporting* with data set from **World Bank Demography and Census**. The purpose was to identify key factors influencing a country's GDP growth. The scope of this project was narrowed down to 13 countries in Central Asia including:
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
* Find null columns through sum nulls and correlation plot
* Replace null values with means and median of each column, or drop nulls

2. Data Engineering
* Correlation matrix
* Standard distribution plots of each attribute
* Central tendency and standard deviation calculations
* Linear regression

3. Reporting
* Bar plots of high correlated attributes influencing a country's GDP growth
* Pie chart of industrial shares to a country's GDP
* Scatter plot of correlation and residue between middle-class income and tax revenue gain
* Bar charts representing different percentages of population particiapting in each industry

