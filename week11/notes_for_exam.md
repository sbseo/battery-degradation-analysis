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

  

9 14

