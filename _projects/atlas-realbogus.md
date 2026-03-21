---
layout: page
title: Training a CNN for ATLAS Real/Bogus Classification
description: A convolutional neural network for transient classification in the ATLAS survey
img: assets/img/publication_preview/model.png
importance: 4
category: research
---

We present a convolutional neural network (CNN) for use in the real–bogus classification of transient detections made by the Asteroid Terrestrial-impact Last Alert System (ATLAS) and subsequent efforts to improve performance since initial development. In transient detection surveys, the number of alerts made outstrips the capacity for human scanning, necessitating the use of machine learning aids to reduce the number of false positives presented to annotators. We take a sample of recently annotated data from each of the three operating ATLAS telescope with ~340,000 real (known transients) and ~1,030,000 bogus detections per model. We retrained the CNN architecture with these data specific to each ATLAS unit, achieving a median false positive rate (FPR) of 0.72 per cent for a 1.00 per cent missed detection rate. Further investigations indicate that if we reduce the input image size it results in increased FPR. Finally architecture adjustments and comparisons to contemporary CNNs indicate that our retrained classifier is providing an optimal FPR. We conclude that the periodic retraining and readjustment of classification models on survey data can yield significant improvements as data drift arising from changes in the optical and detector performance can lead to new features in the model and subsequent deteriorations in performance.

**Published in:** [RAS Techniques and Instruments, 2024](https://doi.org/10.1093/rasti/rzae027)