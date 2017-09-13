[Think Stats Chapter 4 Exercise 2](http://greenteapress.com/thinkstats2/html/thinkstats2005.html#toc41) (a random distribution)

>> random_number = np.random.random(1000)  
random_number  
pmf = thinkstats2.Pmf(random_number)  
cdf = thinkstats2.Cdf(random_number)  
thinkplot.Cdf(cdf)  
thinkplot.Pmf(pmf)  
thinkplot.Config(xlabel="number",ylabel="probability")  
