# week7

## Practice quiz

- Numerical variable vs categorical variable(as.factor)

  for a dose increase of 1 milligram per day : change slope of dose

- OJ == orange juice

  Ascorbic acid == VC

- Difference between a and b ->  a-b

## Quiz

- Use the additive model to estimate the **difference** in the change in average heart weight when body weight is increased by 1 kilogram between a male and female cats.

- confint() : use when estimating coefficients
- predict() : use when estimating response
- Use the first order terms as well as all two- and three-way interactions. -> $a*b*c$

- Always calculate from the web R 



# Week8

- sigma^2 = variance. Please note that sqrt is essential
- In billions means divide by **$10^9$**
- lm(y~x^2) (X) 
  ***lm(y~I(x^2)) (O)***

- Standardized residuals: rstandard(model)

- Don't confuse. life_model vs life_model_small
- coef: estimates for parameters vs pvalue: summary(model)$coefficients
- Use $\frac{4}{n}$ as the cutoff for labeling an observation influential => subset=cd < 4/n
- When dealing with $y$ transformation, $\hat{y} == exp(fitted(model))$ 
- Shakiro.test(resid(model)). Residual is resid(model)
- 9 14

# Week9

- **Partial correlation coefficient** ex) cor(resid(model1), resid(model2))

  Model1 = regressing response against all of the predictors except the predictor of interest

  Model2 = regressing the predictor of interest against the other predictors

- Vif: library(car)

- R squared: 1/(1-r_squared)

  You get the r_squared from the model where x5 is the response and the rest of the predictors as the predictors

- AIC(model1, model2) -> find small AIC

- $R^2$ VS Adjusted $R^2$

practice_quiz: 1,3,4

Quiz: 1,6

- What is the largest variance inflation factor? => It requires the value. Not the name of the factor
- 



# Week 10

- Log odds vs response
- Estimate the log-odds that a car vs estimate the probability that a car
  => predict() vs predict(type="response")
- How may predictor are used in this reduced model? Vs How may predictors are reduced in this reduced model?
- cv.glm(k=5)

5,9,10,11,12,14,15



One semester

cs445



Two semesters

cs445, cs446, cs598 



