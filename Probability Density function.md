### Intoduction to Distributions and probability density function

Distributions are simple models of natural phenomenon. Distibutions can give us many insights about the phenomenon of our interest. One such common distribution is Normal distribution or gaussia distribution(both are the same)

Many natural phenomenon follow this type of distribution such as heights and weights of human
1.Measurement errors in physical experiments are often modeled by a normal distribution.

2. Long duration rainfall and river discharge follows normal distribution
and many more follow gaussian distribution

Gaussian distribution is also called the bell curve which peaks at the centre and flatens out on the both sides

lets look at how it looks:

<img src="assets/Probability Density function-53e711fa.png" width="800" />

The biggest blue curves is the normal distribution curve in the diagram with the given mean(mu) and variance(sigmasquare). The curve is called the pdf of the gaussian distribution

So if you give me a random variable x along with its mean and variance, I can very well plot its pdf on the graph. We can caluculate the std deviation using the variance by taking the square root of it. So the parameters of normal distribution are mean and std deviation

Probability density function:
If we plot the mean and std dev of any continuous random variable which is normal distributed we get a pdf and if we plot the same parameters for a discrete random variable we get a prob. mass function. Mean is the peak of the pdf as we in the diagram

The curve at any given point gives the value of the component of x axis at that point. The PDF's are built on top of plotting the histogram's of the x component and smoothening the discrete points of the histogram using kernel density estimation

PLOTTING A PDF:

So for a continuos random variable (x) which we know is normally distributed if we plot the pdf of x, What we get is a bell curve

The simplified version of that formula is y=1/sqrt(2.pi)exp(1/2(-(x^2)))

So as x increase, y decreases square of exponentially and not exponentially which is what we see as a steep fall in the pdf of (x). Its also called y is reducing exponential of the square
