# Why Is Sample Variance Divided By *n*‒1?

## Sample vs. Population Variance

- **Population variance ($\sigma^2$):**
    $$
    \sigma^2 = \frac{\sum_{i=1}^{N} (x_i - \mu)^2}{N}
    $$
    - $N$: population size
    - $\mu$: population mean

- **Sample variance ($s^2$):**
    $$
    s^2 = \frac{\sum_{i=1}^{n} (x_i - \bar{x})^2}{n-1}
    $$
    - $n$: sample size
    - $\bar{x}$: sample mean

## Why Use *n*‒1?

Dividing by $n-1$ (not $n$) is called **Bessel's correction**.  
It adjusts for the fact that the sample mean $\bar{x}$ is estimated from the data, which reduces the number of independent values (degrees of freedom).

- Using $n$ underestimates the true population variance.
- $n-1$ corrects this bias, making $s^2$ an **unbiased estimator** of $\sigma^2$.

## Degrees of Freedom

- **Degrees of freedom:** Number of independent values that can vary.
- For sample variance, DOF is $n-1$ (since the mean is estimated from the sample).

## Summary

- Population variance divides by $N$ (mean known).
- Sample variance divides by $n-1$ (mean estimated).
- Bessel's correction ensures unbiased estimation.
- Degrees of freedom for sample variance is $n-1$.

