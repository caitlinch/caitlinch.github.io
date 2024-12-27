---
title: "MAST: Phylogenetic inference with mixtures across sites and trees"
collection: publications
category: manuscripts
permalink: /publication/2024-wong_etal
excerpt: 'We introduce an implementation of a multi-tree mixture model that we call mixtures across sites and trees (MAST). [...] The MAST model allows each tree to have its own weight, topology, branch lengths, substitution model, nucleotide or amino acid frequencies, and model of rate heterogeneity across sites. '
date: 2024-02-29
venue: 'Systematic Biology'
paperurl: 'https://doi.org/10.1093/sysbio/syae008'
citation: 'Thomas K F Wong, Caitlin Cherryh, Allen G Rodrigo, Matthew W Hahn, Bui Quang Minh, Robert Lanfear 2024. MAST: Phylogenetic Inference with Mixtures Across Sites and Trees. Systematic Biology. 73:375–391.'
---

Hundreds or thousands of loci are now routinely used in modern phylogenomic 
studies. Concatenation approaches to tree inference assume that there is a 
single topology for the entire dataset, but different loci may have different 
evolutionary histories due to incomplete lineage sorting (ILS), introgression, 
and/or horizontal gene transfer; even single loci may not be treelike due to 
recombination. To overcome this shortcoming, we introduce an implementation of 
a multi-tree mixture model that we call mixtures across sites and trees (MAST). 
This model extends a prior implementation by Boussau et al. (2009) by allowing 
users to estimate the weight of each of a set of pre-specified bifurcating 
trees in a single alignment. The MAST model allows each tree to have its own 
weight, topology, branch lengths, substitution model, nucleotide or amino acid 
frequencies, and model of rate heterogeneity across sites. We implemented the 
MAST model in a maximum-likelihood framework in the popular phylogenetic software, 
IQ-TREE. Simulations show that we can accurately recover the true model parameters, 
including branch lengths and tree weights for a given set of tree topologies, 
under a wide range of biologically realistic scenarios. We also show that we 
can use standard statistical inference approaches to reject a single-tree model 
when data are simulated under multiple trees (and vice versa). We applied the 
MAST model to multiple primate datasets and found that it can recover the 
signal of ILS in the Great Apes, as well as the asymmetry in minor trees caused 
by introgression among several macaque species. When applied to a dataset of 4 
Platyrrhine species for which standard concatenated maximum likelihood (ML) and 
gene tree approaches disagree, we observe that MAST gives the highest weight 
(i.e., the largest proportion of sites) to the tree also supported by gene tree 
approaches. These results suggest that the MAST model is able to analyze a 
concatenated alignment using ML while avoiding some of the biases that come 
with assuming there is only a single tree. We discuss how the MAST model can be 
extended in the future.

