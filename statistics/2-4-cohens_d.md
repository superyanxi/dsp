[Think Stats Chapter 2 Exercise 4](http://greenteapress.com/thinkstats2/html/thinkstats2003.html#toc24) (Cohen's d)

>>
live.totalwgt_lb  
firsts = live.totalwgt_lb[live["birthord"] == 1]  
Others = live.totalwgt_lb[live["birthord"] != 0]  
CohenEffectSize(firsts,Others)  
firsts.mean(),Others.mean()


In average, first babies are lighter than others,however the difference in means is 0.029   standard deviations,which is small  
