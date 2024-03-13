---
title: Staging and Subtyping of Parkinson's disease progression with imaging biomarkers
status: active
layout: project
people:
  - Michelle
  - Nikhil
---

## Background

Identifying PD subtypes and disease trajectories aims to improve personalized prognosis and treatment options. So far many PD studies have focused on identifying neuroimaging biomarkers to differetiate between diagnosed cases from healthy controls. However there have been far fewer attempts to model disease _progression_.

Magnetic Resonance Imaging (MRI) has been used to identify potential biomarkers for PD, but there are currently no well-established imaging-based PD biomarkers that can reliably track disease progression. Given the heterogeneous nature of PD, large datasets are needed to accurately capture the various dimensions of the disease, and many studies cannot afford to set aside enough data to validate model performance. As a potential solution to this problem, larger longitudinal datasets can be created by combining data from multiple individual studies; this requires a substantial harmonization effort to ensure that similar measures from different datasets can be used together (see related projects in the lab: [Neurobagel](https://www.neurobagel.org/documentation/) and [`mr_proc`](https://github.com/neurodatascience/mr_proc)).

## Objective

This project aims to identify and validate PD subtypes and stages using MRI biomarkers from multiple large longitudinal cohorts and advanced disease modelling techniques. The end goal is to produce a machine learning model that can predict a PD patient's disease stage and most likely progression course. The overall project can be divided into three steps:

1. Extract relevant MRI biomarkers from various longitudinal PD studies ([Parkinson's Progression Markers Initiative](https://www.ppmi-info.org/), [Quebec Parkinson Network](https://rpq-qpn.ca/en/home/), and others)
2. Define and characterize disease trajectories (i.e., subtypes and stages) using the SuStaIn model ([Young et al., 2018](https://doi.org/10.1038/s41467-018-05892-0))
3. Develop a robust predictive model for PD progression at the level of individual patients
