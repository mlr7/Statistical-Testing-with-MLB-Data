# Statistical-Testing-with-MLB-Data
Exploring what statistical tests can teach us about the history of Major League Baseball (MLB)

![](img/dodgers_history_1.png)

## Python Libraries for Statistical Testing and Visualization

SciPy (https://pypi.org/project/scikit-posthocs/). Fundamental algorithms for scientific computing in Python

Pingouin (https://pypi.org/project/pingouin/). Pingouin is a statistical Python package based on Pandas.

Scikit-Posthocs (https://pypi.org/project/scikit-posthocs/). Statistical post-hoc analysis and outlier detection algorithms. 

Bioinfokit (https://pypi.org/project/bioinfokit/). Bioinformatics data analysis and visualization toolkit. (tukey hsd)

Seaborn (https://pypi.org/project/seaborn/). Statistical data visualization

## Datasets

The first dataset we will look at is the winning percentage of the Dodgers from 1884 through 2022. 

## Concepts

### T-Test

The T-Test is an inferential technique that compares the means of two groups of data. It is based on the t-distribution and is primarily used to determine whether there is a significant difference 
between the means of two independent groups. The results of a T-test tell us whether two groups are statistically different from each other, 
and can provide insight even when the data is small and noisy.

### P-Value

The P-value is the probability of obtaining the observed results or more extreme results if the null hypothesis is true. P-value can be understood
 as the probability of observing the data, given that the null hypothesis is correct. 
The value of the P-value indicates whether the null hypothesis should be accepted or rejected. Often, a P-value less than 0.05 is 
considered statistically significant, meaning that the observed results are 
unlikely to have occurred by chance. 

### Z-Score

The Z-score indicates the number of standard deviations that a data point differs from the mean of the distribution. Essentially, the Z-score indicates how far a value is from the average, expressed in standard deviations. It is calculated by subtracting the mean from the value of interest and dividing the result by the standard deviation. The Z-score standardizes the data and enables meaningful comparisons across different distributions. The Z-score is also a convenient tool for identifying outliers, as any observation with a Z-score greater than three or less than negative three is considered an extreme value under the assumption of Gaussian statistics. 

### T-Score

The T-score and Z-score are both measures of how far a data point or observation is from the mean of a distribution, expressed in standard deviations. However, the main difference between the two is that the Z-score is based on the standard normal distribution, which has a mean of zero and a standard deviation of one, while the T-score is based on the t-distribution, which has a mean of zero but a wider range of standard deviations than the normal distribution. The Z-score is used when the population standard deviation is known, while the T-score is used when the population standard deviation is unknown and must be estimated from the sample data. This makes the T-score more appropriate for small sample sizes, where the estimate of the population standard deviation is less precise. Another important difference is that the Z-score is more commonly used in statistical analysis than the T-score, as the normal distribution is more widely applicable to many types of data. The T-score, on the other hand, is primarily used in situations where the sample size is small or the population standard deviation is unknown.

### ANOVA

ANOVA (Analysis of Variance) determines whether there are significant differences between the means of two or more groups of data. ANOVA compares the variance between group means to the variance within groups, and uses the F-statistic to assess whether the differences observed are statistically significant. ANOVA is particularly useful for situations where there are multiple independent variables or factors that may influence the outcome of interest. By decomposing the total variance in the data into various components, ANOVA enables the identification of the sources of variation and can contribute to a deeper understanding of the underlying mechanisms driving the processes generating the data. 

In ANOVA, post-hoc testing refers to a statistical analysis performed after the initial ANOVA analysis to compare the means of individual groups and identify which groups differ significantly from each other. The role of post-hoc testing is to provide more detailed and specific information about the differences between groups, beyond the overall ANOVA results. This is particularly useful in situations where there are more than two groups, and the ANOVA analysis indicates a significant difference between groups but does not specify which groups are different. Post-hoc testing methods include Tukey's HSD (Honestly Significant Difference), Scheffe's test, and Bonferroni correction, among others. The use of post-hoc testing is essential to avoid making erroneous conclusions based on ANOVA results alone, as it provides more nuanced insights into the underlying patterns and relationships present in the data. 


