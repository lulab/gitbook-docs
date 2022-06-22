---
description: cfRNA (cell-free RNA) is also called exRNA (extracellular RNA)
---

# cfRNA-seq Analysis

> [**PDFs**](https://cloud.tsinghua.edu.cn/d/07d2b19d6b284ebea5ea/?p=%2F2.%20Precision%20Medicine\&mode=list)****

## I. Pipelines

* \[small cfRNA-seq] ** **_**2019 Cell Sys. -**_** exceRpt:** A Comprehensive Analytic Platform for Extracellular RNA Profiling
* \[long and small cfRNA-seq] [exSEEK Tutorial](https://lulab2.gitbook.io/teaching/part-v.-quiz/1.quiz\_exrna)
* \[long cfRNA-seq] [cfRNA-SEEK Github](https://lulab.github.io/cfRNA-SEEK/)&#x20;

## II. Data Clean and Normalization

> **Imputation, Normalization and Batch Correction**

* **Methods for Single Cell RNA-seq**&#x20;
  * (1) Dropout/Sparseness and Imputation
  * (2) Heterogeneity and Normalization
  * (3) Batch effect and Confounder
  * (Pseudo-time and Others)
* **Recommendations**:
  * **2020 **_**Nature COMMN**_** ** - Embracing the dropouts in single-cell RNA-seq analysis
  * **2019 - **_**Nature Methods**_ - A discriminative learning approach to differential expression analysis for single-cell RNA-seq
  * **✨ Review**: **2017 - **_**Nature Methods**_** ** - Normalizing single-cell RNA sequencing data: challenges and opportunities
  * **MNN**: **2017 - **_**Nature Biotech.**_ - Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors

> * (1) Dropout/Sparseness and Imputation
> * (2) Heterogeneity and Normalization
> * (3) Batch effect and Confounder
> * (Pseudo-time and Others)
>
> [Tutorial](https://lulab1.gitbook.io/training/part-iii.-case-studies/case-study-1.exrna-seq/1.4.normalization-issues)

## III. Feature Selection & Optimization

> **Signature genes/pathways and network approach**

### 1.  Signature Genes and Feature Selection

* **✨ **_**2021 Nature Machine Intelligence**_ - Integration of multiomics data with graph convolutional networks to identify new cancer genes and their associated molecular mechanisms
* _**2021 Nature Biotech.** _ - Gene signature extraction and cell identity recognition at the single-cell level with Cell-ID
* _**2021 Genome Res.**_ - NS-Forest: A machine learning method for the discovery of minimum marker gene combinations for cell type identification from single-cell RNA sequencing
* _**2019 Briefings in Bioinformatics**_ - A comprehensive evaluation of connectivity methods for L1000 data Briefings in Bioinformatics

### 2. Network Approach&#x20;

* _**2021 Nature Computational Science**_ - Modeling gene regulatory networks using neural network architectures
* **✨ 2021 **_**Cell**_** ** - **** A modular master regulator landscape controls cancer transcriptional identity
* **✨ 2017 **_**Nature Methods**_** -** SCENIC: single-cell regulatory network inference and clustering
* **2018 **_**Nature COMMN.**_** -** Pathway based subnetworks enable cross-disease biomarker discovery

### 3. Deep Learning Approach

* **2020 **_**Bioinformatics**_** -** Deeptype - Deep-learning approach to identifying cancer subtypes using high-dimensional genomic data

## IV. Feature Engineering

### 1. New RNA features

* [**POSTAR**](../rna/postar.md): editing, splicing, modification, APA, chimeric RNA, etc
* **✨** \[**TmS**: **total mRNA expression**] **2022 **_**Nature Biotech.**_ - Estimation of tumor cell total mRNA expression in 15 cancer types predicts disease progression

### 2. cfRNA frag. & motif

* **✨ miRNA motif - **_**2021 Nature**_** -** MicroRNA sequence codes for small extracellular vesicle release and cellular retention
* **sRNA cluster: 2021 Gut** - Unannotated small RNA clusters associated with circulating extracellular vesicles detect early stage liver cancer
* **Fragmented ribosomes: 2020 NAR** - Fragmentation of extracellular ribosomes and tRNAs shapes the extracellular RNAome ([link](https://academic.oup.com/nar/article/48/22/12874/5891565))
* **mRNA frag. :  2020 elife** - Identification of protein-protected mRNA fragments and structured excised intron RNAs in human plasma by TGIRT-seq peak calling
* **tsRNA: 2019 Molecular Cancer** - Exosomal tRNA-derived small RNA as a promising biomarker for cancer diagnosis
* **mRNA/lncRNA frag.: 2019 EMBO J.** - Phospho‐RNA‐seq: a modified small RNA‐seq method that reveals circulating mRNA and lncRNA fragments as potential biomarkers in human plasma
* **srpRNA domain (RNA7SL1)**: **2019 Clinical Chem.** - Noncoding RNAs serve as diagnosis and prognosis biomarkers for hepatocellular carcinoma

## V. Origin of Tissue and Tumor Location Method

* **✨ 2017 **_**Genome Biology**_** ** - CancerLocator: non-invasive cancer diagnosis and tissue-of-origin prediction using methylation profiles of cell-free DNA
* **✨ Deconvolution**: **2022 **_**Nature Biotech.**_ - Cell types of origin of the cell-free transcriptome





