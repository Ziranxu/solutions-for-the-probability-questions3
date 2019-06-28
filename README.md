# solutions-for-the-probability-questions3

1  Generate random samples size 100 and size 1000 for the Sun City example using any software. First, use the ”fair coin” proposal, 
and then apply accept/reject technique from Section 4.1. Compare the resulting estimates of the long-term proportion of rainy days with 
the theoretical probability 0.25.

2  Implement IMA (using any software) to estimate posterior mean with Poisson likelihood for the data x = (3,1,4,3,2) and exponential prior with
the mean 2, also known as Gamma(1,0.5). Choose an exponential proposal density with the parameter value you consider the best. Modify 
the proposal if you need it badly enough. Use sample size N = 1000. Draw relevant graphs: trace plot,histogram, and sample autocorrelation
function.

3  Implement RWMHA (using any software) to estimate posterior mean with Poisson likelihood for the data x = (3,1,4,3,2) and exponential 
prior with the mean 2, also known as Gamma(1,0.5). Choose a normal proposal density with the parameter value σ you consider the best. 
Modify the proposal if you need it badly enough. Use sample size N = 1000. Draw relevant graphs: trace plot, histogram, and sample
autocorrelation function.
4  Calculate Geweke statistics for the chains obtained in Exercise 3.2 and Exercise 3.3. Compare these values.

5  Calculate Gelman-Rubin shrink factors for the chains obtained in Exercise 3.2 and Exercise 3.3. Compare these values.

6  Apply burn-in with b = 0.1N and b = 0.5N for the chain obtained in Exercise 3.2. Apply skip with k = 10. Does burn-in or skip or 
both improve your estimates?

7  Apply burn-in with b = 0.1N and b = 0.5N for the chain obtained in Exercise 3.3. Apply skip with k = 10. Does burn-in or skip or both 
improve your estimates?

8  Calculate Geweke statistics for the chains obtained in Exercise 3.6 and Exercise 3.7. Compare these values
