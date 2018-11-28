### kernel density estimation using gaussian kernels

This the nice way of creating pdf's using the histogram's, we basically smoothen the histogram until we get a less jagged distribution

How to do it??

<img src="assets/kernel density estimation using gaussian kernels-6a5b18d5.png" width="800" /> 

The above is the image of performing kde. We first plot the histogram as seen above and then we plot mini gaussian kernel for every point we plotted to the x axis depending on the density of the points the number of kernel increase and depending on how spread they are in the x axis the traffic of kernel will react

At every point in x axis, We draw a perpendicular line to the ceiling and calculate how many gaussian mini kernel's intersect the line for every point

for example for a point x=1.2 if the number of kernels are 5, We calculate the y axis value for each intersecting kernel and add them to plot the pdf at that point and after plotting all the points we get the pdf of the distribution which mayt be jagged and depending on the bin size we can smooth out the pdf
