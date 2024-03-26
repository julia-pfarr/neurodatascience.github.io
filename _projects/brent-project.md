---
title: Estimating Polygenic Risk Scores (PRS) on longitudinal changes in Imaging Derived Phenotypes (IDPs)
status: active
layout: project
people:
  - Brent McPherson
---

# Background

The deep phenotyping of populations is increasingly being used to
investigate how the brain, genetics, behavior, and clinical outcomes
interact. Through the collaborative collection of large samples, like
the UK Biobank ([UKBB](https://www.ukbiobank.ac.uk/)), the methods and interpretation of these kinds
of datasets can be reported and applied to real world outcomes. Large
population samples can be used for normative modelling to contrast a
clinical sample, like the Quebec Parkinson's Network ([QPN](https://rpq-qpn.ca/en/home/)) or the
Parkinson's Progression Markers Initiative ([PPMI](https://www.ppmi-info.org/)).

In order to maximize the information available within these samples,
it is important to combine different modalities of information, like
neuroimaging and genetics.

A common way to combine genetics and neuroimaging data is with
genome-wide association studies (GWAS) and the estimation of polygenic
risk scores (PRS). A PRS model can be estimated for each neuroimaging
feature, or an imaging derived phenotype (IDP). This provides a model
that highlights the single nucleotide polymorphisms (SNPs) that
contribute the most variation to the IDP, linking the genetic
contribution to neural expression.

# Methods

My work revolves around contributing high quality imaging derived
phenotypes (IDPs) across multiple datasets (UKBB, QPN, PPMI). This involves utilizing current
standard pre-processing tools for MRI data, like [fMRIPrep](https://fmriprep.org/en/stable/) and
[TractoFlow](https://tractoflow-documentation.readthedocs.io/en/latest/). The analysis, quality control, and indexing of these
derivatives is being contributed through other ongoing projects in the
lab, namely [Nipoppy](https://www.neurobagel.org/documentation/Nipoppy/overview/) and [NeuroBagel](https://www.neurobagel.org/documentation/).

With these high-quality IDPs generated, I am estimating the
variational inference of polygenic risk scores
([VIPRS](https://pubmed.ncbi.nlm.nih.gov/37030289/)). I am extending
this approach by estimating the PRS of the _longitudinal_ change of
the IDPs from the samples. This will more accurately
target the SNPs that correspond to change over time in the IDPs. This
will improve our ability to use these biobanks to identify the neural
and genetic features that correspond with degenerative diseases.

# Goal

My goal with creating these higher quality imaging derivatives (IDPs) is
to combine them with other physiological phenotypes in the sample
(genetics, behavior, clinical status, etc.). Incorporating polygenic
risk scores (PRS) with the imaging phenotypes will allow researchers
to maximize the use of information in these biobanks. By extending
this usage to incorporate longitudinal change in the PRS estimates of
the IDPs we can better identify the multi-modal features that underlie
the transition toward a disease.
