---
layout: default
title:  Raphael Lab // TADTree
container_css_class: container
---

# TADtree

## About 
TADtree is an algorithm the identification of hierarchical topological domains in Hi-C data.

<img src="{{ site.baseurl }}/projects/tadtree/tadtree-overview.jpg" />
<br/>
Overview of TADtree algorithm. Beginning with contact matrix <i>A</i>, we compute the fold-enrichment over background for each pair of positions. For each interval [<i>i</i>,<i>j</i>], we estimate parameters &delta;(<i>i</i>,<i>j</i>), &beta;(<i>i</i>,<i>j</i>). Next, for each genomic position <i>i</i> we compute the boundary index, a 1D statistic that looks for local shifts in interaction frequency at TAD boundaries . Finally, a dynamic program finds TAD trees that maximize the boundary index and best fit the contact matrix <i>A</i>, then selects an optimal set of TAD trees to form a TAD forest.

<a name="download"></a>
<br/>

## Download
<a href='http://compbio-research.cs.brown.edu/software/TADtree.zip'>TADtree.zip</a>