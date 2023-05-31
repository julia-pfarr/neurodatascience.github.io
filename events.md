---
layout: default
title: NeuroImaging Statistics - July 27th 2023 - Montreal Neurological Institute
---

## NeuroImaging Statistics Satellite 
We’re pleased to announce a satellite event to the 2023 Organisation for Human Brain Mapping (OHBM) meeting, the Neuroimaging Statistics Workshop, as a means to foster collaboration and generate ideas among statisticians working with brain data.

The event will take place at the Montreal Neurological Institute on Thursday 27th July (the day after the close of OHBM).  There will be 4 keynote speakers, starting with the Keith Worsley lecture delivered by Jonathan Taylor, Keith’s prolific student and author of the seminal text “Random Fields and Geometry” with Robert J. Adler.  

### Register to attend 
The space is limited, please use [this link](https://forms.gle/CWjZsvdugcHzQKP2A ) to register to the event.
<!-- … 
https://forms.gle/CWjZsvdugcHzQKP2A
-->
<br/>

### Program

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

##### 12:30-13:30 Lunch break (sponsored by ASA-statistics in imaging)

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

### Venue: De Grand Pré Conference Centre
De grand pré, Montreal Neurological Institute, McGill University, 3801 Rue University, Montréal, QC H3A 2B4, Canada


#### Sponsors: ASA statistics in imaging section
<img src="./ASA-SI-logo.png"
     alt="ASA-SI-logo"
     style="float: left; margin-right: 10px;" />

<br/>

#### Abstracts:

Jonathan Taylor: Random field theory meets the LASSO

Random field theory (RFT) has long been used widely used tool for assessing significance in SPMs by analyzing a model of the SPM under a global null.  We describe a method to build and compare models under alternative models with peaks selected by the SPM itself. The selection method is a variant of the LASSO which lends itself to analysis with the methods of selective inference, including a tractable approximate likelihood theory. The likelihood analysis allows much of the common tasks in likelihood based models: interval estimation for effect size, confidence ellipsoids for peak locations, Bayesian analysis with priors solicited after selection of peaks.

Amanda Mejia: Rethinking scrubbing in fMRI from a statistical perspective

Scrubbing" or removal of fMRI volumes potentially contaminated with head motion-induced noise has become common practice in fMRI analysis. However, the removal of volumes based on head motion measures alone has become increasingly flawed for a number of reasons. These include a lack of adaptiveness to improved data denoising techniques such as ICA-FIX and aCompCor, poor generalizability to multi-band acquisitions, and over-aggressive removal of volumes with more stringent motion thresholds, often resulting in exclusion of half or more of all sessions. Statistical approaches based on abnormalities in the fMRI timeseries address many of these limitations. In this talk, I will present recent data-driven alternatives to motion scrubbing and illustrate their potential for dramatically increasing sample sizes in fMRI analysis.


Jelle Goeman: Cluster extent inference revisited: quantification and localization of brain activity

Cluster inference based on spatial extent thresholding is a popular analysis method for finding activated brain areas in neuroimaging. However, the method as currently defined has several well-known issues. While powerful for finding regions with some activation, the method does not allow any further quantification or localization of signal. In this paper we repair this gap.  We show that cluster-extent inference can be used (1.) for inference on the presence of signal in any region of interest and (2.) to quantify the percentage of activation in such regions. These additional inferences come for free, i.e. they do not require any further adjustment of the alpha-level of tests, while retaining full familywise error rate control. We achieve this extension of the possibilities of cluster inference by an embedding of the method into a closed testing procedure, and solving the graph-theoretic k-separator problem that results from this embedding. Our construction shows that classic cluster extent inference is a special case of a category of methods that control True Discovery Proportions for simultaneously for all brain regions, and we compare the method to alternatives such as All-Resolutions Inference. We demonstrate the methods in a large-scale application to data from the Neurovault database.

Martin Linquist: Individualized spatial topography in functional neuroimaging 

Neuroimaging is poised to take a substantial leap forward in understanding the neurophysiological underpinnings of human behavior, due to a combination of improved analytic techniques and the quality of imaging data. These advances are allowing researchers to develop population-level multivariate models of the functional brain representations underlying behavior, performance, clinical status and prognosis, and other outcomes. Population-based models can identify patterns of brain activity, or ‘signatures’, that can predict behavior and decode mental states in new individuals, producing generalizable knowledge and highly reproducible maps. These signatures can capture behavior with large effect sizes and can be used and tested across research groups. However, the potential of such signatures is limited by neuroanatomical constraints, in particular individual variation in functional brain anatomy. To circumvent this problem, current models are either applied only to individual participants, severely limiting generalizability, or force participants’ data into anatomical reference spaces (atlases) that do not respect individual functional topology and boundaries. Here we seek to overcome this shortcoming by developing new topographical models for inter-subject alignment, which register participants’ functional brain maps to one another. This increases effective spatial resolution, and more importantly allow us to explicitly analyze the spatial topology of functional maps make inferences on differences in activation location and shape across persons and psychological states. In this talk we discuss several approaches towards functional alignment and highlight promises and pitfalls.



Samuel Davenport: Accurate voxelwise FWER control in fMRI using Random Field Theory

Abstract: In this talk I will discuss improvements to the current use of Random Field Theory (RFT) for performing multiple testing in neuroimaging. RFT has a long established history of being used for multiple testing (Worsley 1996). However recent work (Eklund 2016) showed that, using large resting state based analyses, many of the standard assumptions of RFT (i.e. smoothness, stationary and Gaussianity) do not hold in fMRI. As a result traditional means of applying this framework cannot be relied upon to control false positive rates. I will show how it is possible to get around these standard assumptions. Moreover I will demonstrate that this results in a fast framework for performing multiple testing inference in fMRI which correctly controls the voxelwise false positive rate. I will present resting state validations based on 7000 subjects from the UK BioBank in order to demonstrate that the error rate is correctly controlled in practice.

Sarah Weinstein: Spatially-enhanced clusterwise inference for testing and localizing intermodal correspondence

Abstract: With the increasing availability of neuroimaging data from multiple modalities--each providing a different lens through which to study brain structure or function--new techniques for comparing spatial patterns shared across modalities are emerging. Until recently, statistical methods in this area have primarily evaluated global inter-modal associations--for example, testing whether associations exist throughout the entire brain or within pre-defined subregions or functional networks. Here, we propose CLEAN-R, a method for spatial localization of inter-modal associations (Weinstein et al., 2022, NeuroImage). Our method involves first adjusting for hetereogeneity in spatial autocorrelation between modalities before conducting clusterwise inference on inter-modal correlations to construct an interpretable map of “spatially enhanced” test statistics. Through simulation studies using multi-modal neuroimaging data from the Philadelphia Neurodevelopmental Cohort, we illustrate our method’s power, interpretability, and its ability to replicate findings in small-sample settings.
Software is publicly available at https://github.com/junjypark/CLEAN/.

Bertrand Thirion: False Discovery Proportion control for aggregated Knockoffs

We present a novel method, KOPI, that achieves False Discovery Proportion (FDP) control for Knockoffs-based inference, a popular statistical tool for conditional variable selection in high dimension. The proposed method also leverages a novel type of aggregation to address the undesired randomness associated with classical Knockoffs inference. We demonstrate FDP control and substantial power gains over existing state-of-the art Knockoffs-based methods in various simulation settings and obtain good sensitivity/specificity tradeoffs on brain imaging data.

Chris Camp: Contextualizing classification accuracy within effect sizes

Biomarkers in neuroimaging are typically evaluated on the strength of their association, or effect size, with a phenotype of interest. Alternatively, machine learning models can be trained on potential biomarkers to classify individuals and evaluated on their accuracy. Although classification accuracy is dependent on the effect size of the features of interest, no work thus far has illustrated the translation of Cohen’s d effect sizes and classification accuracy in models of real-world data. We used simulated neuroimaging data to investigate the relationship between effect size and classification accuracy. We further explored the effects of variance, sample size, and reliability in both univariate and multivariate models to develop a comprehensive understanding of this relationship. This work provides a contextualization of practical classification accuracies within conventional effect sizes. 

Yifan Yu: Neuroimaging Meta Regression for Coordinate Based Meta Analysis Data with a Spatial Model

Abstract: Coordinate-based meta-analysis combines evidence from a collection of Neuroimaging studies to estimate brain activation. In such analyses, a key practical challenge is to find a computationally efficient approach with good statistical interpretability to model the locations of activation foci. In this work, we propose a generative coordinate-based meta-regression (CBMR) framework to approximate smooth activation intensity function and investigate the effect of study-level covariates (e.g., year of publication, sample size). We employ spline parameterisation to model spatial structure of brain activation and consider four stochastic models for modelling the random variation in foci. To examine the validity of CBMR, we estimate brain activation on 20 meta-analytic datasets, conduct spatial homogeneity tests at voxel level, and compare to results generated by existing kernel-based approaches

Jun Young Park: SAN-GP: Mitigating inter-scanner biases in high-dimensional neuroimaging data via spatial Gaussian process

SAN-GP: Mitigating inter-scanner biases in high-dimensional neuroimaging data via spatial Gaussian process In neuroimaging studies, combining data collected from multiple study sites or scanners is becoming common to increase the reproducibility of scientific discoveries. At the same time, unwanted variations arise by using different scanners (inter-scanner biases), which need to be corrected before downstream analyses. While statistical harmonization methods such as ComBat (Johnson et al., 2007) have become popular in mitigating inter-scanner biases in neuroimaging, recent methodological advances have shown that harmonizing heterogeneous covariances result in higher data quality. Our work proposes a new statistical harmonization method called SAN-GP (Spatial Autocorrelation Normalization via Gaussian Process) that preserves homogeneous covariance vertex-level cortical thickness data across different scanners. We use an explicit Gaussian process to characterize scanner-invariant and scanner-specific variations to reconstruct spatially homogeneous data across scanners. SAN-GP is computationally efficient, and it easily allows the integration of existing harmonization methods. We demonstrate the utility of the proposed method using cortical thickness data from the Social Processes Initiative in the Neurobiology of the Schizophrenia(s) (SPINS) study.


Ian-Christopher Tanoh: A scalable multivariate Bayesian polygenic model for heritability-based principal component analysis

Abstract: Genome-wide association studies (GWAS) of neuroimaging phenotypes can advance our understanding of human brain intrinsic organisation by discovering genetic variants associated with normal and disorder-related phenotypic variance in brain structure and function. Joint modelling of correlated brain imaging phenotypes can improve GWA statistical power and need for multiple comparisons correction. It has been shown dimensionality reduction methods that use the estimated genetic correlation matrix to combine phenotypes with maximum heritability outperforms multivariate regression. However, existing methods to estimate genetic and environmental covariance matrices are not scalable to large scale studies or across all brain regions. In this work we propose a scalable hierarchical Bayesian model to a) estimate the covariance matrices by fitting a single multivariate model to all traits simultaneously, not a series of bivariate models and b) exploit the estimated heritability and genetic correlation matrix to define new phenotypes with maximum heritability.


Habib Ganjgahi: Scalable Hierarchical Bayesian Model for Multiple Sclerosis Progression using Brain Imaging and Clinical Features

Multiple sclerosis (MS) is a chronic and ultimately debilitating disease of the central nervous system that affects approximately 2.5 million individuals worldwide. MS subtypes have been defined only based on the clinical disease course of patients (relapse and physical disability), they reveal limitations in prognosticating long-term outcome, or in providing homogeneous treatment targets. However, there is growing evidence that MS patients suffer from neurodegeneration, inflation measured by different magnetic resonance imaging (MRI) modalities and cognitive impairment.
We have developed a scalable multivariate hierarchical Bayesian model (probabilistic latent variable followed by hidden Markov model (HMM)) that can handle different data modalities (binary, count, ordinal and continuous variables) and structured missingness to characterize MS progression in a data driven way using both brain imaging and clinical variables. The proposed model 1) exploits shared information between different brain imaging modalities and clinical variables to find key MS dimensions and corresponding composite scores 2) discover and describe homogeneous states of MS based on composite scores change over time by putting HMM prior on the latent variables.
The method was applied to the NO.MS dataset which is currently the largest and most comprehensive clinical trial dataset in MS with longitudinal data on more than 8000 MS patients that contains both clinical assessments (relapse occurrence, cognitive performance, physical disability status, walking speed and hand coordination) and brain imaging markers (brain atrophy, T2 lesion volume, T1 Gd lesion). We discovered four key-dimensions of MS: a) physical disability; b) subclinical disease burden/associated cognitive deficits; ongoing inflammation either as c) MRI lesions and/or d) clinical relapses. We identified 9 states which can be grouped into 4 clinical Meta-states solely based on transition probability matrix clustering that allow a complete description: i) Early MS (clinically stable patients), ii) acute relapse, iii) transition state and iv) evolved MS.

