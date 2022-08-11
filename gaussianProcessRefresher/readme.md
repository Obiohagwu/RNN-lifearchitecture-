# Gaussian Processes
As far as I can recall, most of modern ML is based on the methods of bayesian inference and gaussian processes. To define a gaussian process, one could imagine a multivariate normal distribution, generally defined by an input value x, and a distribution over the mean(x) and a covariate function(y, y')

The crux of gaussian processes are it's mean and its covariance functors
Defined: 
We can say f is a function that samples x from a N-dimensional gaussian distribution defined by GP(m(x), k(x,x')), where m(x) is the mean, and k(.,.) is the covariance function showing the euclidean relationship between the joint variable distribution of the different variables
    f(x) $\sim GP(m(x), k(.,.))
