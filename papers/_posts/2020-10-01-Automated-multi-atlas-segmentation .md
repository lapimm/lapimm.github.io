---
layout: paper
title: Automated multi-atlas segmentation of gluteus maximus from Dixon and T1-weighted magnetic resonance images 
year: 2020
shortref:  "Belzunce <i>et al.</i> 2020"
nickname:
journal: "Magnetic Resonance Materials in Physics, Biology and Medicined"
volume: 33
issue: 
pages: 677-688
authors: "Belzunce MA, Henckel J, Fotiadou A, Di Laura A, Hart, AJ"
image: /assets/images/papers/GluteusMaximusSegmentation.webp
redirect_from: 
fulltext: https://link.springer.com/article/10.1007/s10334-020-00839-3
pdflink: /assets/pdfs/2019_GluteusMaximusSegmentation_accepted.pdf
github: 
pmid: 32152794 
pmcid:  
f1000: 
doi: 10.1007/s10334-020-00839-3
dryad_doi: 
figshare_doi: 
altmetric_id: 
category: paper
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: 
---
{% include JB/setup %}


# Abstract

## Objective
To design, develop and evaluate an automated multi-atlas method for segmentation and volume quantification of gluteus maximus from Dixon and T1-weighted images.

## Materials and methods
The multi-atlas segmentation method uses an atlas library constructed from 15 Dixon MRI scans of healthy subjects. A non-rigid registration between each atlas and the target, followed by majority voting label fusion, is used in the segmentation. We propose a region of interest (ROI) to standardize the measurement of muscle bulk. The method was evaluated using the dice similarity coefficient (DSC) and the relative volume difference (RVD) as metrics, for Dixon and T1-weighted target images.

## Results
The mean(± SD) DSC was 0.94 ± 0.01 for Dixon images, while 0.93 ± 0.02 for T1-weighted. The RVD between the automated and manual segmentation had a mean(± SD) value of 1.5 ± 4.3% for Dixon and 1.5 ± 4.8% for T1-weighted images. In the muscle bulk ROI, the DSC was 0.95 ± 0.01 and the RVD was 0.6 ± 3.8%.

## Conclusion
The method allows an accurate fully automated segmentation of gluteus maximus for Dixon and T1-weighted images and provides a relatively accurate volume measurement in shorter times (~ 20 min) than the current gold-standard manual segmentations (2 h). Visual inspection of the segmentation would be required when higher accuracy is needed.