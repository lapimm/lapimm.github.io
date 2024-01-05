---
layout: paper
title: "Time-invariant component-based normalization for a simultaneous PET-MR scanner"
year: 2016
shortref:  "Belzunce <i>et al.</i> 2016"
nickname:
journal: "Physics in Medicine & Biology"
volume: 61
issue: 9
pages: 3554
authors: "Belzunce MA, Reader AJ"
image: /assets/images/papers/time_invariant_comp.jpg
redirect_from: 
fulltext: https://iopscience.iop.org/article/10.1088/0031-9155/61/9/3554/meta
pdflink: /assets/pdfs/Belzunce_2016_Phys._Med._Biol._61_3554.pdf
github: 
pmid: 27054290
pmcid: 
f1000: 
doi: 10.1088/0031-9155/61/9/3554
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


Component-based normalization is a method used to compensate for the sensitivity of each of the lines of response acquired in positron emission tomography. This method consists of modelling the sensitivity of each line of response as a product of multiple factors, which can be classified as time-invariant, time-variant and acquisition-dependent components. Typical time-variant factors are the intrinsic crystal efficiencies, which are needed to be updated by a regular normalization scan. Failure to do so would in principle generate artifacts in the reconstructed images due to the use of out of date time-variant factors. For this reason, an assessment of the variability and the impact of the crystal efficiencies in the reconstructed images is important to determine the frequency needed for the normalization scans, as well as to estimate the error obtained when an inappropriate normalization is used. Furthermore, if the fluctuations of these components are low enough, they could be neglected and nearly artifact-free reconstructions become achievable without performing a regular normalization scan. In this work, we analyse the impact of the time-variant factors in the component-based normalization used in the Biograph mMR scanner, but the work is applicable to other PET scanners. These factors are the intrinsic crystal efficiencies and the axial factors. For the latter, we propose a new method to obtain fixed axial factors that was validated with simulated data. Regarding the crystal efficiencies, we assessed their fluctuations during a period of 230 d and we found that they had good stability and low dispersion. We studied the impact of not including the intrinsic crystal efficiencies in the normalization when reconstructing simulated and real data. Based on this assessment and using the fixed axial factors, we propose the use of a time-invariant normalization that is able to achieve comparable results to the standard, daily updated, normalization factors used in this scanner. Moreover, to extend the analysis to other scanners, we generated distributions of crystal efficiencies with greater fluctuations than those found in the Biograph mMR scanner and evaluated their impact in simulations with a wide variety of noise levels. An important finding of this work is that a regular normalization scan is not needed in scanners with photodetectors with relatively low dispersion in their efficiencies.