# Dystopia-of-Happy-Countries-using-Individual-and-Stacked-Regression-models

Link to the dataset:
https://www.kaggle.com/chhotanpanday/happinesss-1234


**Observations from the Pairplot:**
1. 'Happiness Score', 'Whisker.High', 'Whisker Low', 'Economy GDP Per Capita' and 'Dystopia Residual' have Standard Normal/ Gaussian distribution.
2. 'Family', 'Health Life Expectancy' and 'Freedom' are right-skewed, while 'Generosity' and 'Trust..Government.Corruption' are left-skewed.
3. 'Happiness Score' has a correlation coeffient of '+1' with 'Whisker.high', 'Whisker.low' and a high positive correlation coefficient with 'Economy..GDP.per.Capita.', 'Family', 'Health..Life.Expectancy.' and 'Freedom'. 
4. 'Whiskers.high' has a correlation coefficient of '+1' with 'Whiskers.low' and a high positive correlation coefficient with 'Economy..GDP.per.Capita.', 'Family', 'Health..Life.Expectancy.' and 'Freedom'.
'5. Whiskers.low' has a high positive Correlation Coefficient with 'Economy..GDP.per.Capita.', 'Family', 'Health..Life.Expectancy.' and 'Freedom'.
6. 'Economy..GDP.per.Capita.' has a high positive Correlation Coefficient with 'Family', 'Health..Life.Expectancy.' and 'Freedom'.
7. 'Family' has a high positive Correlation Coefficient with 'Health..Life.Expectancy.' and 'Freedom'.
8. 'Health..Life.Expectancy.' has a high positive Correlation Coefficient with 'Freedom'.
9. The dependent variable 'Dystopian Residual' shares a fair positive correlation coeffient of approximately 0.6 with 'Happiness.Score', 'Whisker.High' and 'Whisker.low'. It shows no correlation with the other features.

**Stacked Regression Model**
Base Model: 
1. Ridge Regression
2. KNN Regression
3. Random Forest Regression
4. Support Vector Regression
Meta Model: Ridge Regression

**Observations from the Model Scores and Parameters:**
1. Stacked Model offers best performance with the least negative mean score and least variance and Support Vector Regression gives the least desirable performance with the most number of outliers.
2. Ridge Regression and Stacked model produces an r2 score of more than 0.8. Hence, only these models can be used for multiple linear regression.
