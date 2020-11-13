# Visualizing-and-Predicting-World-Happiness


This notebook will explore the World Happiness Report data, part of the findings from the Gallup World Poll. A detailed explanation of the data can be found below:

The joy scores and rankings utilize information from the Gallup World Survey. The scores are based on answers to the most life evaluation address inquired within the survey. This address asks respondents to think of a scale with the most excellent conceivable life for them being a 10 and the most exceedingly bad conceivable life being a 0 and to rate their claim current lives on that scale. The columns taking after the bliss score assess the degree to which each of six variables – financial generation, social back, life anticipation, flexibility, nonattendance of debasement, and liberality – contribute to making life assessments higher in each nation than they are in Dystopia, a theoretical nation that has values rise to to the world’s least national midpoints for each of the six variables.

The Happiness Score is explained by the following factors:

- GDP per capita
- Healthy life expectancy
- Social support
- Freedom to make life choices
- Generosity
- Perceptions of corruption
- Residual error

The dataset we'll be using contains the Happiness Score for 153 countries along with the factors used to explain the score.


We will explore some visualizations to get a grasp of some trends in the data, then come up with our very own implementation of linear regression, using two different methods: the well-known gradient descent algorithm as well as solving the normal equations. Our implementation will only use relatively basic Python commands and common libraries such as NumPy and Pandas in order to carry out the necessary linear algebra operations. I will also include detailed step-by-step explanations throughout the code.

Linear regression is a linear approach to modeling the relationship between a response (or dependent variable) and one or more explanatory variables (or independent variables). We will try to use our regression model to predict the happiness of a country based on the various aforementioned factors (economic status, amount of social support, perceptions of corruption, etc.) and explore some ways in which we can use our insights gathered from EDA to add to and improve our model in the future.
