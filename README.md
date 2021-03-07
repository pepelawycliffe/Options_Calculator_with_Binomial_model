# Options_Calculator_with_Binomial_model
Binomial model is arguably the simplest techniques used for option pricing. In this calculator, the options price will be calculated by two binomial-tree methods,Cox-Ross-Rubinstein and Jarrow-Rudd (the equal-probability model).   Each of the approaches has its advantages and disadvantages for pricing different types of options. However, they all involve a similar tree-step process.  * There are only two possible prices for the underlying asset on the next day. * The two possible prices are the up-price and down-price * No dividends are paid out during the option’s life. * The risk-free rate is constant throughout the life of the option * There are no transaction and commissions costs in buying the option. * Investors are risk neutral


<h4>All trees are built from four parameters (u, d, p and q). </h4>
- The parameters u and d are how much the underlying will go up or down in each discrete time. 
- The parameters p and q are the probabilities for the price to go up and down respectively. Moreover, assume p+q=1.

<h4>Python Resources:</h4>

* Pandas: Pandas is a Python package for data analysis. In particular, it offers data structures and operations for manipulating numerical tables and time series. 

* Numpy: Numpy is a fundamental package to support for multi-dimensional arrays and matrices. It is not only used for scientific computing, but also for multi-dimensional container of generic data.

* Math: Math provides access to the mathematical functions, such as pi, log, exp, sqrt, and other mathematical functions.  

* Statistics: Statistics provides access to the statistics functions, such as norm_pdf, norm_cdf, mean, stdev, and other statistics functions.

* matplotlib.pyplot

* datetime
