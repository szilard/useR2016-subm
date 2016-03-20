### Proposal/submission for useR! 2016 talk

#### Title: Size of Datasets for Analytics and Implications for R

**Abstract:** With so much hype about "big data" and the industry pushing for distributed computing 
vs traditional single-machine tools, one wonders about the future of R. In this talk I will argue that
most data analysts/data scientists don't actually work with big data the majority of the time, therefore using 
immature "big data" tools is in fact counterproductive. I will show that contrary to widely-spread
believes, the increase of dataset sizes used for analytics has been actually outpaced in the last 10 years
by the increase in memory (RAM), making the use of single-machine tools ever more attractive.
Furthermore, base R and several widely used R packages have undergone significant performance improvements 
(I will present benchmarks to quantify this), making R the ideal tool for data analysis on even relatively 
large datasets. In particular, R has access (via CRAN packages) to excellent high-performance machine 
learning libraries (benchmarks will be presented), while high-performance and parallel computing facilities 
have been part of the R ecosystem for many years. Nevertheless, the R community shall of course continue 
pushing the boundaries and extend R with new and ever more performant features.

**A few of my blog posts/github repos this talk will be based on:**

**1.** Size of datasets used for analytics based on 10 years of surveys by KDnuggets. While reported dataset 
sizes have increased at 20%/year rate, RAM in typical servers/EC2 has increased at 50%/year (in average in
the last 10 years).
[Blog post here.](http://datascience.la/big-ram-is-eating-big-data-size-of-datasets-used-for-analytics/)

**2.** R 3.1 introduced huge improvements (in run time and memory footprint) 
in doing less copies when changing dataframes. `data.table` is one of the fastest data manipulation
libraries in the industry. [Blog post here](http://datascience.la/dplyr-and-a-very-basic-benchmark/)
and [another one/github repo here](https://github.com/szilard/benchm-databases). 
More results will be presented in the talk.

**3.** R has packages on CRAN interfacing to high performance open source machine learning tools. 
Benchmark of open source machine learning tools in this 
[blog post](http://datascience.la/benchmarking-random-forest-implementations/) (for random forests)
and for further algorihms in this [github repo](https://github.com/szilard/benchm-ml).

