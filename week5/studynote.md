1: 문제를 끝까지 읽어야함. Alive 들의 나이

10: Lowerbound vs upper bound

12: # Test statistic for slope and intercept requires n-2 degree of freedom

13: Covariance Matrix 

X = cbind(1, x_values$x1, x_values$x2, x_values$x3)

Also, watch out for accessing element. Beta_22 == matrix[3,3]

Don't forget for sort when sd(C) se(C)



X = cbind(1, x_values$x1, x_values$x2, x_values$x3)
cov = solve(t(X) %*% X)

3 * sqrt(cov[3,3])



Magnitude 나오면 abs( )로 계산하기!!



SLR model assumes that **the reponse variable** follos normal distribution! (X)