---
title: Cohort creator
subtitle: Creates a neuroimaging cohort by aggregating data across datasets.
status: inactive
layout: project
repository: https://github.com/neurodatascience/cohort_creator
documentation: https://cohort-creator.readthedocs.io/en/latest/
image:
people:
  - Remi
---

The landscape of open neuroimaging datasets is expanding rapidly, with a notable increase in the availability of BIDS (Brain Imaging Data Structure, 1) datasets. Many of these datasets have open derivatives data, (fMRIprep preprocessed data (2) or MRIQC (3) quality control reports). While platforms like OpenNeuro host a significant portion of these datasets and their derivatives, some are scattered across various platforms, necessitating users to navigate different sources.

The introduction of a tool like Neurobagel (4) addresses some of these challenges by enabling users to conduct searches across multiple datasets, providing a comprehensive list of participants that match specific queries. However users interested in a particular subset of data currently face difficulties accessing it seamlessly.

In the current state, users encounter the following issues:

- lack of monitoring for growing open data: there is no easy way for users to obtain regularly updated overviews of the content within these datasets.
- absence of tools facilitating access: users looking to access specific subsets of datasets across various sources encounter a significant challenge.
- no tools for summary reports on content and quality of the accessed data. This deficiency makes it challenging for users to assess the suitability and reliability of the data they intend to use.

The goals of the [`cohort_creator`](https://github.com/neurodatascience/cohort_creator) are:

1. Monitoring BIDS Datasets:
   - Periodically check specified BIDS datasets for updates.
   - Extract metadata about the datasets, such as available modalities, tasks, and participants.
   - Generate reports summarizing changes and additions to the datasets.
2. Aggregating synthetic cohort:
   - Take a neurobagel query results as input to define a cohort of participants to download from several datasets.
   - Access multiple BIDS datasets and their derivatives to aggregate participants.
   - Parametrize the cohort creation to only include the data necessary for certain analysis: for example only download functional MRI or diffusion MRI data
   - Create a synthetic cohort based on the defined criteria and organize this new dataset following the recommendations from the BIDS extension proposal 35 for mega-analysis (5)
3. Generating reports on Cohort Content:
   - Create summary TSV file to report on the status of derivatives availability that can be viewed and browsed with the neurobagel digest dashboard (6).
   - Create MRIQC group summary reports for the subset of participants included in the cohort.
   - Produce reports detailing the number of subjects, basic demographics, imaging modalities, and other relevant information for each datasets included in the cohort.

The cohort-creator package ([https://pypi.org/project/cohort-creator/](https://pypi.org/project/cohort-creator/)) allows access to 1113 datasets containing 48579 subjects representing over 69 terabytes of data. 1018 of those datasets are on openneuro from which 781 datasets contain MRI data with the following available derivatives:

- with fMRIprep output: 97 (4179 subjects)
- with freesurfer output: 38 (3342 subjects)
- with MRIQC output: 333 (14829 subjects)

Following a query on neurobagel providing the user a listing of datasets (`dataset.tsv`) and participants (`participants.tsv`), a user can easily get and reorganize the corresponding data and available derivatives with 3 commands.

The output will include a TSV file summarizing the availability of derivative data for each participant and visualization of for each dataset (for example: number of subject, gender ratio) or for the entire cohort (age distribution for each gender).

## References

1. Gorgolewski, K.J., et al. (2016). The brain imaging data structure, a format for organizing and describing outputs of neuroimaging experiments. Scientific Data. DOI: [10.1038/sdata.2016.44](https://doi.org/10.1038/sdata.2016.44)
2. Esteban, O., et al. (2019). fMRIPrep: a robust preprocessing pipeline for functional MRI. Nat Methods. DOI: [10.1038/s41592-018-0235-4](https://doi.org/10.1038/s41592-018-0235-4)
3. Esteban O, et al. (2017). MRIQC: Advancing the automatic prediction of image quality in MRI from unseen sites. PLOS ONE. DOI: [10.1371/journal.pone.0184661](https://doi.org/10.1371/journal.pone.0184661)
4. Neurobagel-query; URL: [https://query.neurobagel.org](https://query.neurobagel.org); DOI: [10.5281/zenodo.8088224](https://doi.org/10.5281/zenodo.8088224)
5. BIDS extension proposal 35 for mega-analysis; URL: [https://bids.neuroimaging.io/bep035](https://bids.neuroimaging.io/bep035)
6. Neurobagel digest dashboard; URL: [https://digest.neurobagel.org/](https://digest.neurobagel.org/)
