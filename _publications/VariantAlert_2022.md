---
title: "VariantAlert: a web-based tool to notify updates in genetic variant annotations"
collection: publications
permalink: /publication/VariantAlert_2022
citation: 'Atzeni, R., <b>Massidda, M.</b>, Fotia, G., & Uva, P. (2022). VariantAlert: A web-based tool to notify updates in genetic variant annotations. <i>Human mutation, 10.1002/humu.24495</i>. Advance online publication. https://doi.org/10.1002/humu.24495'
date: 2022-10-27
venue: 'Human Mutation (Oct 2022)'

---

[Download paper here](https://onlinelibrary.wiley.com/doi/epdf/10.1002/humu.24495)


## Abstract
The reinterpretation of variants based on updated annotations is part of the routine work of research laboratories: the more data is collected about a specific variant, the higher the probability to reinterpret its classification. To support this task, we developed VariantAlert, a web-based tool to help researchers and clinicians to be constantly informed about changes in variant annotations extracted from multiple sources. VariantAlert provides daily re-annotation of variants using external resources accessed through application programming interface, such as MyVariant.info providing in turn links to gnomAD, catalogue of somatic mutations In cancer (COSMIC), ClinVar, CIViC, and many others. Researchers and clinicians can submit one or more lists of variants. If a change is detected for the annotation of a variant due to the upgrade of the underlying resource (e.g., change in gnomAD allele frequency, presence in COSMIC database, change in ClinVar classification) the user is notified by email and updated annotations are stored on the web-site. VariantAlert is freely available at https://github.com/next-crs4/VariantAlert. Installation and deployment are easy thanks to the use of the Docker platform. A Makefile allows you to easily bootstrap VariantAlert. VariantAlert is also available as a web service at https://variant-alert.crs4.it/.