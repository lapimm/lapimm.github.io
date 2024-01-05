---
layout: paper
title: "Assessment of the impact of modeling axial compression on PET image reconstruction"
year: 2017
shortref:  "Belzunce <i>et al.</i> 2017"
nickname:
journal: "Medical physics"
volume: 44
issue: 10
pages: 5172-5186
authors: "Belzunce MA, Reader AJ"
image: /assets/images/papers/Assessment of the impact of modeling axial compression on PET image reconstruction.jpg
redirect_from: 
fulltext: https://aapm.onlinelibrary.wiley.com/doi/full/10.1002/mp.12454
pdflink: /assets/pdfs/Medical Physics - 2017 - Belzunce - Assessment of the impact of modeling axial compression on PET image reconstruction.pdf
github: 
pmid: 28681375
pmcid: 
f1000: 
doi: 10.1002/mp.12454
dryad_doi: 
figshare_doi: 
# Note: 'published' is a Jekyll keyword and does not refer to whether the paper is published, but rather to whether this Markdown should be part of the rendered site.
altmetric_id: 
category: paper
published: true
preprint: false
embargo: false	
peerreview: true
review: false
tags: 
---
{% include JB/setup %}


# Abstract


## Purpose: 
To comprehensively evaluate both the acceleration and image-quality impacts of axial compression and its degree of modeling in fully 3D PET image reconstruction.

## Method: 
Despite being used since the very dawn of 3D PET reconstruction, there are still no extensive studies on the impact of axial compression and its degree of modeling during reconstruction on the end-point reconstructed image quality. In this work, an evaluation of the impact of axial compression on the image quality is performed by extensively simulating data with span values from 1 to 121. In addition, two methods for modeling the axial compression in the reconstruction were evaluated. The first method models the axial compression in the system matrix, while the second method uses an unmatched projector/backprojector, where the axial compression is modeled only in the forward projector. The different system matrices were analyzed by computing their singular values and the point response functions for small subregions of the FOV. The two methods were evaluated with simulated and real data for the Biograph mMR scanner.

## Results: 
For the simulated data, the axial compression with span values lower than 7 did not show a decrease in the contrast of the reconstructed images. For span 11, the standard sinogram size of the mMR scanner, losses of contrast in the range of 5-10 percentage points were observed when measured for a hot lesion. For higher span values, the spatial resolution was degraded considerably. However, impressively, for all span values of 21 and lower, modeling the axial compression in the system matrix compensated for the spatial resolution degradation and obtained similar contrast values as the span 1 reconstructions. Such approaches have the same processing times as span 1 reconstructions, but they permit significant reduction in storage requirements for the fully 3D sinograms. For higher span values, the system has a large condition number and it is therefore difficult to recover accurately the higher frequencies. Modeling the axial compression also achieved a lower coefficient of variation but with an increase of intervoxel correlations. The unmatched projector/backprojector achieved similar contrast values to the matched version at considerably lower reconstruction times, but at the cost of noisier images. For a line source scan, the reconstructions with modeling of the axial compression achieved similar resolution to the span 1 reconstructions.

## Conclusions
 Axial compression applied to PET sinograms was found to have a negligible impact for span values lower than 7. For span values up to 21, the spatial resolution degradation due to the axial compression can be almost completely compensated for by modeling this effect in the system matrix at the expense of considerably larger processing times and higher intervoxel correlations, while retaining the storage benefit of compressed data. For even higher span values, the resolution loss cannot be completely compensated possibly due to an effective null space in the system. The use of an unmatched projector/backprojector proved to be a practical solution to compensate for the spatial resolution degradation at a reasonable computational cost but can lead to noisier images.