---
layout: default
title:  Raphael Lab // Survival Analysis
container_css_class: container
---

#Accurate Genome-Wide Survival Analysis

##About
Current implementations of the log-rank test (R survdiff, SAS LIFETEST, etc.) are based on an asymptotic approximation for the distribution of the log-rank statistic that is not appropriate when the two populations to be compared are unbalanced, as it is the case when testing the association of a mutation with survival in genomic studies. This asymptotic approximation results in p-values that can be very different from the exact p-values, up to 7 orders of magnitude, and a large number of false discoveries are reported because of this difference. We have designed and implemented a method, now called ExaLT (Exact Log-rank Test) to compute a conservative approximation of the exact p-value. In particular, our method computes the p-value for the exact permutational p-value, that is more appropriate for testing the association of mutations with survival.

* [ExaLT in C++, and R](http://compbio-research.cs.brown.edu/projects/exactlogrank/ExaLT.zip)

A different p-value can be computed using a different null distribution (called conditional); while we suggest to compute the p-value from the permutational distribution (with the code above), we note that efficient implementations to compute the exact p-value from the conditional distribution are not available, and provide such an implementation in Matlab below:

* [exact conditional test in Matlab](http://compbio-research.cs.brown.edu/projects/exactlogrank/exact_conditional.zip)

<a name="download"></a>

##Downloads
* [ExaLT in C++, and R](http://compbio-research.cs.brown.edu/projects/exactlogrank/ExaLT.zip)
* [exact conditional test in Matlab](http://compbio-research.cs.brown.edu/projects/exactlogrank/exact_conditional.zip)

##Support

For more information, contact Fabio Vandin at vandinfa [at] cs.brown.edu. 

<a name="reference"></a>

##Reference
If you use our method in your research, please cite: 

>F. Vandin, A. Papoutsaki, B.J. Raphael, E.Upfal (2013) Genome-Wide Survival Analysis of Somatic Mutations in Cancer.
>*17th Annual International Conference on Research in Computational Molecular Biology (RECOMB 2013)*. [**Best Paper Award, RECOMB 2013**]
>[[Publisher Link]](http://link.springer.com/chapter/10.1007%2F978-3-642-37195-0_26)
