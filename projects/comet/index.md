---
layout: default
title:  Raphael Lab // CoMEt
container_css_class: container
---

#CoMEt: <u>C</u>ombinations <u>o</u>f <u>M</u>utually <u>E</u>xclusive Al<u>t</u>erations
CoMEt improves upon the [Dendrix](/projects/dendrix) and [Multi-Dendrix](/projects/multi-dendrix)
algorithms to identify collections of exclusive alterations in cancer without prior information. CoMEt
uses a novel statistical score for exclusivity collections of alterations and an MCMC algorithm to
compute the marginal probability of observing pairs of alterations in the same exclusive set.

CoMEt is released as a [software package on GitHub](https://github.com/raphael-group/comet). The exact test used by CoMEt is also available as the [cometExactTest R package](http://cran.r-project.org/web/packages/cometExactTest/) hosted by [CRAN](http://cran.r-project.org/).

### Dendrix++
Dendrix++ is a preliminary version of CoMEt that we applied as part of the
[TCGA AML project](http://www.nejm.org/doi/full/10.1056/NEJMoa1301689#t=articleTop).

<a name="reference"></a>
## References
The CoMEt algorithm is described in the following publication:

Mark D.M Leiserson\*, Hsin-Ta Wu\*, Fabio Vandin, Benjamin J. Raphael. (2015) Comet: A Statistical Approach to Identify Combinations of Mutually Exclusive Alterations in Cancer. In *Proceedings of the 19th Annual Research in Computational Biology Conference (RECOMB)* (to appear).

\* equal contribution
