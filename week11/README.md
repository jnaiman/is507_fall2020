# Week 11: Multiple Linear Regression

Today we'll extend our Linear Regression to include multiple explanatory variables - Multiple Linear Regression.  We'll also talk about some of the issues that can arise with trusting p-values alone and address issues of "p-hacking" and "data dredging".

## Class outline

 1. [Lecture](lecture12_s2020_toupload.pdf)
 1. [Notebook #1: Starting Multiple Linear Regression](prep_intro_mlr_part1.ipynb)
	* See [as an Rscript](Rscripts/prep_week12_intro_mlr.R)	
	* Data:  beersbac.csv([view](../week11/beersbac.csv), [raw](https://raw.githubusercontent.com/jnaiman/is542_spring2020/master/week11/beersbac.csv))
	* Data:  snotel\_s.csv from [NRCS](http://www.wcc.nrcs.usda.gov/snotel/Montana/montana.html)([view](snotel_s.csv), [raw](https://raw.githubusercontent.com/jnaiman/is542_spring2020/master/week12/snotel_s.csv))
 1. [Notebook #2: Hubbles Law Take 2 - using Multiple Linear Regression](prep_HubbleRevisited_part2.ipynb)
	* See [as an Rscript](Rscripts/prep_week12_part2_HubbleRevisited.R)	
	* Data:  sn\_data\_out\_lg.csv([view](sn_data_out_lg.csv), [raw](https://raw.githubusercontent.com/jnaiman/is542_spring2020/master/week12/sn_data_out_lg.csv))
	
**Extra:** Hubble's data processing (Python) and original data [linked here](../week11/fullHubbleData).

## Reading

Multiple Linear Regression: OIS 8.1-8.3 & ISL 3.2-3.5

**Optional** Reading: MIS Ch. 8.1-8.3; Ch 2.8 (issues with p-values)

Packages to install (with command: install.packages("PACKAGE_NAME") or install.packages(PACKAGE_NAME) ):
  1. psych
  2. effects (Note: this may not install on all machines, but don't worry it is not essential)
  3. corrplot
  4. car
  5. manipulate
  6. tigerstats

## [Homework](homework.md)

## References
 
 * Montana's course - http://www.math.montana.edu/courses/s217
 * Hubble's law - http://adamdempsey90.github.io/python/dark_energy/dark_energy.html
 * Error bar example - http://www.phys.boun.edu.tr/~ozcan/lectures/phys443autumn13/classwork/fitting/fittingData_part2.html