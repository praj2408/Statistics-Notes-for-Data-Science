# Bassel's Correction

We use \( n - 1 \) in the formula for the sample standard deviation as part of Bessel's correction. This correction accounts for the fact that when we estimate the population standard deviation from a sample, the sample standard deviation tends to be biased, specifically underestimated.

Here's a more detailed explanation:

### Standard Deviation Calculation

1. **Population Standard Deviation (\(\sigma\))**: 
   \[
   \sigma = \sqrt{\frac{1}{N} \sum_{i=1}^{N} (x_i - \mu)^2}
   \]
   Here, \( N \) is the size of the population, \( x_i \) are the individual data points, and \( \mu \) is the population mean.

2. **Sample Standard Deviation (s)**: 
   \[
   s = \sqrt{\frac{1}{n-1} \sum_{i=1}^{n} (x_i - \bar{x})^2}
   \]
   Here, \( n \) is the sample size, \( x_i \) are the sample data points, and \( \bar{x} \) is the sample mean.

### Bessel's Correction

When calculating the sample variance and standard deviation, the term \( n - 1 \) is used instead of \( n \). This adjustment is known as Bessel's correction. It corrects the bias in the estimation of the population variance and standard deviation from a sample.

### Why Use \( n - 1 \)?

1. **Unbiased Estimator**: Using \( n - 1 \) instead of \( n \) provides an unbiased estimator of the population variance. Without this correction, the sample variance would tend to underestimate the true population variance. This underestimation happens because the sample mean \( \bar{x} \) is itself an estimate from the data and introduces some error.

2. **Degrees of Freedom**: The term \( n - 1 \) represents the degrees of freedom in the sample. When calculating the sample mean, one degree of freedom is "used up," leaving \( n - 1 \) degrees of freedom for estimating variability. This adjustment ensures that the sample variance and standard deviation more accurately reflect the variability in the population.

### Summary

In summary, Bessel's correction (using \( n - 1 \)) is used in the calculation of the sample standard deviation to correct for the bias in the estimation of the population variance and standard deviation, ensuring a more accurate and unbiased estimate.
