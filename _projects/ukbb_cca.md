---
title: Canonical Correlation Analysis of brain and behaviour
subtitle: Effects of sample size/composition and analysis pipeline
status: active
layout: project
people:
  - Michelle
  - Brent
---

## Background

[Canonical Correlation Analysis (CCA)](https://en.wikipedia.org/wiki/Canonical_correlation) is a multivariate technique that can describe how measures from different domains -- such as brain and behaviour -- vary together. Recent work suggests that thousands of individuals are required in this type of multivariate analysis to obtain consistently reproducible results ([Marek et al., 2022](https://doi.org/10.1038/s41586-022-04492-9)).

## Objective

The goal of this project is to investigate the effects of sample size on brain-behaviour CCA. We will use imaging-derived phenotypes and cognitive measures from around 40,000 individuals from the [UK Biobank](https://www.ukbiobank.ac.uk/). Specifically, we will focus on diffusion magnetic resonance imaging (dMRI) data and cognitive function, which have been previously shown to covary strongly ([McPherson & Pestilli, 2021](https://doi.org/10.1038/s42003-021-02451-0)). We aim to assess the replicability of CCA correlations by fitting models on bootstrapped samples and testing the fitted models on held-out (validation) data. We will vary our data samples along the following axes:

1. Sample size of the training dataset
2. Sample composition (full sample, healthy participants, disease samples)
3. CCA pipeline (with or without cross-validation)

We expect this study to further inform on the effects of sample size, sample composition and analysis pipeline on the replicability of multivariate methods.

GitHub repository: [`ukbb-cca`](https://github.com/neurodatascience/ukbb-cca).
