---
title: "Parameter estimation for parameter-varying systems using optimization and sparse regression."
collection: publications
permalink: /publication/paper4
excerpt: '[PDF](http://jamiree.github.io/files/paper4.pdf)'
date: 
venue:
paperurl: 
citation: 'Currently in review'
---

Suppose that we have data from a system which has parameters that depend on some independent
variable such as time or space. Further, suppose that we know the form of the model for underlying
system dynamics a priori, but we wish to identify functions that describe parameter-varying elements
of the model as they change with respect to time or some other system variable. At first, we consider
the case where parameters are constant but switching at discrete points in time. We devise an algorithm
that detects these discrete switches in data using binary segmentation and that fits a parameter-varying
model to the data using optimization-based parameter estimation. We demonstrate the algorithm’s
capabilities across several examples from ordinary differential equations (ODEs), parametric curves,
and partial differential equations (PDEs). Lastly we show how dictionary-based sparse regression
with universal function approximators, e.g., trigonometric, polyonmial functions, can be used in
conjunction with our algorithm to obtain time-varying or spatially-dependent parameter functions.
