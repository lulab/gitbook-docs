---
description: MethodcfRNA (cell-free RNA) is also called exRNA (extracellular RNA)
---

# cfRNA-seq Analysis

> [**PDFs**](https://cloud.tsinghua.edu.cn/d/07d2b19d6b284ebea5ea/?p=%2F1.%20Precision%20Medicine\&mode=list)
>
> ✅ or ✨ **: recommended readings**

## I. Pipelines

* \[small cfRNA-seq] _**2019 Cell Sys. -**_**&#x20;exceRpt:** A Comprehensive Analytic Platform for Extracellular RNA Profiling
* \[long and small cfRNA-seq] [exSEEK Tutorial](https://lulab2.gitbook.io/teaching/part-v.-quiz/1.quiz_exrna)
* \[long cfRNA-seq] [cfRNA-SEEK Github](https://lulab.github.io/cfRNA-SEEK/)&#x20;

## II. RNA Feature Extraction

{% hint style="info" %}
* see more in [**RNA Regulation**](postar.md): editing, splicing, modification, APA, chimeric RNA, etc
* learn from [**cfDNA features**](../med/liquid-biopsy/#ii.-cfdna)
{% endhint %}

### II.1. RNA motif

* ( ✅ **2023 PNAS** - Fragmentation landscape of cell-free DNA revealed by deconvolutional analysis of end motifs )
* ✅ **miRNA motif -&#x20;**_**2021 Nature**_**&#x20;-** MicroRNA sequence codes for small extracellular vesicle release and cellular retention
* G-quadruplex - _**2020 Genome biology**_ - RNA G-quadruplex structures exist and function in vivo in plants
* G-quadruplex - _**2016 Science** -_ RNA G-quadruplexes are globally unfolded in eukaryotic cells and depleted in bacteria

### II.2. RNA fragment (novel sncRNA)

* Peak calling: **2022 Genome Biology** - GoPeaks: histone modification peak calling for CUT\&Tag
* **2021 PNAS** - Small noncoding RNA profiling across cellular and biofluid compartments and their implications for multiple sclerosis immunopathology
* [**2021 NAR**](https://www.ncbi.nlm.nih.gov/pubmed/33772581) **-** Computational meta-analysis of ribosomal RNA fragments: potential targets and interaction mechanisms
* **sRNA cluster: 2021 Gut** - Unannotated small RNA clusters associated with circulating extracellular vesicles detect early stage liver cancer
* [**2020 Mol. Cancer** ](https://www.ncbi.nlm.nih.gov/pubmed/33176804)- Peripheral blood non-canonical small non-coding RNAs as novel biomarkers in lung cancer
* **Fragmented ribosomes: 2020 NAR** - Fragmentation of extracellular ribosomes and tRNAs shapes the extracellular RNAome
* ✅ **mRNA frag. :  2020 elife** - Identification of protein-protected mRNA fragments and structured excised intron RNAs in human plasma by TGIRT-seq peak calling
* **tsRNA: 2019 Molecular Cancer** - Exosomal tRNA-derived small RNA as a promising biomarker for cancer diagnosis
* **mRNA/lncRNA frag.: 2019 EMBO J.** - Phospho‐RNA‐seq: a modified small RNA‐seq method that reveals circulating mRNA and lncRNA fragments as potential biomarkers in human plasma
* **srpRNA domain (RNA7SL1)**: **2019 Clinical Chem.** - Noncoding RNAs serve as diagnosis and prognosis biomarkers for hepatocellular carcinoma

## III. Feature Selection

### III.1.  Signature Genes

* ✅  \[**TmS**: **total mRNA expression**] **2022&#x20;**_**Nature Biotech.**_ - Estimation of tumor cell total mRNA expression in 15 cancer types predicts disease progression
* ✅  _**2021 Nature Biotech.**_ - Gene signature extraction and cell identity recognition at the single-cell level with Cell-ID
* _**2021 Nature Machine Intelligence**_ - Integration of multiomics data with graph convolutional networks to identify new cancer genes and their associated molecular mechanisms
* _**2021 Genome Res.**_ - NS-Forest: A machine learning method for the discovery of minimum marker gene combinations for cell type identification from single-cell RNA sequencing
* _**2019 Briefings in Bioinformatics**_ - A comprehensive evaluation of connectivity methods for L1000 data Briefings in Bioinformatics

### III.2. Network Approach&#x20;

* **2022&#x20;**_**Nature Commn.**_ - Network-based machine learning approach to predict immunotherapy response in cancer patients
* ✅ **\[P-Net]** _**2021 Nature -**_  Biologically informed deep neural network for prostate cancer discovery
* _**2021 Nature Computational Science**_ -  Modeling gene regulatory networks using neural network architectures
* **2021&#x20;**_**Cell**_ - A modular master regulator landscape controls cancer transcriptional identity
* _**2020 Bioinformatics**_ - Varmole: A biologically drop-connect deep neural network model for prioritizing disease risk variants and genes
* **2017&#x20;**_**Nature Methods**_**&#x20;-** SCENIC: single-cell regulatory network inference and clustering
* **2018&#x20;**_**Nature COMMN.**_**&#x20;-** Pathway based subnetworks enable cross-disease biomarker discovery



## IV. Data Clean - normalization, batch correction, etc

> **Issues for single-cell and cell-free RNA-seq data**
>
> * (1) Dropout/Sparseness and Imputation
> * (2) Heterogeneity and Normalization
> * (3) Batch effect and Confounder
> * (Pseudo-time and Others)
>
> [Tutorial](https://lulab1.gitbook.io/training/part-iii.-case-studies/case-study-1.exrna-seq/1.4.normalization-issues)

* ✅  **Review**:  **2021&#x20;**_**Nature Biotech.**_ - Computational principles and challenges in single-cell data integration
* **2019&#x20;**_**Nature Methods**_ - A discriminative learning approach to differential expression analysis for single-cell RNA-seq
* ✅ **2018&#x20;**_**Nature Biotech.**_ - Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors
* **MNN**: **2017&#x20;**_**Nature Biotech.**_ - Batch effects in single-cell RNA-sequencing data are corrected by matching mutual nearest neighbors
* ✅ **Review**: **2017&#x20;**_**Nature Methods**_ - Normalizing single-cell RNA sequencing data: challenges and opportunities

## V. Tissue of Origin

* ✅ [**2024 Cell Genomics -**](https://doi.org/10.1016/j.xgen.2024.100522) Revealing the grammar of small RNA secretion
* ✅ **Deconvolution**: **2022&#x20;**_**Nature Biotech.**_ - Cell types of origin of the cell-free transcriptome
* **2021 Nature Biotech.** - ChIP-seq of plasma cell-free nucleosomes identifies gene expression programs of the cells of origin
* ✅ **miRNA motif -&#x20;**_**2021 Nature**_**&#x20;-** MicroRNA sequence codes for small extracellular vesicle release and cellular retention
* ✅ **2017&#x20;**_**Genome Biology**_ - CancerLocator: non-invasive cancer diagnosis and tissue-of-origin prediction using methylation profiles of cell-free DNA

## VI. Classification Models

### Pre-training and Transfer Learning

* ✅ [**2023 Nature Methods** ](https://www.nature.com/articles/s41592-023-02117-1)- SEVtras delineates small extracellular vesicles at droplet resolution from single-cell transcriptomes
* _**2022 BIB**_ - A universal approach for integrating super large-scale single-cell transcriptomes by exploring gene rankings
* _**2022 bioRxiv**_ - Generative pretraining from large-scale transcriptomes: Implications for single-cell deciphering and clinical translation
* ✅ _**2021 bioRxiv**_ - scBERT: a Large-scale Pretrained Deep Langurage Model for Cell Type Annotation of Single-cell RNA-seq Data

###

