---
layout: default
title:  Raphael Lab // GASV
container_css_class: container
---

#GASV & GASVPro: Geometric Analysis of Structural Variants

##About
GASV and GASVPro are software packages for analysis of structural variation from paired-end sequencing and/or array-CGH data. This software has been tested used to find structural variation in both normal and cancer genomes using data from a variety of next-generation sequencing platforms. It can be used to predict structural variants directly from aligned reads in SAM/BAM format.

GASVPro is a probabilistic version of our original GASV algorithm. GASVPro combines read depth information along with discordant paired-read mappings into a single probabilistic model two common signals of structural variation. When multiple alignments of a read are given, GASVPro utilizes a Markov Chain Monte Carlo procedure to sample over the space of possible alignments.


##Downloads
GASVPro is availabile at the GASV GoogleCode site. Download.) We also provide an Example Data Set for analysis with GASVPro.

Description of the software: README.  
Latest release is located on GoogleCode.

##References
The GASVPro algorithm is described in the following paper:

>S. Sindi, S. Onal, L. Peng, H. Wu and B.J. Raphael. (2012)
>An Integrative Model for Identification of Structural Variation in Sequencing Data. *Genome Biology* (In Press)

The original GASV method is described in the following paper:

>S. Sindi, E. Helman, A. Bashir, B.J. Raphael. (2009)
>A Geometric Approach for  Classification and Comparison of Structural Variants. *Bioinformatics(. 25: i222-i230. (Special issue for the Joint 17th Annual International >Conference on Intelligent Systems in Molecular Biology and 8th Annual International European Conference on Computational Biology (ISMB/ECCB 09)). Publisher Link

##Previous versions

Old versions. These are for archival purposes. It is recommended to download the latest version from link above.

Version 1.4 (3/5/2010) . Download  
Version 1.3 (1/19/2010) . Download  
Example BAM file  
Version 1.2 (11/30/2009) . Download: software  
New in Version 1.4: Release notes.  
New in Version 1.3: New output formats, streamlining of BAM file handling, bug fixes.  
New in Version 1.2 (11/30/2009): Improved handling of SAM/BAM alignment files, speed improvements, maxCliqueSize option.  
New in Version 1.1: a preprocessor for SAM/BAM files, aCGH comparison, fusion gene detection, and more.