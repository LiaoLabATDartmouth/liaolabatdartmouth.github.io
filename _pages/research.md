---
permalink: /research/
title: "Research"
author_profile: true
redirect_from: 
  - /md/
  - /markdown.html
---

## Direction 1: Metabolic modeling of gut microbiome

__We aim to develop novel computational models (e.g., constraint-based models and machine learning models) to predict metabolic phenotypes (e.g., uptake and secretion of metabolites) of gut bacteria at both cellular and community levels__. In particular, we are interested in short-chain fatty acids (SCFAs), which are the main metabolites produced in the colon by bacterial fermentation of dietary fibers and resistant starch.

__At the cellular level, we are interested in the metabolic regulation of SCFA production. We ask how bacterial cells choose among alternative pathways under given nutrient conditions__. What is the best computational model and the minimal input data for accurate prediction of SCFA concentration? Is a dynamic flux balance model (knowledge-driven) or a machine learning model (data-driven) better? Can we develop a hybrid approach that combines the two types of models (i.e., knowledge-driven machine learning models)? Is genomic sequencing data sufficient for SCFA prediction, or is transcriptomic/proteomic data essential?

__At the community level, we are interested in the metabolic cross-feeding involved in SCFA production__. Well known examples of cross-feeding includes primary fermenters breaking down complex polysaccharides into simpler sugars, which secondary fermenters then utilize to produce acetate, propionate, and butyrate. But what else? Can we detect cross-feeding interactions from microbiome multiomics data? This approach will enable discovery of altered cross-feeding interactions in patients (e.g., cystic fibrosis), which cannot be directly measured in experiments.

__Other projects along this line include spatiotemporal simulation of gut microbiome composition and host-microbiome interactions__. For spatiotemporal simulation, we will develop differential equation models to simulate microbiome responses to external perturbations (e.g., antibiotics) both temporally and spatially. Regarding host-microbiota interactions, we are particularly interested in tryptophan metabolism and the expression of IDO in the kynurenine pathway.

## Direction 2: Spectrometry-based fungal metabolomics

__We aim to establish multiple complementary (experimental and computational) approaches to provide a detailed portrait of metabolic states in fungal pathogens such as *Candida albicans*, *Candida parapsilosis*, and *Aspergillus fumigatus*__. Cellular metabolism encompasses two key aspects: metabolite abundance and metabolic flux, both of which are crucial for a comprehensive understanding of metabolic states and the regulation of metabolic pathways. By developing these methods, we hope to address the most critical questions in fungal pathogenesis, including:

1. Why do some fungal strains colonize patients and cause infections while others are more commonly detected in the environment?
2. The morphological yeast-to-hyphae transition is crucial for *C. albicans* to invade host tissues. What are the metabolic differences between these two morphologies?
3. Fungal pathogens resistant to antifungal drugs may develop mutations in their primary drug targets, which can have a fitness cost. However, some pathogens can rewire their metabolic pathways to compensate for this cost. We ask: how do these fungal pathogens rewire their metabolic pathways to maintain metabolic homeostasis?
4. Although the primary antifungal drug target is undoubtedly important, secondary processes such as cellular metabolism can also affect antimicrobial potency. What are the metabolites and metabolic reactions that confer antifungal drug resistance? These metabolic targets with therapeutic potential will be experimentally validated in the laboratory.

A great challenge in metabolic profiling is that the vast majority of compounds in a mass spectrometry experiment cannot be identified due to limited coverage in existing libraries. **We will address this challenge by (1) developing deep neural network models (e.g., transformers) to predict molecular structures from mass spectra, and (2) using isotope labeling dynamics to provide additional information for compound identification.** Additionally, we are interested in developing a computational pipeline that automates the calculation of isotope labeling patterns from raw mass spectrometry data.

Metabolic flux can be quantified using isotope tracing data through metabolic flux analysis. However, the estimated fluxes are typically limited to a few canonical metabolic pathways. **We aim to develop a new approach that expands flux estimation to include more pathways, ultimately moving towards a genome-scale analysis**. The fundamental concept is to integrate bulk RNA-seq data with isotope labeling data. While metabolic fluxes estimated from isotope labeling data are accurate, they are limited to small-scale metabolic models. In contrast, RNA-seq data provides an indirect but genome-wide assessment of gene and metabolic activity. By combining these two data sources, we hope to leverage the strengths of both approaches.

