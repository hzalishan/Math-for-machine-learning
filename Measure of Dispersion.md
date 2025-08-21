Measure of Dispersion
=====================

Introduction
------------

This lecture focuses on measures of dispersion in statistics, specifically **variance** and **standard deviation**. These concepts help quantify how spread out data points are around the mean. The formulas differ slightly depending on whether you have population or sample data.

Understanding Dispersion
------------------------

Consider two datasets: 2, 2, 3, 3 and 1, 1, 5, 5. Both can have the same mean, but their data points are spread differently.

- For 2, 2, 3, 3:  
    $$ \mu = \frac{2 + 2 + 3 + 3}{4} = 2.5 $$
- For 1, 1, 5, 5:  
    $$ \mu = \frac{1 + 1 + 5 + 5}{4} = 3 $$

Even with similar means, the second dataset has values farther from the mean, indicating greater dispersion.

Variance
--------

Variance measures how much data points deviate from the mean. For population data, it is:

$$ \sigma^2 = \frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2 $$

Where $N$ is the population size, $x_i$ are data points, and $\mu$ is the mean.

**Example:**  
Dataset: 2, 2, 4, 4  
Mean: $$ \mu = 3 $$
Squared deviations: $1, 1, 1, 1$  
Sum: $4$  
Variance: $$ \sigma^2 = \frac{4}{4} = 1 $$

**Another Example:**  
Dataset: 1, 1, 5, 5  
Mean: $$ \mu = 3 $$
Squared deviations: $4, 4, 4, 4$  
Sum: $16$  
Variance: $$ \sigma^2 = \frac{16}{4} = 4 $$

The second dataset has a higher variance, showing greater spread.

Sample Variance
---------------

For sample data, use:

$$ S^2 = \frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2 $$

Where $n$ is sample size, $x_i$ are sample points, and $\bar{x}$ is the sample mean. Dividing by $(n-1)$ corrects bias in estimating population variance.

Key Points
==========

- Variance and standard deviation measure data spread.
- Population variance divides by $N$; sample variance divides by $n-1$.
- Datasets with the same mean can have different variances, indicating different levels of dispersion.
