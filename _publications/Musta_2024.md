---
title: "A Novel Affordable and Reliable Framework for Accurate Detection and Comprehensive Analysis of Somatic Mutations in Cancer"
collection: publications
permalink: /publication/Musta_2024
citation: 'Atzeni, R., <b>Massidda, M.</b>, Pieroni, E., Rallo, V., Pisu, M., & Angius, A. (2024). A Novel Affordable and Reliable Framework for Accurate Detection and Comprehensive Analysis of Somatic Mutations in Cancer. <i>International Journal of Molecular Sciences, 25(15), 8044., 10.3390/ijms25158044</i>.'
date: 2024-07-24
venue: 'Int. J. Mol. Sci (Jul 2024)'

---

[Download paper here](https://www.mdpi.com/1422-0067/25/15/8044/pdf?version=1721807322)


## Abstract
Accurate detection and analysis of somatic variants in cancer involve multiple third-party tools with complex dependencies and configurations, leading to laborious, error-prone, and time-consuming data conversions. This approach lacks accuracy, reproducibility, and portability, limiting clinical application. Musta was developed to address these issues as an end-to-end pipeline for detecting, classifying, and interpreting cancer mutations. Musta is based on a Python command-line tool designed to manage tumor-normal samples for precise somatic mutation analysis. The core is a Snakemake-based workflow that covers all key cancer genomics steps, including variant calling, mutational signature deconvolution, variant annotation, driver gene detection, pathway analysis, and tumor heterogeneity estimation. Musta is easy to install on any system via Docker, with a Makefile handling installation, configuration, and execution, allowing for full or partial pipeline runs. Musta has been validated at the CRS4-NGS Core facility and tested on large datasets from The Cancer Genome Atlas and the Beijing Institute of Genomics. Musta has proven robust and flexible for somatic variant analysis in cancer. It is user-friendly, requiring no specialized programming skills, and enables data processing with a single command line. Its reproducibility ensures consistent results across users following the same protocol.