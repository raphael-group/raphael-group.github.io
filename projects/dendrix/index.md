---
layout: default
title:  Raphael Lab // Dendrix
container_css_class: container
---

#Dendrix
Dendrix (De novo Driver Ex Exclusivity) is an algorithm that identifies driver groups of mutations without prior information, using the exclusivity property observed for mutations in a driver pathway.

People (strict random order): Fabio Vandin, Hsin-Ta Wu, Eli Upfal, Ben Raphael.

references
The Dendrix algorithm is described in the following publications:

F. Vandin, E. Upfal, and B.J. Raphael. (2011) De Novo Discovery of Mutated Driver Pathways in Cancer. (Abstract) Proceedings of the 15th Annual International Conference on Research in Computational Molecular Biology (RECOMB 2011), pag:499-500.
F. Vandin, E. Upfal, and B.J. Raphael. De novo discovery of mutated driver pathways in cancer. Genome Research (2011) Jul 11. [Epub ahead of print]
 

download
Beta version of Dendrix is available.

Dendrix (ver0.3, February 4, 2013): for finding significant groups of mutations (with collapsing level -gene, protein domain, etc.- for mutations defined by the user) based on coverage and exclusivity in the alteration matrix.
contact: dendrix@cs.brown.edu
 

requirements
Python
how-to
Detailed instructions for running Dendrix are provided in the README.txt file in the release above.

 

visualization
Cytoscape plugin: visualize the result of Dendrix.