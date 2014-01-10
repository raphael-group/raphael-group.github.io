---
layout: default
title:  Raphael Lab // Research
container_css_class: container
---
#research

We develop algorithms and mathematical models to address biological problems. Major areas of interest include computational cancer genomics, human structural variation, comparative genomics, and algorithms for DNA and protein sequence analysis.

The motivation for many of our current projects derives from the tremendous advances in DNA sequencing technology over the past few years. Next-generation DNA sequencing machines have lowered the cost of DNA sequencing by orders of magnitude, and enabled a variety of new applications such as personal genome sequencing and cancer genome sequencing.

##Computational Cancer Genomics
We develop algorithms to study somatic mutations that drive cancer progression. Specific areas of interest include:

* Identification of genome rearrangements (including translocations, inversions, deletions, and duplications) in cancer genomes. Reconstruction of highly scrambled cancer genomes and the mechanisms that produce them. Study of changes in gene structure and regulation that result from these rearrangements.
* Network and pathway-based analysis of somatic mutations. We designed [HotNet](/projects/hotnet) an algorithm for de novo identification of mutated subnetworks in large-scale protein-protein interaction networks using somatic mutation data from multiple cancer patients.

##Comparative Genomics
We study the role of structural variation (genome rearrangements, segmental duplications, and repeats) in evolution and human genetics.

##Sequencing Structural Variants
We are developing scalable and robust algorithms to identify structural variants in individual genomes and to compare structural variants across individuals using various second and third generation DNA sequencing technologies. We introduced [Geometric Analysis of Structural Variants (GASV)](/projects/structvar) a geometric method that explicitly computes the information that each measurement reveals about the boundaries (breakpoints) of a structural variant and quantifies the uncertainty associated with this measurement.

We are designing algorithms to maximize the effectiveness of emerging single-molecule sequencing technologies for detecting and assembling complex structural variants and for de novo genome assembly. In particular, we are designing algorithms for strobe reads, a generalization of paired reads that consist of more than two reads from a single DNA fragment, and are being commercialized by [Pacific Biosciences](http://www.pacificbiosciences.com/).

##Biological Sequence Analysis
We develop algorithms for analysis and annotation of DNA and protein sequences. Earlier work includues methods for multiple sequence alignment with block rearrangements, motif finding, analysis of high-copy number repeats in the human genome, and metagenomic studies of protein family diversity.

See the [publications page]({{ site.url }}/publications) for further details.
