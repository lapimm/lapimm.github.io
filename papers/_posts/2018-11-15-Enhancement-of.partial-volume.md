---
layout: paper
title: "Enhancement of partial volume correction in MR-guided PET image reconstruction by using MRI voxel sizes"
year: 2018
shortref:  "Belzunce <i>et al.</i> 2018"
nickname:
journal: "IEEE Transactions on Radiation and Plasma Medical Sciences"
volume: 3
issue: 3
pages: 315-326
authors: "Belzunce MA, Mehranian A, Reader AJ"
image: /assets/images/papers/Enhancement of partial volume correction.jpg
redirect_from: 
fulltext: https://onlinelibrary.wiley.com/doi/full/10.1002/jor.24627
pdflink: /assets/pdfs/Enhancement_of_Partial_Volume_Correction_in_MR-Guided_PET_Image_Reconstruction_by_Using_MRI_Voxel_Sizes.pdf
github: 
pmid: 31245657
pmcid: PMC6528651 
f1000: 
doi: 10.1109/TRPMS.2018.2881248
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

Positron emission tomography (PET) suffers from poor spatial resolution which results in quantitative bias when evaluating the radiotracer uptake in small anatomical regions, such as the striatum in the brain which is of importance in this paper of neurodegenerative diseases. These partial volume effects need to be compensated for by employing partial volume correction (PVC) methods in order to achieve quantitatively accurate images. Two important PVC methods applied during the reconstruction are resolution modeling, which suffers from Gibbs artifacts, and penalized likelihood using anatomical priors. The introduction of clinical simultaneous PET-MR scanners has attracted new attention for the latter methods and brought new opportunities to use MRI information to assist PET image reconstruction in order to improve image quality. In this context, MR images are usually down-sampled to the PET resolution before being used in MR-guided PET reconstruction. However, the reconstruction of PET images using the MRI voxel size could achieve a better utilization of the high resolution anatomical information and improve the PVC obtained with these methods. In this paper, we evaluate the importance of the use of MRI voxel sizes when reconstructing PET images with MR-guided maximum a posteriori (MAP) methods, specifically the modified Bowsher method. We also propose a method to avoid the artifacts that arise when PET reconstructions are performed in a higher resolution matrix than the standard for a given scanner. The MR-guided MAP reconstructions were implemented with a modified Lange prior that included anatomical information with the Bowsher method. The methods were evaluated with and without resolution modeling for simulated and real brain data. We show that the use of the MRI voxel sizes when reconstructing PET images with MR-guided MAP enhances PVC by improving the contrast and reducing the bias in six different regions of the brain using regional metrics for a single simulated data set and ensemble metrics for ten noise realizations. Similar results were obtained for real data, where a good enhancement of the contrast was achieved. The combination of MR-guided MAP reconstruction with point-spread function modeling and MRI voxel sizes proved to be an attractive method to achieve considerable enhancement of PVC, while reducing and controlling the noise level and Gibbs artifacts.