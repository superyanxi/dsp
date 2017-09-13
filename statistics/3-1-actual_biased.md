[Think Stats Chapter 3 Exercise 1](http://greenteapress.com/thinkstats2/html/thinkstats2004.html#toc31) (actual vs. biased)

resp = nsfg.ReadFemResp()  
hist = thinkstats2.Hist(resp.parity)  
pmf_actual = thinkstats2.Pmf(hist,label = "actual")   
def BiasPmf(pmf,label):  
    new_pmf = pmf.Copy(label=label)  
    for x,p in pmf.Items():  
        new_pmf.Mult(x,x)  
    new_pmf.Normalize()  
    return new_pmf  
BiasPmf(pmf_actual,"observed")   
pmf_biased = BiasPmf(pmf_actual,"observed")  
thinkplot.PrePlot(2)  
thinkplot.Pmfs([pmf_actual,pmf_biased])  
thinkplot.Show(xlabel="Number of Children",ylabel="PMF")  
