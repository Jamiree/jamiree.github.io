---
title: "Genetic sequence clustering using unsupervised clustering algorithms and applications in mapping genotype to phenotype."
collection: publications
permalink: /publication/paper6
excerpt: '[PDF](http://jamiree.github.io/files/paper6.pdf)'
date: 
venue:
paperurl: 
citation: 'Currently in review'
---

Genetic sequence clustering is an important high-dimensional clustering problem with many applications in
bioinformatics and bioengineering. Most current approaches are built for large sequence data sets and optimize for run-time efficiency. As such, most sequence clustering algorithms are written in C++ and can become unwieldy when working in Python environments. Our method implements a one hot encoding on the DNA nucleotides and implements the various unsupervised clustering approaches such as k-means, c-means, and DB-scan. Since these unsupervised clustering algorithms require the input sequences to have equal length, we provide a simple trimming tool that pairwise aligns each target sequence to a specified reference sequence and snips off the ends of each sequence. We show how noisy sequence data affects clustering results in unsupervised methods. Lastly, we exhibit how these clustering algorithms can be used to map genotypes to phenotypes using the adjusted mutual information score.
