---
layout: paper
title: "Technical Note: Ultra high-resolution radiotracer-specific digital pet brain phantoms based on the BigBrain atlas"

year: 2020
shortref:  "Belzunce <i>et al.</i> 2020"
nickname:
journal: "Medical Physics"
volume: 47
issue: 8
pages: 3356-3362
authors: "Belzunce MA, Reader AJ"
image: /assets/images/papers/Ultra-high‐resolution-radiotracer.jpg
redirect_from: 
fulltext: https://linkinghub.elsevier.com/retrieve/pii/S0730-725X(20)30171-5
pdflink: /assets/pdfs/Medical Physics - 2020 - Belzunce - Technical Note  Ultra high‐resolution radiotracer‐specific digital pet brain phantoms.pdf
github: 
pmid: 32368798
pmcid:  
f1000: 
doi:  10.1002/mp.14218
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
## Purpose
To introduce a method that allows the generation of ultra high-resolution (submillimeter) heterogeneous digital PET brain phantoms and to provide a new publicly available [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0001 ]FDG phantom as an example.

## Method
The radiotracer distribution of the phantom is estimated by minimizing the Kullback–Leibler distance between the parameterized unknown phantom distribution and a radiotracer-specific template used as a reference. The phantom is modelled using the histological and tissue classified volumes of the BigBrain atlas to provide both high resolution and heterogeneity. The Hammersmith brain atlas is also included to allow the estimation of different activity values in different anatomical regions of the brain. Using this method, a realistic [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0002 ]FDG phantom was produced, where a single real [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0003 ]FDG scan was used as the reference to match. An MRI T1-weighted image, obtained from the BigBrain atlas, and a pseudo-CT are included to complete the dataset. A full PET-MRI dataset was simulated and reconstructed with MR-guided methods for the new [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0004 ]FDG phantom.

## Results
An ultra high-resolution (400 μm voxel size) and heterogeneous phantom for [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0005 ]FDG was obtained. The radiotracer activity follows the patterns observed in the scan used as a reference. The simulated PET-MRI dataset provided a realistic simulation that was able to be reconstructed with MR-guided methods. By visual inspection, the reconstructed images showed similar patterns to the real data and the improvements in contrast and noise with respect to the standard MLEM reconstruction were more modest compared to simulations done with a simpler phantom, which was created from the same MRI image used to assist the reconstruction.

## Conclusions
A method to create high-resolution heterogeneous digital brain phantoms for different PET radiotracers has been presented and successfully employed to create a new publicly available [ urn:x-wiley:00942405:media:mp14218:mp14218-math-0006 ]FDG phantom. The generated phantom is of high resolution, is heterogeneous, and simulates the uptake of the radiotracer in the different regions of the brain.