Running Median Indicator for MQL4
=============

This indicator computes the median of odd span. The median is described as the numerical value separating the higher half of a sample, or a probability distribution, from the lower half. It is often considered as one of the most robust smoothing operator in the presence of outlier values, and particularly more robust than the mean.

Calculation of medians is a popular technique in summary statistics and summarizing statistical data. A very nice property of the median is that the distance between the median and the mean is bounded by one standard deviation. The median is also a non-lagging operator.

The paradox is that it is almost impossible to find the median indicator in trading softwares. Moreover, straightforward implementations rely on array sorts, which is a very slow operation that does not scale up to long timeseries.

I therefore designed this running median operator which is incremental and therefore very fast. It is under the GNU public license.

![Screenshot](https://github.com/scoulondre/runningmedian/raw/master/img/Running_Median_Indicator.png)
