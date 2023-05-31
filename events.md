---
layout: default
title: NeuroImaging Statistics - July 27th 2023 - Montreal Neurological Institute
---

## NeuroImaging Statistics Satellite 
We’re pleased to announce a satellite event to the 2023 Organisation for Human Brain Mapping (OHBM) meeting, the Neuroimaging Statistics Workshop, as a means to foster collaboration and generate ideas among statisticians working with brain data.

The event will take place at the Montreal Neurological Institute on Thursday 27th July (the day after the close of OHBM).  There will be 4 keynote speakers, starting with the Keith Worsley lecture delivered by Jonathan Taylor, Keith’s prolific student and author of the seminal text “Random Fields and Geometry” with Robert J. Adler.  

<!-- … 
## Attend or contribute

#### We have space for 8 contributed lectures please use [this link](https://forms.gle/YraFS9AVLPozjwZY9) to attend or contribute.
-->

## Program

### Morning: 

**9:30-10:30**
* Introductory remarks: Tom Nichols, JB Poline
* Keynote: Inaugural Keith Worsley lecture : **Jonathan Taylor** : Random field theory meets the LASSO

**10:30:11:45**
- **Samuel Davenport**: Accurate voxelwise FWER control in fMRI using Random Field Theory
- **Sarah Weinstein**: Spatially-enhanced clusterwise inference for testing and localizing intermodal correspondence

**Break** 
- **Bertrand Thirion**: False Discovery Proportion control for aggregated Knockoffs
- **Chris Camp**: Contextualizing classification accuracy within effect sizes

**11:45-12:30** 
* Keynote: **Mandy Meija** : Rethinking scrubbing in fMRI from a statistical perspective

### 12:30-13:30 Lunch break 

### Afternoon : 
**13:30-2:15** 
* Keynote: **Jelle Goeman** : Rethinking scrubbing in fMRI from a statistical perspective

**2:15-3:30**
* **Yifan Yu**: Neuroimaging Meta Regression for Coordinate Based Meta Analysis Data with a Spatial Model
* **Jun Young Park**: SAN-GP: Mitigating inter-scanner biases in high-dimensional neuroimaging data via spatial Gaussian process

**Break** 
* **Ian-Christopher Tanoh**: A scalable multivariate Bayesian polygenic model for heritability-based principal
* **Habib Ganjgahi**: Scalable Hierarchical Bayesian Model for Multiple Sclerosis Progression using Brain Imaging and Clinical Features

**3:30-4:30** 
- Keynote: **Martin Linquist** :Individualized spatial topography in functional neuroimaging 

## Venue

### De Grand Pré Conference Centre
De grand pré, Montreal Neurological Institute, McGill University, 3801 Rue University, Montréal, QC H3A 2B4, Canada

### Abstracts:

Jonathan Taylor: Random field theory meets the LASSO

Random field theory (RFT) has long been used widely used tool for assessing significance in SPMs by analyzing a model of the SPM under a global null.  We describe a method to build and compare models under alternative models with peaks selected by the SPM itself. The selection method is a variant of the LASSO which lends itself to analysis with the methods of selective inference, including a tractable approximate likelihood theory. The likelihood analysis allows much of the common tasks in likelihood based models: interval estimation for effect size, confidence ellipsoids for peak locations, Bayesian analysis with priors solicited after selection of peaks.

Amanda Mejia: Rethinking scrubbing in fMRI from a statistical perspective

Scrubbing" or removal of fMRI volumes potentially contaminated with head motion-induced noise has become common practice in fMRI analysis. However, the removal of volumes based on head motion measures alone has become increasingly flawed for a number of reasons. These include a lack of adaptiveness to improved data denoising techniques such as ICA-FIX and aCompCor, poor generalizability to multi-band acquisitions, and over-aggressive removal of volumes with more stringent motion thresholds, often resulting in exclusion of half or more of all sessions. Statistical approaches based on abnormalities in the fMRI timeseries address many of these limitations. In this talk, I will present recent data-driven alternatives to motion scrubbing and illustrate their potential for dramatically increasing sample sizes in fMRI analysis.


Jelle Goeman: Cluster extent inference revisited: quantification and localization of brain activity

Cluster inference based on spatial extent thresholding is a popular analysis method for finding activated brain areas in neuroimaging. However, the method as currently defined has several well-known issues. While powerful for finding regions with some activation, the method does not allow any further quantification or localization of signal. In this paper we repair this gap.  We show that cluster-extent inference can be used (1.) for inference on the presence of signal in any region of interest and (2.) to quantify the percentage of activation in such regions. These additional inferences come for free, i.e. they do not require any further adjustment of the alpha-level of tests, while retaining full familywise error rate control. We achieve this extension of the possibilities of cluster inference by an embedding of the method into a closed testing procedure, and solving the graph-theoretic k-separator problem that results from this embedding. Our construction shows that classic cluster extent inference is a special case of a category of methods that control True Discovery Proportions for simultaneously for all brain regions, and we compare the method to alternatives such as All-Resolutions Inference. We demonstrate the methods in a large-scale application to data from the Neurovault database.

Martin Linquist: Individualized spatial topography in functional neuroimaging 

Neuroimaging is poised to take a substantial leap forward in understanding the neurophysiological underpinnings of human behavior, due to a combination of improved analytic techniques and the quality of imaging data. These advances are allowing researchers to develop population-level multivariate models of the functional brain representations underlying behavior, performance, clinical status and prognosis, and other outcomes. Population-based models can identify patterns of brain activity, or ‘signatures’, that can predict behavior and decode mental states in new individuals, producing generalizable knowledge and highly reproducible maps. These signatures can capture behavior with large effect sizes and can be used and tested across research groups. However, the potential of such signatures is limited by neuroanatomical constraints, in particular individual variation in functional brain anatomy. To circumvent this problem, current models are either applied only to individual participants, severely limiting generalizability, or force participants’ data into anatomical reference spaces (atlases) that do not respect individual functional topology and boundaries. Here we seek to overcome this shortcoming by developing new topographical models for inter-subject alignment, which register participants’ functional brain maps to one another. This increases effective spatial resolution, and more importantly allow us to explicitly analyze the spatial topology of functional maps make inferences on differences in activation location and shape across persons and psychological states. In this talk we discuss several approaches towards functional alignment and highlight promises and pitfalls.



