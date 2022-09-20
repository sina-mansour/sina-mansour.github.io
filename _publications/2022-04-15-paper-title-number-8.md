---
title: "Connectome spatial smoothing (CSS): Concepts, methods, and evaluation"
collection: publications
permalink: /publication/2022-04-15-paper-title-number-8
excerpt: "A journal article describing a new methodological approach extending spatial smoothing to connectivity matrices."
date: 2022-04-15
venue: "NeuroImage"
paperurl: 'https://doi.org/10.1016/j.neuroimage.2022.118930'
citation: 'Mansour L., Sina, et al. &quot;Connectome spatial smoothing (CSS): Concepts, methods, and evaluation.&quot; <i>NeuroImage</i> 250 (2022): 118930.'
---

[Article available from here.](https://doi.org/10.1016/j.neuroimage.2022.118930)

## Abstract:

Structural connectomes are increasingly mapped at high spatial resolutions comprising many hundreds—if not thousands—of network nodes. However, high-resolution connectomes are particularly susceptible to image registration misalignment, tractography artifacts, and noise, all of which can lead to reductions in connectome accuracy and test-retest reliability. We investigate a network analogue of image smoothing to address these key challenges. Connectome Spatial Smoothing (CSS) involves jointly applying a carefully chosen smoothing kernel to the two endpoints of each tractography streamline, yielding a spatially smoothed connectivity matrix. We develop computationally efficient methods to perform CSS using a matrix congruence transformation and evaluate a range of different smoothing kernel choices on CSS performance. We find that smoothing substantially improves the identifiability, sensitivity, and test-retest reliability of high-resolution connectivity maps, though at a cost of increasing storage burden. For atlas-based connectomes (i.e. low-resolution connectivity maps), we show that CSS marginally improves the statistical power to detect associations between connectivity and cognitive performance, particularly for connectomes mapped using probabilistic tractography. CSS was also found to enable more reliable statistical inference compared to connectomes without any smoothing. We provide recommendations for optimal smoothing kernel parameters for connectomes mapped using both deterministic and probabilistic tractography. We conclude that spatial smoothing is particularly important for the reliability of high-resolution connectomes, but can also provide benefits at lower parcellation resolutions. We hope that our work enables computationally efficient integration of spatial smoothing into established structural connectome mapping pipelines.
