---
description: Finding Structural Motif (dsRNA, RNA-RNA pairs)
---

# RNA Motif & dsRNAfinder

## 0. Overview

* **Short-distance folding**:  RNAstructure; RNAfold (free energy minimization methods) see [_**RNA Secondary Structure Prediction**_](rna-structure.md#i.-rna-secondary-structure-prediction)
* ✅ **Long distance (>200nt) pairing**:   **SuperFold** for long distance base pairs (folding)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)
* **Motif finder:**
  * **CGF:** 2012 _Nature_  - TESISE&#x52;**:** Systematic discovery of structural elements governing stability of mammalian messenger RNAs
  * **HMM+SHAPE**: 2018 _Genome Biology_ - PATTERNA - [2018 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/29495968)PATTERNA: transcriptome-wide  search for functional RNA elements via structural data signatures
  * **Graph Kernel:** GraphProt - [2014 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/24451197)
  * **CFG:** TEISER ([2012 _Nature_](https://www.ncbi.nlm.nih.gov/pubmed/22495308))
  * **SCFG:** [Rfam/Infernal](https://rfam.xfam.org/);  CMfinder ([2006 _Bioinformatics_](https://www.ncbi.nlm.nih.gov/pubmed/16357030)_)_; RNApromo - [2008 _PNAS_ ](https://www.ncbi.nlm.nih.gov/pubmed/18815376)

> - **RNAstructure**/**Mfold** and **RNAfold** perform good for sequence less than 200nt.
> - **SuperFold** uses partition in RNAstructure package to predict partition functions for subsequences of long RNA, then merge the results. Therefore, it claims to perform better on long distance base pairs.

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



