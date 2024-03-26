---
title: Neurobagel
subtitle: Neuro(imaging) metadata integration and search
status: active
layout: project
image: img/projects/neurobagel_logo.png
documentation: https://neurobagel.org/
people:
  - Sebastian
  - Jonathan
  - Arman
  - Alyssa
---

Despite the progress in neuroimaging data sharing, defining study samples which fit specific research aims or criteria remains a challenge due to the distributed storage of datasets and inter-dataset heterogeneity in phenotypic and imaging data labels. The Neurobagel tool ecosystem enables the integration of heterogeneous neuroimaging datasets at the subject level via annotation that uses a unified metadata schema. Once annotated, these datasets can then be queried via federated search to form new, cross-dataset cohorts.

[Neurobagel](https://github.com/neurobagel) currently comprises the following interrelated tools:

- `/annotate` - browser-based phenotypic data annotator
- `/bagel-cli` - CLI for creating subject-specific phenotypic and imaging data dictionaries
- `/query-tool` - browser-based app for querying Neurobagel subject data graph
- `/api` - REST API for Neurobagel graph operations
- `/dash` - browser-based dashboard for statuses of image processing tasks and derivatives
