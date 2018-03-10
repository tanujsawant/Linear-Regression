# Linear Regression
Performed Linear Regression on the Kings County House Prices. Tested various hypothesis using OLS assumptions method. Explained methods how to perform transformations on the dependent variable when it is not normally distributed but skewed. Ploted various graphs and histograms to understand the effect of normal distribution vs a skewed one.
The motivation behind this exercise is to give a simple demonstration of how we can use pandas and a little bit of numpy and matplotlib and sklearn library to design a simple linear regression model.
I am using a very basic regression model which is based on OLS assumptions.

DATA:
For this particular assignment I have taken dataset from kaggle which is Kings county housing price dataset. This data set has 20 attributes and 21613 rows. 

Target Variable: Price(Which is the house Price) --- Continuous Variable

Predictor variables: 
1)Sqft_living - The size of house which is sqfeets. --- Continuous Variable
2)Bathrooms- The number of bathrooms in house. --- Discrete Variable
3)Bedrooms - The number of bedrooms in house. --- Discrete Variable 
4)Condition - This is the condition of house which is on scale of 5. --- Discrete Variable
5)Year - The Year during which the house was constructed. --- Discrte Variable

Hypothesis:
1) HO: NULL HYPOTHESIS - With increase in sqfeet there is no change in price.
   HA :ALTERNATE HYPOTHESIS - With increase in sqfeet there is change in price.
   
2) HO: NULL HYPOTHESIS - With increase in number of bathrooms there is no change in price.
   HA :ALTERNATE HYPOTHESIS - With increase in number of bathrooms there is change in price.
   
3) HO: NULL HYPOTHESIS - With increase in number of bedrooms there is no change in price.
   HA :ALTERNATE HYPOTHESIS - With increase in number of bedrooms there is change in price.
   
Data preperation:
We are selecting only 5 variables out of 20 for predicitng as we are considering only the variables which are intutive and easier to understand.
We are dividing the data into two different data frames.
x <- predictor variables
y <- Target variable

   

