---
layout: default
title:  Raphael Lab // HotNet
container_css_class: container
---

#HotNet

##About
HotNet is an algorithm for finding significantly altered subnetworks in a large gene interaction network.  HotNet2 improves on this algorithm in several respects. While originally developed for use with cancer mutation data, the current release of HotNet also supports any application in which scores can be assigned to genes in the network (this version of the algorithm is called generalizedHotNet - see Vandin et al., PSB 2012).

**People** (strict random order): Fabio Vandin, Hsin-Ta Wu, Edward Rice, Layla Oesper, Adrien Deschamps, Max Leiserson, Jonathan Eldridge, Jason Schum, Eli Upfal, Ben Raphael.

<a name="download"></a>
##Download
You can download the latest version of HotNet from the [releases page](https://github.com/raphael-group/hotnet/releases) of the [HotNet GitHub project](https://github.com/raphael-group/hotnet).

##Support
Detailed instructions for running HotNet are provided in the included [README](https://github.com/raphael-group/hotnet/blob/master/README.md).

For additional support, please see the [HotNet Google Group](http://localhost:4000/projects/hotnet/).

<a name="reference"></a>
##References
The HotNet algorithm is described in the following publications:

>F. Vandin, E. Upfal, and B.J. Raphael. (2010) Algorithms for Detecting Significantly Mutated Pathways in Cancer.
>*Proceedings of the 14th Annual International Conference on Research in Computational Molecular Biology (RECOMB 2010)*.

>F. Vandin, E. Upfal, and B.J. Raphael. (2011) Algorithms for Detecting Significantly Mutated Pathways in Cancer. *Journal of Computational Biology*. 18(3):507-22.

Moreover, we have used HotNet in the following publications:

>The Cancer Genome Atlas Research Network (2011). Integrated genomic analyses of ovarian carcinoma. *Nature*. 474:609-615.

>F. Vandin, P. Clay, E. Upfal, and B. J. Raphael (2012) Discovery of Mutated Subnetworks Associated with Clinical Data in Cancer. In *Pacific Symposium on Biocomputing (PSB)* 2012.

>C. Grasso, Y.Wu, D. Robinson, X. Cao, S. Dhanasekaran, A. Khan, M. Quist, X. Jing, R. Lonigro, J.C. Brenner, I. Asangani, B. Ateeq, S. Chun, J. Siddiqui, L. Sam, M. Anstett, R. Mehra, J. Prensner, N. Palanisamy, G. Ryslik, F. Vandin, B. Raphael, L. Kunju, D. Rhodes, K. Pienta, A. M. Chinnaiyan, S.A. Tomlins. The Mutational Landscape of Lethal Castrate Resistant Prostate Cancer. *Nature*, 2012.

>The Cancer Genome Atlas Research Network. Genomic and Epigenomic Landscapes of Adult De Novo Acute Myeloid Leukemia. New England Journal of Medicine, May 1st 2013.
>The Cancer Genome Atlas Research Network. Comprehensive molecular characterization of clear cell renal cell carcinoma. *Nature*, 2013 Jul 4; 499(7456):43-9.


##Previous versions
These are for archival purposes. It is recommended to download the latest version from the link above.

* [HotNet version 1.0.0 (July 13th, 2012)](http://compbio.cs.brown.edu/software/HotNet/HotNet_v1.0.0.zip)  
  This new version merges the old HotNet and Generalized HotNet methods, requires a new, cleaner representation for copy number aberrations, and adds a number of new features - see the README.txt in archive download for details.

* [HotNet (ver0.9.1, June 29, 2011)](http://compbio.cs.brown.edu/software/HotNet/HotNet_v0.9.1.zip)  
  For finding significantly mutated subnetworks using single nucleotide mutations (and indels) and copy number aberrations (that is, the statistical test performed by HotNet is designed for these types of data).

* [Generalized HotNet (ver0.9.1, June 29, 2011)](http://compbio.cs.brown.edu/software/HotNet/GeneralizedHotNet_v0.9.1.zip)  
  A general version of HotNet that allows for arbitrary gene scores. (The statistical test is a general test that can be used with any score.)
