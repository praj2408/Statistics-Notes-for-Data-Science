# STATISTICS

## Definition of Statistics:

Statistics is a branch of mathematics that involves collecting, organizing, analyzing, interpreting, and presenting numerical data. It provides methods and techniques for making inferences and decisions in the presence of uncertainty. The primary goal of statistics is to extract meaningful information from data, enabling us to understand patterns, relationships, and trends within the information available.

In essence, statistics allows us to make sense of the vast amounts of data that surround us in various fields such as science, economics, social sciences, engineering, and many others. It plays a crucial role in decision-making processes, research, policy formulation, and understanding the world around us.

# TYPES OF STATISTICS
Statistics can be broadly classified into two main types: descriptive statistics and inferential statistics.

## 1. Descriptive Statistics:
Descriptive statistics involve methods for summarizing and describing the main features of a dataset. These methods include measures of central tendency (such as mean, median, and mode), measures of dispersion (such as range, variance, and standard deviation), and graphical techniques (such as histograms, box plots, and scatter plots). Descriptive statistics help us understand the basic characteristics of the data, providing insights into its distribution, variability, and shape.

## 2.Inferential Statistics:
Inferential statistics involve using sample data to make inferences or predictions about a larger population. This branch of statistics allows us to draw conclusions, test hypotheses, and make predictions based on the analysis of sample data. Common techniques in inferential statistics include hypothesis testing, confidence intervals, regression analysis, analysis of variance (ANOVA), and correlation analysis. Inferential statistics enables researchers to generalize findings from a sample to the population, provided certain assumptions are met.


# Sampling Techniques
## 1. Simple Random Sampling:
In simple random sampling, each member of the population has an equal chance of being selected, and every possible sample of a given size has the same probability of being chosen. This method is often conducted using random number generators or drawing names from a hat. Simple random sampling is unbiased and ensures each member of the population has an equal opportunity to be included in the sample.

## 2. Stratified Sampling:
In stratified sampling, the population is divided into distinct subgroups or strata based on certain characteristics (such as age, gender, or income level), and then random samples are independently selected from each stratum. This method ensures that each subgroup is adequately represented in the sample, making it useful when certain subgroups are of particular interest or importance.

## 3. Systematic Sampling:
Systematic sampling involves selecting every kth member from a list or population, where k is a fixed interval calculated by dividing the population size by the desired sample size. The first element is randomly selected, and subsequent elements are chosen at regular intervals. Systematic sampling is relatively simple to implement and may be more efficient than simple random sampling when the population is large and organized.

## 4. Cluster Sampling:
In cluster sampling, the population is divided into clusters or groups, and a random sample of clusters is selected. Then, all members within the chosen clusters are included in the sample. Cluster sampling is often more practical and cost-effective than other methods, especially when the population is geographically dispersed or difficult to access.

## 5. Convenience Sampling:
Convenience sampling involves selecting individuals or items that are easily accessible or convenient for the researcher. This method is quick and inexpensive but may lead to biased results since it does not ensure representative sampling of the population. Convenience sampling is commonly used in pilot studies or situations where time and resources are limited.

## 6. Snowball Sampling:
Snowball sampling is a non-probabilistic sampling method where existing study subjects recruit future subjects from among their acquaintances. This technique is useful for sampling from hard-to-reach or hidden populations, such as homeless individuals or drug users. However, snowball sampling may introduce bias, as the sample is based on the connections and characteristics of the initial participants.


# Scale of Measurements

## 1. Nominal Scale:
- The nominal scale is the simplest level of measurement.
- It categorizes data into distinct categories or groups with no inherent order or ranking.
- Examples include gender (male, female), marital status (single, married, divorced), and types of cars (sedan, SUV, truck).
- Nominal data can be represented using labels, but mathematical operations such as addition and subtraction are not meaningful.
- Statistical analysis for nominal data typically involves frequency counts and percentages.

## 2. Ordinal Scale:
- The ordinal scale ranks data into ordered categories or levels, but the intervals between the categories are not uniform or measurable.
- While there is a meaningful order, the differences between categories are not necessarily equal.
- Examples include ranking satisfaction levels (very dissatisfied, dissatisfied, neutral, satisfied, very satisfied) or educational attainment (high school diploma, bachelor's degree, master's degree, Ph.D.).
- Ordinal data allow for comparisons of relative magnitude but do not support precise quantification of differences.
- Statistical analysis for ordinal data includes non-parametric tests such as the Mann-Whitney U test or Spearman's rank correlation.

## 3. Interval Scale:
- The interval scale has ordered categories with uniform intervals between them, but there is no true zero point.
- Intervals on the scale represent equal differences in the underlying attribute being measured.
- Examples include temperature measured in Celsius or Fahrenheit, where the difference between 20°C and 30°C is the same as the difference between 30°C and 40°C.
- Interval data support addition and subtraction operations but do not have a meaningful zero point.
Statistical analysis for interval data includes parametric tests such as t-tests and analysis of variance (ANOVA).

## 4. Ratio Scale:
- The ratio scale has all the properties of the interval scale but also has a true zero point, indicating the absence of the measured attribute.
- In addition to equal intervals, ratio scales allow for meaningful ratios between values.
- Examples include height, weight, time, and money.
- Ratio data support all mathematical operations, including multiplication and division.
- Statistical analysis for ratio data includes parametric tests similar to those for interval data, as well as descriptive statistics such as means and standard deviations.


# Co-variance and Co-relation
Covariance and correlation are both measures used to quantify the relationship between two variables in statistics, particularly in the field of multivariate analysis. While they are related concepts, they serve slightly different purposes and have different interpretations.

## Covariance:
Covariance measures the degree to which two variables change together. It indicates the direction of the linear relationship between the variables. A positive covariance indicates that the two variables tend to increase or decrease together, while a negative covariance indicates that one variable tends to increase as the other decreases.

However, covariance alone doesn't provide a clear indication of the strength or magnitude of the relationship. It's influenced by the scale of the variables, making interpretation challenging. The formula for covariance between two variables X and Y, based on a sample, is:
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/9e8341e4-a749-47fe-ba5c-9751de08520c)

## Correlation:
Correlation, on the other hand, standardizes covariance to provide a more interpretable measure of the relationship between two variables. It ranges between -1 and 1, where:

- A correlation of 1 indicates a perfect positive linear relationship.
- A correlation of -1 indicates a perfect negative linear relationship.
- A correlation of 0 indicates no linear relationship.
Correlation is dimensionless and not affected by changes in the scale of the variables. Pearson correlation coefficient is the most common measure of correlation for continuous variables. The formula for Pearson correlation coefficient between two variables X and Y is:
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/7b8554b6-6ccd-4d16-ac44-25873c09f6b0)

Correlation is widely used in various fields, including finance, economics, psychology, and biology, to assess the strength and direction of relationships between variables.
covariance measures the directional relationship between two variables, while correlation standardizes covariance to provide a more interpretable measure of the strength and direction of the relationship.

# Types of Correlation

## 1. Pearson Correlation (Linear Correlation):
- Pearson correlation coefficient measures the linear relationship between two continuous variables.
- It ranges from -1 to 1, where:
    - 1 indicates a perfect positive linear relationship,
    - -1 indicates a perfect negative linear relationship,
    - 0 indicates no linear relationship.
- It assumes that the variables have a normal distribution and linear relationship.
- Pearson correlation is widely used in many fields, especially when examining the association between two continuous variables.

## 2. Spearman Correlation (Rank Correlation):
- Spearman correlation coefficient assesses the strength and direction of association between two ranked (ordinal) variables.
- It is based on the ranks of the data rather than the actual values.
- Spearman correlation is robust to outliers and non-linear relationships.
- It is often used when the relationship between variables is monotonic but not necessarily linear, or when the data do not meet the assumptions of Pearson correlation.

## 3. Kendall's Tau:
- Kendall's Tau is another rank correlation coefficient that measures the association between two variables.
- It also uses the ranks of the data and is suitable for ordinal or ranked data.
- Kendall's Tau is particularly useful when dealing with small sample sizes.
- It is less sensitive to outliers compared to Pearson correlation.

## 4. Point-Biserial Correlation:
- Point-biserial correlation coefficient measures the association between a dichotomous variable (binary) and a continuous variable.
- It is used when one variable is continuous and the other is dichotomous.
- Point-biserial correlation is a special case of Pearson correlation.
- It is often used in studies involving experimental and control groups or in psychometrics.

## 5. Phi Coefficient:
- Phi coefficient is a measure of association between two dichotomous variables.
- It is similar to Pearson correlation but is specifically used when both variables are binary.
- Phi coefficient ranges from -1 to 1, with 0 indicating no association.
- These are the main types of correlations commonly used in statistics.
  
Choosing the appropriate correlation coefficient depends on the nature of the variables being analyzed and the assumptions underlying the data. It's essential to consider the characteristics of the data and the research question when selecting a correlation measure.

# Descriptive Statistics

1. Measures of Central Tendency
2. Measures of Dispersion
3. Frequency Distributions
4. Graphical Presentation of Data
5. Measures of Position
6. Probability Distributions
7. Summarizing Bivariate Data

## 1. Measures of Central Tendency

### 1. Mean:
- The mean is the most common measure of central tendency.
- It is calculated by summing all the values in the dataset and dividing by the number of observations.
- The formula for the mean is:
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/79a49731-08e6-4e9b-821c-254a0758fa72)
- The mean is sensitive to extreme values (outliers) and may not be representative of the data if the distribution is skewed.


### 2. Median:

- The median is the middle value of a dataset when the values are arranged in ascending or descending order.
- If there is an odd number of observations, the median is the middle value.
- If there is an even number of observations, the median is the average of the two middle values.
- The median is less affected by outliers and extreme values compared to the mean and is often used when the data is skewed or contains outliers.

### 3. Mode:

- The mode is the value that occurs most frequently in the dataset.
- A dataset may have one mode (unimodal), two modes (bimodal), or more than two modes (multimodal), or it may have no mode if all values occur with the same frequency.
- The mode is useful for categorical and nominal data, but it can also be applied to numerical data.
- Unlike the mean and median, the mode can be determined for any type of distribution.


## 2. Measures of Dispersion
Measures of Dispersion, also known as measures of variability or spread, quantify the extent to which the values in a dataset differ from the central tendency. They provide information about the spread, scatter, or variability of the data points. The main measures of dispersion include:

- Range
- Variance
- Standard Deviation
- Interquartile Range (IQR)

### 1. Range:

- The range is the simplest measure of dispersion.
- It is calculated as the difference between the maximum and minimum values in the dataset.
- While easy to compute, the range may be influenced by outliers and is not robust to extreme values.

### 2. Variance:

- Variance measures the average squared deviation of each data point from the mean.
- It provides a measure of the spread of the data around the mean.
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/b7994574-3337-4ef9-ae90-3a9a8f9905f2)
- Variance is sensitive to the units of measurement and can be difficult to interpret due to the squared values.
### 3. Standard Deviation:
- The standard deviation is the square root of the variance.
- It measures the average deviation of each data point from the mean.
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/bb8f7cc8-5a53-4595-b519-485b237b63be)
- Standard deviation is widely used because it is in the same units as the original data and provides a measure of the typical distance from the mean.

### 4. Interquartile Range (IQR):

- The interquartile range is a measure of the spread of the middle 50% of the data.
- It is calculated as the difference between the third quartile (Q3) and the first quartile (Q1).
- The IQR is robust to outliers and is often used to describe the variability of skewed distributions.

These measures of dispersion complement measures of central tendency by providing information about the variability or spread of the data. They are essential for understanding the distribution and characteristics of a dataset and are used in various statistical analyses and data visualization techniques.


## 3. Frequency Distributions
Frequency distributions are a way of organizing and summarizing data by displaying the number of times each value occurs in a dataset. This helps to understand the distribution or pattern of the data and identify any trends or outliers. The main components of a frequency distribution include:

### 1. Class Intervals or Categories:

Class intervals are the ranges into which the data values are grouped.
They divide the range of data values into smaller, manageable intervals or categories.
Class intervals should be mutually exclusive and collectively exhaustive, meaning that each data point falls into exactly one interval, and all data points are accounted for.

### 2. Frequency:

Frequency refers to the number of times a value or data point occurs within each class interval.
It represents the count or tally of observations falling within each interval.

### 3. Relative Frequency:

Relative frequency is the proport ion or percentage of observations within each class interval relative to the total number of observations.
It is calculated by dividing the frequency of each interval by the total number of observations and multiplying by 100 to express it as a percentage.

### 4. Cumulative Frequency:

Cumulative frequency is the running total of frequencies as you move through the intervals from the lowest to the highest.
It provides information about the number of observations below a certain value or within a certain range.
Frequency distributions can be presented in various formats, including:

Frequency Table: A table that lists the class intervals, frequencies, relative frequencies, and cumulative frequencies.
Histogram: A graphical representation of the frequency distribution, where the class intervals are shown on the x-axis and the frequencies are represented by the heights of the bars.
Frequency Polygon: A line graph that connects the midpoints of each class interval with lines to show the distribution of frequencies.
Cumulative Frequency Curve (Ogive): A graph that plots cumulative frequencies against the upper or lower class boundaries to display the cumulative distribution of the data.

Frequency distributions are fundamental in descriptive statistics as they provide a concise summary of the dataset's distribution and allow for visual interpretation of the data's patterns and characteristics.

## 4. Graphical Presentation of Data

Graphical presentation of data involves representing data visually using various types of graphs and charts. It is an essential aspect of statistics and data analysis because visualizing data can help reveal patterns, trends, and relationships that may not be apparent from numerical summaries alone. Some common types of graphical presentations of data include:

**Histograms:** Histograms are used to display the distribution of continuous data by dividing the data into intervals (bins) and plotting the frequency or relative frequency of observations within each interval as bars.

**Bar Charts:** Bar charts are used to display the distribution of categorical or discrete data. They consist of rectangular bars, with the length of each bar representing the frequency or relative frequency of observations in each category.

**Pie Charts:** Pie charts are used to represent the proportions or percentages of different categories within a dataset. Each category is represented by a slice of the pie, with the size of the slice proportional to the percentage of the whole.

**Line Graphs:** Line graphs are used to display trends or changes in data over time or across different conditions. They consist of points connected by lines, with the x-axis representing the independent variable (e.g., time) and the y-axis representing the dependent variable.

**Scatter Plots**: Scatter plots are used to display the relationship between two continuous variables. Each data point is plotted as a point on the graph, with one variable represented on the x-axis and the other variable represented on the y-axis.

**Box Plots** (Box-and-Whisker Plots): Box plots are used to display the distribution of a continuous variable and provide information about central tendency, dispersion, and skewness. The box represents the interquartile range (IQR), with the median line inside the box and the whiskers extending to the minimum and maximum values or to a certain distance from the quartiles.

**Histograms:** Histograms are used to display the distribution of continuous data by dividing the data into intervals (bins) and plotting the frequency or relative frequency of observations within each interval as bars.

**Heatmaps:** Heatmaps are used to represent the intensity or density of data values in a matrix format, with colors indicating the magnitude of the values.

These are just a few examples of graphical presentations of data. Choosing the appropriate type of graph or chart depends on the nature of the data and the specific objectives of the analysis. Graphical presentation of data enhances data exploration, communication, and interpretation, making it an essential tool in statistical analysis.



## 5. Probability Distributions

Probability distributions are mathematical functions that describe the likelihood of observing different outcomes of a random variable. They are essential tools in statistics and probability theory, used to model uncertainty and variability in various phenomena. Some of the main probability distributions include:

### 1. Discrete Probability Distributions:

**Bernoulli Distribution:** Models the probability of success (1) or failure (0) in a single trial of a binary experiment.
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/d6df4b1a-33e5-49aa-9ba9-3381271652e5)

**Binomial Distribution:** Describes the probability of obtaining a certain number of successes in a fixed number of independent Bernoulli trials.
![image](https://github.com/praj2408/Statistics-Notes-for-Data-Science.-Practical-and-Theory/assets/70437673/7a23d94b-2f17-4447-b018-2f73509a6c47)

**Poisson Distribution:** Models the number of events occurring in a fixed interval of time or space, given a known average rate of occurrence.
  
### 2. Continuous Probability Distributions:

- **Uniform Distribution:** Represents a constant probability over a range of values, with all outcomes equally likely.
- **Normal Distribution (Gaussian Distribution):** One of the most widely used distributions, characterized by a symmetric bell-shaped curve. It is governed by two parameters: the mean (μ) and the standard deviation (σ).
- **Exponential Distribution:** Models the time until an event occurs in a continuous process, such as the waiting time between successive events in a Poisson process.
- **Gamma Distribution:** Generalizes the exponential distribution and is used to model the waiting time for multiple events to occur in a continuous process.
- **Chi-Square Distribution:** Arises in statistical hypothesis testing and is used to model the distribution of the sum of squared standard normal deviates.
- **Student's t-Distribution:** Used in hypothesis testing for small sample sizes when the population standard deviation is unknown.
- **F-Distribution:** Arises in the analysis of variance (ANOVA) and is used to compare the variances of two or more populations.

These probability distributions have different shapes, parameters, and applications. Understanding them is crucial for performing statistical analyses, making predictions, and drawing conclusions in various fields such as science, engineering, finance, and social sciences.







































































