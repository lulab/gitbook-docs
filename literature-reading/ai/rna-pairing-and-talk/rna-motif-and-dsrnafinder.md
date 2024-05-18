---
description: Finding Structural Motif (dsRNA, RNA-RNA pairs)
---

# RNA Motif & dsRNAfinder

## 0. Overview

* **Short-distance folding**:  RNAstructure; RNAfold (free energy minimization methods) see [_**RNA Secondary Structure Prediction**_](rna-structure.md#i.-rna-secondary-structure-prediction)
* ✅ **Long distance (>200nt) pairing**:   **SuperFold** for long distance base pairs (folding)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)
* **Motif finder:**
  * **CGF:** 2012 _Nature_  - TESISER**:** Systematic discovery of structural elements governing stability of mammalian messenger RNAs
  * **HMM+SHAPE**: 2018 _Genome Biology_ - PATTERNA - [2018 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/29495968)PATTERNA: transcriptome-wide  search for functional RNA elements via structural data signatures
  * **Graph Kernel:** GraphProt - [2014 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/24451197)
  * **CFG:** TEISER ([2012 _Nature_](https://www.ncbi.nlm.nih.gov/pubmed/22495308))
  * **SCFG:** [Rfam/Infernal](https://rfam.xfam.org/);  CMfinder ([2006 _Bioinformatics_](https://www.ncbi.nlm.nih.gov/pubmed/16357030)_)_; RNApromo - [2008 _PNAS_ ](https://www.ncbi.nlm.nih.gov/pubmed/18815376)

> * **RNAstructure**/**Mfold** and **RNAfold** perform good for sequence less than 200nt.
> * **SuperFold** uses partition in RNAstructure package to predict partition functions for subsequences of long RNA, then merge the results. Therefore, it claims to perform better on long distance base pairs.

## **I. Motif finding methods**

* _**1994 Proc Int Conf Intell Syst Mol Biol**_ Fitting a mixture model by expectation maximization to discover motifs in biopolymers
* _**2005 NBT**_ Assessing computational tools for the discovery of transcription factor binding sites
* _**2006 Bioinformatics**_ CMfinder: a covariance model based RNA motif finding algorithm
* _**2008 Plos Computational Biology**_ Discovering Sequence Motifs with Arbitrary Insertions and Deletions
* _**2008 PNAS**_ Computational prediction of RNA structural motifs involved in post transcriptional regulatory processes
* _**2014 Nature Method**_ RNA motif discovery by SHAPE and mutational profiling (SHAPE-MaP)
* _**2015 Plos Computational Biology**_ Structure-Based Alignment and Consensus Secondary Structures for Three HIV-Related RNA Genomes



### I.1 dsRNAfinder

* **2023 BioRxiv** - dsRID: Editing-free in silico identification of dsRNA region using long-read RNA-seq data
* ✅ **Long distance (>200nt) pairing**:   **SuperFold** for long distance base pairs (folding)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)

## **II. RNA motif in human**

* _**2021 Science**_ \[**TEISER**] - A prometastatic splicing program regulated by SNRPA1 interactions with structured RNA elements

## III. sRNA in microbiome

* ✅[ ](https://www.sciencedirect.com/science/article/pii/S0092867422015823?via%3Dihub)[**2024 Science**](https://www.science.org/doi/10.1126/science.adh4859) - Hydrolytic endonucleolytic ribozyme (HYER) is programmable for sequence-specific DNA cleavage
* **2023 **_**Science**_ - Uncovering the functional diversity of rare CRISPR-Cas systems with deep terascale clustering
* ✅[ **2023 **_**Cell**_](https://www.sciencedirect.com/science/article/pii/S0092867422015823?via%3Dihub) - Mining metatranscriptomes reveals a vast world of viroid-like circular RNAs
* _**2021 Genome Biology**_ - Comparative genomics identifies thousands of candidate structured RNAs in human microbiomes
* ✅ [_**2019 Cell**_ ](https://www.sciencedirect.com/science/article/pii/S0092867419307810)- Large-Scale Analyses of Human Microbiomes Reveal Thousands of Small, Novel Genes
* **2017 **_**Science**_ - Protein structure determination using metagenome sequence data
* _**2019 Molecular Systems Biology**_ - Unraveling the hidden universe of small proteins in bacterial genomes
* _**2009 Nature**_ - Metatranscriptomics reveals unique microbial small RNAs in the ocean’s water column. Nature

