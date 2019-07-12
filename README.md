[image1]:variance-formula.png
[image2]:covxy.png
[image3]:covy.png
[image4]:SD.png
[image5]:covari.png
Explain the difference in the normalization constant in variance/covariance formula
Good starting point : https://stats.stackexchange.com/questions/17890/what-is-the-difference-between-n-and-n-1-in-calculating-population-variance

Variance :

In statistics, variance refers to the spread of a data set. It’s a measurement used to identify how far each number in the data set is from the mean.
A variance value of zero represents that all of the values within a data set are identical, while all variances that are not equal to zero will come in the form of positive numbers.
The larger the variance, the more spread in the data set.

A large variance means that the numbers in a set are far from the mean and each other. A small variance means that the numbers are closer together in value.

Formula for Variance:

![image1]

In this formula, X represents an individual data point, u represents the mean of the data points, and N represents the total number of data points.

We have 2 kinds of variance:
1. Population variance
2. Sample Variance

Difference between population & Sample Variance:

The main difference between population variance and sample variance relates to calculation of variance. Variance is calculated in five steps. First mean is calculated, then we calculate deviations from the mean, and thirdly the deviations are squared, fourthly the squared deviations are summed up and finally this sum is divided by number of items for which the variance is being calculated.

As per above formulae:


Example:

To find the Bloodpressure of 1000 people

Now, when the variance is to be calculated from population data, n is equal to the number of items. Thus if variance in blood pressure of all the 1000 people is to be calculated from data on blood pressures of all the 1000 people, then n = 1000. However when the variance is calculated from sample data 1 is to be deducted from n before dividing the sum of the squared deviations. Thus in the above example if sample data have 100 items, the denominator would be 100 – 1 = 99.

Summary:

Population variance refers to the value of variance that is calculated from population data, and sample variance is the variance calculated from sample data. Due to this value of denominator in the formula for variance in case of sample data is ‘n-1’, and it is ‘n’ for population data. As a result both variance and standard deviation derived from sample data are more than those found out from population data. Basically Population variance is unbiased and sample variance is biased.



2) How to calculate Covariance?

Vriance is usually calculated on single random variable, if there are 2 variables in which 1 is independent and other is dependent the n we calcluate covarinace

Covariance of 2 variables can be found by using cov(x,y)
![image2]
Covariance of 1 variables can be found by using cov(y,y)
![image3]

Now, we divide by total population.

![image5]
