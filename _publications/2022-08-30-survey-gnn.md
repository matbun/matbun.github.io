---
title: "From Spectral Graph Convolutions to Large Scale Graph Convolutional Networks"
collection: publications
permalink: /publication/2022-08-30-survey-gnn
excerpt: 'Graph Convolutional Networks (GCNs) have been shown to be a powerful concept that has been successfully applied to a large variety of tasks across many domains over the past years. In this work we study the theory that paved the way to the definition of GCN, including related parts of classical graph theory. We also discuss and experimentally demonstrate key properties and limitations of GCNs such as those caused by the statistical dependency of samples, introduced by the edges of the graph, which causes the estimates of the full gradient to be biased. Another limitation we discuss is the negative impact of minibatch sampling on the model performance. As a consequence, during parameter update, gradients are computed on the whole dataset, undermining scalability to large graphs. To account for this, we research alternative methods which allow to safely learn good parameters while sampling only a subset of data per iteration. We reproduce the results reported in the work of Kipf et al. and propose an implementation inspired to SIGN, which is a sampling-free minibatch method. Eventually we compare the two implementations on a benchmark dataset, proving that they are comparable in terms of prediction accuracy for the task of semi-supervised node classification.'
date: 2022-08-30
venue: 'arXiv preprint arXiv:2207.05669'
paperurl: 'https://arxiv.org/pdf/2207.05669'
citation: 'Matteo Bunino (2022). &quot;From Spectral Graph Convolutions to Large Scale Graph Convolutional Networks&quot; <i>Journal arXiv preprint arXiv:2207.05669</i>.'
---

[Download paper here](https://arxiv.org/pdf/2207.05669.pdf)

Recommended citation: 'Matteo Bunino (2022). &quot;From Spectral Graph Convolutions to Large Scale Graph Convolutional Networks&quot; <i>Journal arXiv preprint arXiv:2207.05669</i>.'
