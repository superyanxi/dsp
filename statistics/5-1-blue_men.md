[Think Stats Chapter 5 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2006.html#toc50) (blue men)

#scipy.stats contains objects that represent analytic distributions    
import scipy.stats  
#For example scipy.stats.norm represents a normal distribution.  
mu = 178  
sigma = 7.7  
dist = scipy.stats.norm(loc=mu, scale=sigma)  
#A "frozen random variable" can compute its mean and standard deviation.  
dist.mean(), dist.std()  
#It can also evaluate its CDF. How many people are more than one standard deviation below the mean? About 16%  
dist.cdf(mu-sigma)  
#How many people are between 5'10" and 6'1"?  
xs, ps = thinkstats2.RenderNormalCdf(mu, sigma, low=0, high=8)  
thinkplot.Plot(xs,ps)  
abs(dist.cdf(177.8)-dist.cdf(185.4))  
