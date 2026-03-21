---
layout: page
title: Transient Host Matching in LSST Deep Drilling Fields
description: Galaxy catalogue compilation and host-matching for LSST transients
img: assets/img/publication_preview/ddf.png
importance: 3
category: research
---

The upcoming Vera C. Rubin Observatory Legacy Survey of Space and Time (LSST) will enable astronomers to discover rare and distant astrophysical transients. Host-galaxy association is crucial for selecting the most scientifically interesting transients for follow-up. LSST Deep Drilling Field observations will detect distant transients occurring in galaxies below the detection limits of most all-sky catalogues. Here we investigate the use of pre-existing smaller-scale, field-specific catalogues for host identification in the Deep Drilling Fields (DDFs) and a ranking of their usefulness. We have compiled a database of 70 deep catalogues that overlap with the Rubin DDFs and constructed thin catalogues to be homogenised and combined for transient-host matching. A systematic ranking of their utility is discussed and applied based on the inclusion of information such as spectroscopic redshifts and morphological information. Utilising this data against a Dark Energy Survey (DES) sample of supernovae with pre-identified hosts in the XMM-LSS and ECDFS fields, we evaluate different methods for transient-host association in terms of both accuracy and processing speed. We also apply light data-cleaning techniques to identify and remove contaminants within our associations, such as diffraction spikes and blended galaxies where the correct host cannot be determined with confidence. We use a lightweight machine learning approach in the form of extreme gradient boosting to generate confidence scores in our contaminant selections and associated metrics. Finally, we discuss the computational expense of implementation within the LSST transient alert brokers, which will require efficient, fast-paced processing to handle the large stream of survey data.

**Published in:** [arXiv, 2025](https://arxiv.org/abs/2511.22634)