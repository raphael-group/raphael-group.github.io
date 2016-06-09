---
layout: default
title:  Raphael Lab // HotNet2
container_css_class: container
---

# HotNet2 #

## About ##

<span>
HotNet2 (diffusion-oriented subnetworks) is a general algorithm for identifying high weight subnetworks in a vertex-weighted network. HotNet2 was developed for identifying significantly mutated groups of interacting genes from large cancer sequencing studies. HotNet2 uses an "insulated" heat diffusion process to simultaneously analyze a gene's mutations (or mutation score) and its local topology. This diffusion process encodes the source, or directionality, of heat within the network, allowing HotNet2 to uncover surprisingly "hot" subnetworks with wide ranges of heat scores.
</span>

**People** (strict random order): Max Leiserson, Fabio Vandin, Hsin-Ta Wu, Jonathan Eldridge, Ben Raphael.

<a name="download"></a>

## Download ##
You can download the latest version of HotNet2 from the [releases page](https://github.com/raphael-group/hotnet2/releases) of the [HotNet2 GitHub project](https://github.com/raphael-group/hotnet2). The GitHub page also includes documentation for running HotNet2 (see below).

## Support ##
Detailed instructions for running HotNet2 are provided in the included [README](https://github.com/raphael-group/hotnet2/blob/master/README.md).

For additional support, please see the [HotNet Google Group](https://groups.google.com/forum/#!forum/hotnet-users). Note that we use the HotNet Google Group for issues relating to either HotNet2 or HotNet.

<a name="reference"></a>

## References ##
The HotNet2 algorithm is described in the following paper:

>M.D.M. Leiserson\*, F. Vandin\*, H-T. Wu, J.R Dobson, J.V. Eldridge, J.L. Thomas, A. Papoutsaki, Y. Kim, B. Niu, M. McLellan, M.S. Lawrence, A. Gonzalez-Perez, D. Tamborero, Y. Cheng, G.A. Ryslik, N. Lopez-Bigas, G. Getz, L. Ding, and B.J. Raphael. Pan-cancer network analysis identifies combinations of rare somatic mutations across pathways and protein complexes. *Nature Genetics* (2014).

Moreover, we have used HotNet2 in the following publications:

>Hoadley, K.A. *et al*. Multiplatform analysis of 12 cancer types reveals molecular classification within and across tissues of origin. *Cell* 158, 929–944 (2014).

>The Cancer Genome Atlas Research Network. Comprehensive molecular characterization of gastric adenocarcinoma. *Nature* 513, 202–209 (2014).

>Agrawal, Nishant *et al*. Integrated Genomic Characterization of Papillary Thyroid Carcinoma. *Cell* 159, 676 - 690 (2014).
