1: 문제를 끝까지 읽어야함. Alive 들의 나이

10: Lowerbound vs upper bound

12: # Test statistic for slope and intercept requires n-2 degree of freedom

13: Covariance Matrix 

X = cbind(1, x_values$x1, x_values$x2, x_values$x3)

Also, watch out for accessing element. Beta_22 == matrix[3,3]

Don't forget to add column for 1 when sd(C) se(C)



X = cbind(1, x_values$x1, x_values$x2, x_values$x3)
cov = solve(t(X) %*% X)

3 * sqrt(cov[3,3])



Magnitude 나오면 abs( )로 계산하기!!



SLR model assumes that **the reponse variable** follos normal distribution! (X)

$\sigma ^2$ 나오면 sqrt() 해야되는지 안해야되는지 반드시 보자!!

음수 복사까지 확실하게!!!



EST ± MARGIN 

EST ± XRIT * SE

Therefore, margin = length / 2



Single parameter test 

What is the p-value for testing H0:β1=0 vs H1:β1≠0*H*0:*β*1=0 vs *H*1:*β*1\\=0 in a multiple linear regression model with 5 predictors and 20 observations if the value of the t*t* test statistic is -1.3?



Greater or equal to 





