## QQ Plot

qq plot is a good way of determining whether a sampple's of a given continuous rv is gaussian distributed or not

Let,
(x) - any distribution- with mean(mu) and std dev(sigma)
(Y) - normal distribution with mean(0) and stddev(1)

Step1: For every observation in (x) we sort them by ascending order and calculate the percentile for each sample

example - if we have 100 obervations and after sorting them by ascending order, For every yi we caluculate percentile where y1 is the first percentile and y2 is the second pecentile and so on for all observation in the list x

Perform the same for the gaussian distributed rv (y) i.e sort the observations in ascending order and calculate the percentile values for each of the observations in the list

Finally plot the percentiles of (x) and (y) together like (x1,y1) (x2, y2) all percentiles

If the graph of both rv's lie on a straight line, We the conclude the rv (y) is gaussian distributed rv

Note:

1. Depending on the number of observation the qq plot can change keep that in mind
2. in this we plot y axis in x and x in y
3. We can make this work for any distributions,

If x and y lie on a straight line where y is pareto then x is pareto
if y is log normal then x is log normal
This is not limited only to normal distribution
