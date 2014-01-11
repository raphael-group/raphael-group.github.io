---
layout: default
title:  Raphael Lab // Multi-Dendrix
container_css_class: container
---

#Multi-Dendrix
Multi-Dendrix (Multiple Pathways De novo Driver Exclusivity) is an algorithm that identifies sets of driver pathways in cancer without prior information by simultaneously identifying sets of genes with approximately exclusive mutations and high coverage.

The Multi-Dendrix Python package includes the Multi-Dendrix algorithm, as well as additional functions for: 1) identifying the stable modules identified by Multi-Dendrix over a range of parameter values; 2) analyzing (sub)type-specific mutations in a cohort of samples; and, 3) calculating protein-protein interaction enrichment of gene sets and collections of gene sets.

For full documentation of the Multi-Dendrix package, please see our documentation on GitHub at http://mdml.github.com/multi-dendrix.

 A collection of gene sets identified by Multi-Dendrix from mutation data in 202 genes from 507 primary breast cancer patients . (Left) Nodes represent genes in four modules found by Multi-Dendrix using t=2,...,4 gene sets of minimum size kmin=3 and maximum size kmax=3,...5. Genes with "(A)" appended are amplification events, genes with "(D)" appended are deletion events, and genes with no annotation are SNVs. Edges connect genes that appear in the same gene set for more than value of the parameters, with labels indicating the fraction of parameter values for which the pair of genes appear in the same gene set. Color of nodes indicates membership in three signaling pathways noted as important for breast cancer: p53 signaling, PI(3)K/AKT signaling, p38-JNK1, and cell cycle checkpoints. Shape of nodes indicates genes whose mutations are associated with specific BRCA subtypes, and dashed edges connect genes associated with different subtypes. (Middle) Knwon interactions between proteins in each set and p-value for the observed number of interactions. We show the regulatory interaction between GATA3 and CDH1 as a dashed line. (Right) Mutation matrix for each of the four modules with mutual exclusive (blue) and co-occurring mutations (orange). The top row of each mutation matrix annotates the subtype of each patient.

 

People (strict random order): Max Leiserson, Dima Blokh, Roded Sharan, Ben Raphael.

 

references
The Multi-Dendrix algorithm is described in a paper in submission:

M.D.M. Leiserson, D. Blokh, R. Sharan, B.J. Raphael. (2013) Simultaneous Identification of Multiple Driver Pathways in Cancer PLoS Comp Bio, 9(5):e1003054. Publisher Link | PDF.

 

download
Full version of the Multi-Dendrix pipeline is available via GitHub.

Multi-Dendrix (version 1.0, January 28, 2013): for rapid and simultaneous identification of driver pathways in cancer de novo from genome-scale somatic mutation data (single nucleotide and copy number variants).
contact: {mdml, braphael} [at] cs.brown.edu
 

how-to
Detailed documentation for the Multi-Dendrix package is provided at http://mdml.github.com/multi-dendrix.

requirements
Python
CPLEX with Python module (see CPLEX Python documentation)
NetworkX.
GraphViz.
Either SciPy >= version 0.11 or the Python fisher module.