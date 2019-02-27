---
layout: default
title:  Raphael Lab // MASCoTE
container_css_class: container
---

# MASCoTE: Multi-sample Allele-specific Simulation of Tumor Copy-number Evolution

MASCoTE (Multi-sample Allele-specific Simulation of Copy-number Tumor Evolution) is a simulation framework
to generate sequencing reads with appropriately corrections for the differences in genome lengths between the normal and tumor clone(s) present in multiple mixed samples from the same patient. MASCoTE simulates a normal diploid human genome and the genomes of tumor clones characterized by different kind of somatic copy-number aberrations (CNAs) and whole-genome duplications (WGDs) accumulated during an evolutionary process modeled as a phylogenetic tree. Different CNAs include focal CNAs, and CNAs involving chromosomal arms and whole chromosomes. MASCoTE has been designed and developped by Simone Zaccaria in the group of prof. Ben Raphael at Princeton University. The full description of the simulation framework is included together with the HATCHet algorithm in

[Simone Zaccaria and Ben Raphael, 2018](https://www.biorxiv.org/content/early/2018/12/17/496174)

The simulated data and the results of all the methods considered in the comparison are available at

[manuscript's data](https://github.com/raphael-group/hatchet-paper)

![](doc/mascote-cartoon.png "MASCoTE framework")

**Overview of Multiple Allele-specific Simulation of Copy-number Tumor Evolution (MASCoTE) framework.** MASCoTE simulates sequencing reads of multiple mixed samples according to the genome lengths and proportions of all clones. The simulation framework of MASCoTE is composed of four steps. **(A)** MASCoTE simulates a diploid human genome by inserting homozygous (purple square) and heterozygous (magenta squares) germline SNPs in the two haplotypes (red and blue haplotypes). **(B)** MASCoTE simulates the genomes of 4 tumor clones by considering CNAs and WGDs. First, MASCoTE generates a random phylogenetic tree which describes the tumor evolution; the phylogenetic tree is rooted in the normal diploid clone (grey node) and every other node corresponds to a tumor clone (green, fuchsia, orange, and gold nodes). Next, MASCoTE simulates different kind of CNAs for every branch, including aberrations of whole chromosomes or chromosomal’s arms, and focal duplications and deletions. MASCoTE also simulates a WGD in the trunk of the phylogeny. As such, the CNAs and WGDs in each branch are applied in arbitrary order to the genome of the parent clone to obtain the genome of the child clone such that the diploid human genome generated in **(A)** is assigned to the normal diploid clone. **(C)** MASCoTE simulates sequencing reads from the genome of every clone and computes the corresponding genome lengths (_L_). **(D)** MASCoTE simulates multiple mixed samples according to given clone proportions (_u_) by computing the corrected proportions of sequencing reads belonging to each clone (_v_) and by mixing the reads accordingly.

## Repository 

You can download the latest version of MASCoTE from the [MASCoTE GitHub project](https://github.com/raphael-group/mascote). The repository includes a detailed documentation, demos, examples, and tutorials.

## Support

You can ask support and questions about MASCoTE on the actively mantained **Issues** forum of the HATCHet GitHub project](https://github.com/raphael-group/mascote). 

## References
MASCoTE and its applications are described together with HATCHet in the following publications:

> Simone Zaccaria and Benjamin J. Raphael, *Accurate quantification of copy-number aberrations and whole-genome duplications in multi-sample tumor sequencing data*. bioRxiv (Dec. 17, 2018) doi.org/10.1101/496174
