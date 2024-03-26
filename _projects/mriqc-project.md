---
title: Is between-pipeline variability affected by image quality?
subtitle: A subcortical segmentation study
status: active
layout: project
repository: https://github.com/neurodatascience/Pipeline-Discrepancy-Exploration
people:
  - Jacob
  - Mohammad
---

We are exploring the correlations between Image Quality Metrics (IQMs) produced by MRIQC with the discrepancy in subcortical structure segmentations produced by FSL, FreeSurfer, and SPM.

This should inform us on whether MRI image quality affects agreements in results obtained using different pipelines. We will carry out the analysis across multiple datasets offering a large range of image quality (Prevent-AD, HCP, CoRR) using the NeuroCI framework.

We have carried out a preliminary verison of the experiment on Prevent-AD using FreeSurfer and FSL (published as an abstract in OHBM 2023), and we found no strong correlations, suggesting that the pipelines discrepancies are rooted in the algorithms employed by the tools rather than the image quality.
