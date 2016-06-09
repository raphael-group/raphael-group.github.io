---
layout: default
title:  Raphael Lab // GASV
container_css_class: container
---

#GASV & GASVPro: Geometric Analysis of Structural Variants

##About
GASV and GASVPro are software packages for analysis of structural variation from paired-end sequencing and/or array-CGH data. This software has been tested used to find structural variation in both normal and cancer genomes using data from a variety of next-generation sequencing platforms. It can be used to predict structural variants directly from aligned reads in SAM/BAM format.

GASVPro is a probabilistic version of our original GASV algorithm. GASVPro combines read depth information along with discordant paired-read mappings into a single probabilistic model two common signals of structural variation. When multiple alignments of a read are given, GASVPro utilizes a Markov Chain Monte Carlo procedure to sample over the space of possible alignments.

<a name="download"></a>

##Downloads
* Latest Versions: [GASV Google Code Downloads](http://code.google.com/p/gasv/downloads/list)
* GASVPro sample data set: [VenterChr17.tar.gz](http://compbio-research.cs.brown.edu/projects/gasv/VenterChr17.tar.gz)

##Support
Please see the [GASV Google Code site](https://code.google.com/p/gasv/).

For further support, contact gasv [at] cs.brown.edu.

<a name="reference"></a>

##References
The GASVPro algorithm is described in the following paper:

>S. Sindi, S. Onal, L. Peng, H. Wu, B.J. Raphael. (2012)
>An Integrative Probabilistic Model for Identification of Structural Variation in Sequencing Data.
>*Genome Biology* 13(3):R22. [[Publisher link]](http://genomebiology.com/2012/13/3/R22/abstract)

The original GASV method is described in the following paper:

>S. Sindi, E. Helman, A. Bashir, B.J. Raphael. (2009)
>A Geometric Approach for  Classification and Comparison of Structural Variants.
>*Bioinformatics*. 25: i222-i230.
>(Special issue for the Joint 17th Annual International >Conference on Intelligent Systems in Molecular Biology and 8th Annual International European Conference on Computational Biology (ISMB/ECCB 09)). [[Publisher Link]](http://dx.doi.org/10.1093/bioinformatics/btp208)

##Previous versions
These are for archival purposes. It is recommended to download the latest version from link above.

* Version 1.4 (3/5/2010): [Download](http://cs.brown.edu/~braphael/software/StructVar/GASV_RELEASE_1.4.tgz) | [Release notes](http://cs.brown.edu/~braphael/software/StructVar/RELEASE_NOTES.txt)  
What's new: see release notes

* Version 1.3 (1/19/2010): [Download](http://cs.brown.edu/~braphael/software/StructVar/GASV_RELEASE_1.3.tgz) | [Example BAM file](http://cs.brown.edu/~braphael/software/StructVar/Example.bam)  
What's new: New output formats, streamlining of BAM file handling, bug fixes.

* Version 1.2 (11/30/2009): [Download](http://cs.brown.edu/~braphael/software/StructVar/GASV_RELEASE_1.2.tgz)  
What's new: Improved handling of SAM/BAM alignment files, speed improvements, maxCliqueSize option.

* Version 1.1 (10/30/2009): [Download](http://cs.brown.edu/~braphael/software/StructVar/GASV_RELEASE_1.1.tgz)  
What's new: a preprocessor for SAM/BAM files, aCGH comparison, fusion gene detection, and more.