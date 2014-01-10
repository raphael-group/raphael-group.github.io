---
layout: default
title:  Raphael Lab // Software
container_css_class: container
---

#software

##Accurate Genome-Wide Survival Analysis
Current implementations of the log-rank test (R survdiff, SAS LIFETEST, etc.) are based on an asymptotic approximation for the distribution of the log-rank statistic that is not appropriate when the two populations to be compared are unbalanced, as it is the case when testing the association of a mutation with survival in genomic studies. This asymptotic approximation results in p-values that can be very different from the exact p-values, up to 7 orders of magnitude, and a large number of false discoveries are reported because of this difference. We have designed and implemented a method, now called ExaLT (Exact Log-rank Test) to compute a conservative approximation of the exact p-value. In particular, our method computes the p-value for the exact permutational p-value, that is more appropriate for testing the association of mutations with survival.

* [ExaLT in C++, and R](http://compbio.cs.brown.edu/projects/exactlogrank/ExaLT.zip)

A different p-value can be computed using a different null distribution (called conditional); while we suggest to compute the p-value from the permutational distribution (with the code above), we note that efficient implementations to compute the exact p-value from the conditional distribution are not available, and provide such an implementation in Matlab below:

* [exact conditional test in Matlab](http://compbio.cs.brown.edu/projects/exactlogrank/exact_conditional.zip)

For more information, contact Fabio Vandin at vandinfa [at] cs.brown.edu. 
If you use our method in your research, please cite: 

F. Vandin, A. Papoutsaki, B.J. Raphael*, E.Upfal*. (2013) Genome-Wide Survival Analysis of Somatic Mutations in Cancer. *17th Annual International Conference on Research in Computational Molecular Biology (RECOMB 2013)*. [**Best Paper Award, RECOMB 2013**] [[Publisher Link]](http://link.springer.com/chapter/10.1007%2F978-3-642-37195-0_26)



##HotNet2: Network Analysis of Mutation Data
[HotNet project page](/projects/hotnet)

HotNet2 is an algorithm for the discovery of significantly mutated subnetworks in a protein-protein interaction network. HotNet2 uses an insulated heat diffusion model to simultaneously analyze both the mutations in and local topology of sets of proteins. We describe HotNet2 in a paper in submission. 

The pre-release of HotNet2 will be available soon. For more information or to become a beta-tester, contact Max Leiserson at mdml [at] cs.brown.edu.

##Multi-Dendrix: (Multiple Pathway De novo Driver Exclusivity)
[Multi-Dendrix project page](/projects/multi-dendrix)

Multi-Dendrix is an algorithm for the simultaneous discovery of multiple driver pathways using only somatic mutation data from a cohort of samples. Multi-Dendrix uses an integer linear program to identify pathway sets such that each pathway contains genes with approximately mutually exclusive mutations and high coverage of the sample set. We describe Multi-Dendrix in a paper in submission: 

M.D.M. Leiserson, D. Blokh, R. Sharan, *B.J. Raphael*. (2012) Simultaneous identifcation of multiple driver pathways in cancer. [In submission] 

We have released Multi-Dendrix as a Python package that includes functions for subtype and network analysis of Multi-Dendrix results.

Download the release on GitHub: [Multi-Dendrix (Version 1.0, January 28, 2013)](http://mdml.github.com/multi-dendrix)

##Dendrix: (De novo Driver Exclusivity)
[Dendrix project page](/projects/dendrix)

[Dendrix web server](http://ccmbweb.ccv.brown.edu/dendrix/)

Dendrix is an algorithm for discovery of mutated driver pathways in cancer using only mutation data. It finds sets of genes, domains, or nucleotides whose mutations exhibit both high coverage and high exclusivity in the analyzed samples. This algorithm is described in the paper:

F. Vandin, E. Upfal, B.J. Raphael. (2012) De novo Discovery of Mutated Driver Pathways in Cancer. *Genome Research*. 22(2):375-85. Epub 2011 Jun 7. [PDF Preprint](http://compbio.cs.brown.edu/publications/papers/Vandin_etAl_Dendrix_GRpreprint.pdf) [Publisher Link](http://dx.doi.org/10.1101/gr.120477.111) [Preliminary version accepted at *15th Annual International Conference on Research in Computational Molecular Biology (RECOMB 2011)*]

To download Dendrix see the [Dendrix project page](/projects/dendrix)

...
