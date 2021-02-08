---
title: Deriving Variational E-M Algorithms on Latent Dirichlet Allocation (LDA)
subtitle:

# Summary for listings and search engines
summary: The purpose of this note is to open the box to explore the mathematical details that enable LDA’s effective statistical inference as well as optimization.

# Link this post with a project
# projects: []
url_slides: "slides/lda/LDA_EM.pdf"

# Date published
date: "2021-01-01T00:00:00Z"

# Date updated
lastmod: "2021-01-01T00:00:00Z"

# Is this an unpublished draft?
draft: false

# Show this page in the Featured widget?
featured: false

# Featured image
# Place an image named `featured.jpg/png` in this page's folder and customize its options here.
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/Oal07Ai4oTk)'
  focal_point: Right

authors:
- admin

tags:
- Mathematics
- Statistical Learning

categories:
- Statistics
---

## Overview

LDA is one of the most important topic models in practice. On a high level, it provides a generative model
that describes how the documents in a dataset are generated; i.e. how words are sampled from multiple
topics to construct a document. This generative process follows a bag of words (BOW) assumption. Hence,
the order in which the word occurs is not taken into account. The core of topic modeling is to analyze unlabeled text data, discover the unknown number of topics and topic distribution in a unsupervised way. This is achieved by making use of statistical inference.

## References

This note is written based primarily on the following sources:

0. D. Blei, Andrew Ng, Jordan M. Latent Dirichlet Allocation. Journal of Machine Learning Research. 2003.

1. Reed C. Latent Dirichlet Allocation: Towards a Deeper Understanding. 2012.

2. Coursera: Bayesian Methods in Machine Learning. National Research University - Higher School of Economics. 2020.

3. Chenouri S. Stat440/840: Computational Inference. University of Waterloo. 2019.

4. Lysy M. Stat946: Advanced Computational Inference. University of Waterloo. 2019.

5. Struthers C. Stat450/850: Estimation and Hypothesis Testing. University of Waterloo. 2018.

6. Bishop C. Pattern Recognition and Machine Learning. Information Science and Statistics. 2006.

7. Wolf W. Deriving Expectation-Maximization. Blog. 2018.

8. Serrano L. Latent Dirichlet Distribution. Youtube. 2020.
