SSres       = SUM(y-yred)^2  residual sum of squares
SStotal     = SUM(y-yavg)^2  total sum of squares

R^2=1-(SSres/SStotal)

---

What is R-Squared 
R-squared is a statistical measure that represents the goodness of fit of a regression model. The value of R-square lies between 0 to 1. Where we get R-square equals 1 when the model perfectly fits the data and there is no difference between the predicted value and actual value.  However, we get R-square equals 0 when the model does not predict any variability in the model and it does not learn any relationship between the dependent and independent variables.

---

R == 1  --->passing to all datapoints(suspisous)

R ~=0.9 --->very good

R <=0.7 --->model is not great

R =0.4  --->model is terrible

---


 The more the value of the r-square near 1, the better the model is. 


 The main problem with R-squared is that the R-Square value always increases with an increase in independent variables irrespective 
 
 of the fact that where the independent variable is contributing to the model or not. This leads to the model having high variance if 
 
 the model has a lot of independent variables.

 ---


 AdjR^2 = 1 - ( (1 - R^2)(n-1)/(n-k-1))

Here R-square is the value that we calculate using the method explained above 
n is the total number of observations in the data 
k is the number of independent variables (predictors) in the regression model
