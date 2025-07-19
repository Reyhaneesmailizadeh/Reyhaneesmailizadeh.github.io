---
title: "SLOTMFound: Foundation-Based Diagnosis of Multiple Sclerosis Using Retinal SLO Imaging and OCT Thickness-maps."
collection: publications
category: manuscripts
permalink: /publication/2009-10-01-paper-title-number-1
excerpt: 'Analyzing the potential of vision transformer foundation models and bi-modality in image recognition.'
date: 2025-07-14
venue: 'MedArxiv as Preprint. Accepted at ICMV 2025'
paperurl: 'https://www.medrxiv.org/content/10.1101/2025.07.14.25331522v1'
---
Multiple Sclerosis (MS) is a chronic autoimmune disorder of the central nervous system that can lead to significant neurological disability. Retinal imaging—particularly Scanning Laser Ophthalmoscopy (SLO) and Optical Coherence Tomography (OCT)—provides valuable biomarkers for early MS diagnosis through non-invasive visualization of neurodegenerative changes. This study proposes a foundation-based bi-modal classification framework that integrates SLO images and OCT-derived retinal thickness maps for MS diagnosis. To facilitate this, we introduce two modality-specific foundation models—SLOFound and TMFound—fine-tuned from the RETFound-Fundus backbone using an independent dataset of 203 healthy eyes, acquired at Noor Ophthalmology Hospital with the Heidelberg Spectralis HRA+OCT system. This dataset, which contains only normal cases, was used exclusively for encoder adaptation and is entirely disjoint from the classification dataset. For the classification stage, we use a separate dataset comprising IR-SLO images from 32 MS patients and 70 healthy controls, collected at the Kashani Comprehensive MS Center in Isfahan, Iran. We first assess OCT-derived maps layer-wise and identify the Ganglion Cell–Inner Plexiform Layer (GCIPL) as the most informative for MS detection. All subsequent analyses utilize GCIPL thickness maps in conjunction with SLO images. Experimental evaluations on the MS classification dataset demonstrate that our foundation-based bi-modal model outperforms unimodal variants and a prior ResNet-based state-of-the-art model, achieving a classification accuracy of 97.37%, with perfect sensitivity (100%). These results highlight the effectiveness of leveraging pre-trained foundation models, even when fine-tuned on limited data, to build robust, efficient, and generalizable diagnostic tools for MS in medical imaging contexts where labeled datasets are often scarce.

