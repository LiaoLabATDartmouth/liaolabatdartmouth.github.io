---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Overview:
The gut microbiota produces a diverse array of metabolites that contribute to various physiological processes and modulate the growth, differentiation, and function of host cells and other microbes. **The primary goal of my lab is to decipher the complex microbe-metabolite interactions within the human gut microbiome**. My lab will employ a combination of computational modeling, microbiology experiments, and clinical data analysis to decipher the complex metabolite-mediated microbe-microbe and host-microbe interactions.

![](lab_directions.png)

## Direction 1: Metabolic modeling of gut microbiome

__We aim to develop novel computational models (e.g., constraint-based models and machine learning models) to predict metabolic phenotypes (e.g., uptake and secretion of metabolites) of gut bacteria at both cellular and community levels__. In particular, we are interested in short-chain fatty acids (SCFAs), which are the main metabolites produced in the colon by bacterial fermentation of dietary fibers and resistant starch.

__Multiple projects are available in my lab__. __At the cellular level, we are interested in the metabolic regulation of SCFA production. We ask how bacterial cells choose among alternative pathways under given nutrient conditions__. What is the best computational model and the minimal input data for accurate prediction of SCFA concentration? Is a dynamic flux balance model (knowledge-driven) or a machine learning model (data-driven) better? Can we develop a hybrid approach that combines the two types of models (i.e., knowledge-driven machine learning models)? Is genomic sequencing data sufficient for SCFA prediction, or is transcriptomic/proteomic data essential?

__At the community level, we are interested in the metabolic cross-feeding involved in SCFA production__. Well known examples of cross-feeding includes primary fermenters breaking down complex polysaccharides into simpler sugars, which secondary fermenters then utilize to produce acetate, propionate, and butyrate. But what else? Can we detect cross-feeding interactions from microbiome multiomics data? This approach will enable discovery of altered cross-feeding interactions in patients (e.g., cystic fibrosis), which cannot be directly measured in experiments.

__Other projects along this line include spatiotemporal simulation of gut microbiome composition and host-microbiome interactions__. For spatiotemporal simulation, we will develop differential equation models to simulate microbiome responses to external perturbations (e.g., antibiotics) both temporally and spatially. Regarding host-microbiota interactions, we are particularly interested in tryptophan metabolism and the expression of IDO in the kynurenine pathway.

## Direction 2: Spectrometry-based fungal metabolomics

__We aim to establish multiple complementary (experimental and computational) approaches to provide a detailed portrait of metabolic states in fungal pathogens such as *Candida albicans*, *Candida parapsilosis*, and *Aspergillus fumigatus*__. Cellular metabolism encompasses two key aspects: metabolite abundance and metabolic flux, both of which are crucial for a comprehensive understanding of metabolic states and the regulation of metabolic pathways. By developing these methods, we hope to address the most critical questions in fungal pathogenesis, including:

1. Why do some fungal strains colonize patients and cause infections while others are more commonly detected in the environment?
2. The morphological yeast-to-hyphae transition is crucial for *C. albicans* to invade host tissues. What are the metabolic differences between these two morphologies?
3. Fungal pathogens resistant to antifungal drugs may develop mutations in their primary drug targets, which can have a fitness cost. However, some pathogens can rewire their metabolic pathways to compensate for this cost. We ask: how do these fungal pathogens rewire their metabolic pathways to maintain metabolic homeostasis?
4. Although the primary antifungal drug target is undoubtedly important, secondary processes such as cellular metabolism can also affect antimicrobial potency. What are the metabolites and metabolic reactions that confer antifungal drug resistance? These metabolic targets with therapeutic potential will be experimentally validated in the laboratory.

A challenge in metabolic profiling is that the vast majority of compounds in an mass spectrometry experiment cannot be identified due to limited coverage in existing libraries. **We aim to address this problem by (1) developing deep neural network models (e.g., transformers) to predict molecular structures from mass spectra, and (2) using isotope labeling dynamics to provide additional information for compound identification.** Currently, natural isotope abundances are manually corrected based on known mass spectrum fragments. We are interested in developing a computational pipeline that can automate the calculation of isotope labeling patterns directly from raw mass spectra (an end-to-end solution).

Metabolic flux can be quantified using isotope tracing data through metabolic flux analysis (MFA). However, the estimated fluxes are typically limited to several canonical metabolic pathways. **We aim to develop a new approach that can expand the estimated fluxes to include more pathways, eventually moving towards the genome scale. The fundamental concept is to integrate bulk RNA-seq data with isotope labeling data. While isotope labeling experiments have traditionally served as the gold standard for flux measurement, they are usually conducted with small metabolic models, primarily focusing on central carbon metabolism. In contrast, RNA-seq data offers a genome-wide assessment of gene and metabolic activity, albeit indirectly. Metabolomics data, both with and without 13C tracers, will be collected using a GC-MS in our lab and analyzed using an in-house pipeline.

