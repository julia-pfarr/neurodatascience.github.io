---
title: Analytic Flexibility of dMRI Preprocessing and free-water corrected DTI (fwDTI) in Parkinson's Disease (PD)
status: active
layout: project
people:
  - Brent
---

# Background

Parkinson's Disease (PD) is a promininent form of dementia that has
been challenging to prodromally identify. The typical imaging derived
phenotypes (IDPs) that have worked well for other conditions, like
cortical thickness, have failed to reliably predict the prognosis of
the condition. Different modalities, like diffusion magnetic resonance
imaging (dMRI), quantify the movement of water around axons and can be
modeled to describe the qualities of the white matter tissue. Given
the established changes of PD occur in these white matter connections,
it is a promising methods to more reliably predict this disease.

# Methods

dMRI Processing needs to be correctly preprocessed in order to
reliably model the underlying anatomy captured by the scan. Some
steps, such as eddy current and motion correction, are necessary to
reliably interpret the data. Other steps, such as denoising and Gibbs
de-ringing, can be applied with different algorithms at different
stages and may have a differing impact on the eventual
interpretability. Much of this work is being compared through two
pipelines, ([QSIPrep](https://qsiprep.readthedocs.io/en/latest/)) and
([TractoFlow](https://tractoflow-documentation.readthedocs.io/en/latest/)).
These pipelines are largely identical, but standardizing the comparison between similar
tools for identifying their impact on an analysis is important to understand.

The most commonly used model for interpreting dMRI data is the
diffuion tensor (DTI). This summarizes the observed movement of water
within the brain, providing an estimated axis of primary movement
and a measure of isotropy / anisotropy for that orientation. A
free-water corrected tensor (fwDTI) adds an additional anisostropic
metric measuring the "background" isotropy independent of the signal
in the white matter. This information corresponds to surrounding
support tissue of the white matter measured by the regular tensor
components. Changes in this component have been found to correspond to
the clinical progression of PD in different subcortical connections.

# Goal

My goal is to describe the impact of processing decisions on the
ability of diffusion tensor models to make clinically relevant
predictions. I am also exploring the impact of the different
parameterizations and methods of predicting fwDTI. I hope to
identify the processing steps and modeling procedures that maximize
the utility of this promising method. With this model we can better
understand the underlying neural changes associated with PD.
