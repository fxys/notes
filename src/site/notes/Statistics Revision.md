---
{"dg-publish":true,"permalink":"/statistics-revision/"}
---

##### Sampling
- When carrying out a hypothesis test, sampling can be used when the population is too large, meaning it will be to time consuming and expensive to sample the whole population, and when sampling is destructive.
- The sample should be chosen randomly as this avoids bias and enables proper inference about the population to be taken.
- The larger the sample of the sampling frame, the better the data in the sample will represent the underlying population and the sample should be representative if used for hypothesis testing and the data should not be changed by act of sampling.
- There are many methods of sampling:
	- A simple random sample means each subject is the population is equally likely to be sampled so it avoids bias but it requires a complete sampling frame.
	- Stratified sampling ensures all strata/subgroups of the population are represented by taking a simple random sample from each strata of size: $\frac{sample \ size \times strata \ size}{population \ size}$ but it only works if each subject in the population can be split into distinct groups.
	- Systematic sampling is easier as it only requires a random starting point and is generally representative but it requires a complete sampling frame.
	- Quota sampling, opportunity sampling and self-selected sampling are not as effective as the sample might not represent the population and the choosing is non-random, introducing bias.
##### Probability
- For independent events, the occurrence of one event does not affect the chances of the other event occurring, as opposed to dependent events.
$$
\text{for indendent events A and B: } P(A \cap B)=P(A) \times P(B)
$$
- For conditional probabilities, draw a 2-way diagram and identify the given row and column.
- Given a set of n unique items, there are $n!$ ways of ordering all the items, ${}_n \mathrm{ P }_r$ ways of ordering r items from the set, and ${}_n \mathrm{ C }_r$ different subsets of size r. 
##### Binomial
- Requirements: known number of independent trials, with 2 outcomes for each trial (success and failure) and a fixed probability of success.
##### Poisson
- Requirements: events occur randomly, independently and at a uniform average rate of occurrence, with a similar mean and variance.
- The sum of the independent Poisson distributions will also be a distributed by a Poisson model.
- If a binomial distribution has a large number of trials (n), and small probability of success (p), it can be modelled with a Poisson model with parameter, np, as the mean will be close to the variance.
##### Geometric
- Requirements: two outcomes for each trials with a fixed probability of success, and independent trials are continued until a success is obtained so the number of trials is not fixed.
$$
for \ X \sim Geo(p) \implies P(X>r)=(1-p)^r
$$
##### Uniform
- Requirements: a fixed number of equally likely outcomes, each with the probability equal to $\frac{1}{n}$ and an expectance equal to the median of possible outcomes.
$$
\begin{align} \\
for \ X \sim \text{Uniform over the set } [1, 2, 3, \dots, n]  \\

E(X)=p \sum x_{i}=\frac{1}{n} \times \frac{n(n+1)}{2}=\frac{n+1}{2} \\
Var(X)=p \sum x^2_{i}-E(X)^2=\frac{1}{n} \times \frac{n(n+1)(2n+1)}{6}-\left( \frac{n+1}{2} \right)^2 \\
=(n+1)\left(  \frac{2n+1}{6} - \frac{n+1}{4} \right)=\frac{n^2-1}{12}
\end{align}
$$
##### Hypothesis testing
- The significance level of a hypothesis test ($\alpha$) is the probability of rejecting the null hypothesis when the null hypothesis is true and it shows the strength of the evidence that must be present in a sample to reject the null hypothesis.
- A smaller significance level provides stronger evidence for a conclusion of the test as it makes it harder to reject the null hypothesis as it leads to a greater critical value.
- The outcome of a hypothesis test will either be 'reject $H_{0}$' or 'do not reject $H_{0}$' which will allow for a conclusion to be made if there is sufficient and statistically significant evidence, or insufficient evidence.
- If a p-value of a test is less than the significance level of the test, the null hypothesis is rejected and the critical region is the range of values that lead to the null hypothesis to be rejected.
#### PMCC
- Before doing a Pearson's Product Moment Correlation Test, a scatter graph should be drawn to identify the shape of the data, identify the outliers, and ensure the data is linear with either a positive or negative correlation.
- Requirements: the data on the scatter graph should be approximately elliptical in shape, which suggests that the underlying population from which the data is drawn from has a bivariate normal distribution, and the data should be random-on-random.
- The hypothesis are defined in terms of $\rho$, the population PMCC between the two variables.
- The conclusion will be 'there is sufficient evidence at $\alpha = \dots$ to suggest that there is (positive/negative/some) correlation between the two variables in the underlying population'.
- As the sample size used increases, the critical value become smaller so a small PMCC value may be significant, which means it is more useful to analyse this value in terms of effect size, for example, a large effect size means that the finding of the test has practical significance.
##### Spearman's
- Requirements: although a test using Spearman's rank correlation coefficient is non-parametric with no distributional assumption, the data must come from a random sample and the data must have a relationship between the variables.
- The test identifies if there is an association between two variables in the underlying population from which the sample data is drawn from.
- The conclusion will be 'there is sufficient evidence at $\alpha = \dots$ to suggests that there is (an/a positive/a negative) association between the two variables in the underlying population'.
##### Regression
- The x-axis should be a random variable or independent variable for a $y \text{ on } x$ line and the data should be linear, with few outliers.
- The point $(\bar{x}, \bar{y})$ lies on the line $y\text{ on }x$ and and $x \text{ on } y$.
- The greater the coefficient of determination, $R^2$, which is the square of the PMCC, the better the fit of the regression line.
$$
\text{residuals:  } \epsilon = y_{i}-(a+bx_{i}), \text{ such that } \sum \epsilon=0  
$$
- Interpolation by predicting values within the range of data can be reliable if the data is linear, and extrapolation should not be used as the prediction will not be reliable.
##### Chi-squared
- Chi-squared tests if variables are not independent of each other meaning there will be association.
- If the expected frequencies are less than 5, the Chi-squared test is not valid, so classes should be combined.
- If a parameter for a Chi-squared test is estimated, take 1 away from the degrees of freedom of the test.
- For a model goodness of fit test the null hypothesis is that the model is a good fit as the observed frequencies should follow the expected.
$$
\chi^2=\sum \frac{(f_{0}-f_{e})^2}{f_{e}}=\left(\sum \frac{f_{0}^2}{f_{e}}\right)-N
$$
##### Normal
- The normal distribution is a continuous distribution so there will be an infinite number of outcomes.
$$
for \ X \sim N(\mu, \sigma^2), \ P(X=k)=0
$$
- A normal distribution is unimodal and bell-shaped and symmetrical about $x=\mu$, so the mean, median and mode of the distribution will be equal, and there are 2 points of inflection at 1 standard deviation away from the mean.
- If a binomial distribution has a large number of trials (n), and a probability of success close to 0.5 (p), it can be modelled by a normal distribution with mean, np, and variance, np(1-p).
- Samples of the mean, numbering n, from a population distributed by a normal distribution will be distributed by a normal distribution with the same mean as the population and a standard deviation of $\frac{\sigma}{\sqrt{ n }}$.