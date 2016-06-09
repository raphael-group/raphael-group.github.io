---
layout: default
title:  Raphael Lab // Research
container_css_class: container
---
# research

We develop algorithms and mathematical models to address biological problems. Major areas of interest include computational cancer genomics, human structural variation, and comparative genomics.  


The motivation for many of our current projects derives from the tremendous advances in DNA sequencing technology over the past few years. Next-generation DNA sequencing machines have lowered the cost of DNA sequencing by orders of magnitude, and enabled a variety of new applications such as personal genome sequencing and cancer genome sequencing.

## Computational Cancer Genomics
We develop algorithms to study somatic mutations that drive cancer progression. Specific areas of interest include:

* Identification of genome rearrangements (including translocations, inversions, deletions, and duplications) in cancer genomes.  
We designed the [RAIG](/projects/raig/) and [NBC](/projects/nbc) algorithms to detect recurrent and independent copy number aberrations.

* Reconstruction of highly scrambled cancer genomes and the mechanisms that produce them. 
We introduced the [PREGO](/projects/prego/) algorithm to combine rearrangement breakpoints and copy number data in cancer genomes.
Study of changes in gene structure and regulation that result from these rearrangements.

* Cancer Genome Evolution.  
Cancer is a microevolutionary process in a population of cells that reproduce (via cell division) and acquire new mutations. Extracting information about the process of tumor evolution from bulk sequencing data containing mixtures of cells demands novel computational approaches.  We developed several algorithms to study intra-tumor heterogeneity and tumor evolution including [THetA](/projects/theta), [rec-BTP](/projects/btp), and [AncesTree](/projects/ancestree).  

* Network and pathway-based analysis of somatic mutations. We designed the [HotNet](/projects/hotnet) and [HotNet2](/projects/hotnet2) algorithms for de novo identification of mutated subnetworks in large-scale protein-protein interaction networks using somatic mutation data from multiple cancer patients.

* De novo identification of combinations of mutually exclusive mutations. Early cancer sequencing studies demonstrated that in many cases somatic mutation of a single gene in a pathway (e.g. a pathway controlling cell growth) is sufficient to perturb this pathway.  This implies that when examining somatic mutations from many patients, mutations in the same pathway will exhibit a pattern of mutual exclusivity.  We designed [Dendrix](/projects/dendrix), [Multi-Dendrix](/projects/multi-dendrix) and [CoMEt](/projects/comet) algorithms for de novo identification of one or more sets of mutually exclusive mutations.


## Comparative Genomics
We study the role of structural variation (genome rearrangements, segmental duplications, and repeats) in evolution and human genetics.

## Sequencing Structural Variants
We are developing scalable and robust algorithms to identify structural variants in 
individual genomes and to compare structural variants across individuals using various 
second and third generation DNA sequencing technologies. We introduced [Geometric Analysis of Structural Variants (GASV)](/projects/gasv) a geometric method that explicitly computes the information that each measurement reveals about the boundaries (breakpoints) of a structural variant and quantifies the uncertainty associated with this measurement.

We are designing algorithms to maximize the effectiveness of emerging single-molecule sequencing technologies for detecting and assembling complex structural variants and for de novo genome assembly. 
In particular, we designed the [MultiBreak-SV](/projects/multibreaksv/) algorithm for long-read and strobe read sequencing data from
[Pacific Biosciences](http://www.pacificbiosciences.com/).

## Other Research
We have also worked on a number of other areas in computational biology.  Examples include:

* Visualization and collaborative annotation of genomics data (O'Brien et al. 2010, Leiserson et al. 2015)
* Chromatin organization (Weinreb and Raphael 2015).
* Proteomics (Nguyen et al. 2009, Ritz et al. 2009), 
* Metagenomic studies of protein family diversity (Yooseph et al. 2006)
* Multiple sequence alignment with block rearrangements (Raphael, et al. 2004)
* Motif finding (Raphael, Liu and Varghese, 2004)


See the [publications page]({{ site.url }}/publications) for further details.
