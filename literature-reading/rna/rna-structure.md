# RNA Structure

## I. Structure Probing

### 1. Structure probing methods

关于RNA 二级结构高通量测序方法

> [PDFs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=%2FStructure%20probing%20method&mode=list)

### 2. Structure probing data analysis

* _**2021 Genome Biology**_ - diffBUM-HMM a robust statistical modeling approach for detecting RNA flexibility changes in high-throughput structure probing data

> [PDFs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=%2FStructure%20probing%20data%20analysis&mode=list)

### 3. RiboShape

* **2018** _**Cell**_  **\(e. coli, proposed a model\)**  Pervasive regulatory functions of mRNA structure revealed by high-resolution SHAPE probing
* _**2014 NAR**_ **\(proposed a model\)** - Deciphering the rules by which dynamics of mRNA secondary structure affect translation efficiency in Saccharomyces cerevisiae
* **2018** _**Mol. Cell**_ **\(e. coli\)-** A Stress Response that Monitors and Regulates mRNA Structure Is Central to Cold Shock Adaptation
* **2020** _**Genome Biology**_ **\(zebrafish\)** RNA structural dynamics regulate early embryogenesis through controlling transcriptome fate and function
* _**2017 Nature**_ \(**plant**\)- Global translational reprogramming is a fundamental layer of immune regulation in plants

#### 2.1 Motif 

* _**2015 Cell**_ - **polyU hairpin** -  EIN2-Directed Translational Regulation of Ethylene Signaling in _Arabidopsis_
* _**2021 PNAS - polyU internal loop**_ - Structural analyses of an RNA stability element interacting with poly\(A\)

> [PDFs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=/Riboshape&mode=list)

## II. Structure Motif Finder

* **SCFG \( Rfam/Infernal** [https://rfam.xfam.org/](https://rfam.xfam.org/) \)
  * **SCFG**: CMfinder - [2006 _Bioinformatics_](https://www.ncbi.nlm.nih.gov/pubmed/16357030) 
  * **SCFG**: RNApromo - [2008 _PNAS_ ](https://www.ncbi.nlm.nih.gov/pubmed/18815376)
  * **CFG:** TEISER - [2012 _Nature_](https://www.ncbi.nlm.nih.gov/pubmed/22495308)  
* **Graph Kernel:** GraphProt - [2014 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/24451197)
* **SHAPE+HMM**:  PATTERNA - [2018 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/29495968)

[PDFs & PPTs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=%2FRNA%20Structural%20Motif&mode=list)

### **1. Motif finding methods**

* _**1994 Proc Int Conf Intell Syst Mol Biol**_ Fitting a mixture model by expectation maximization to discover motifs in biopolymers
* _**2005 NBT**_ Assessing computational tools for the discovery of transcription factor binding sites
* _**2006 Bioinformatics**_ CMfinder: a covariance model based RNA motif finding algorithm
* _**2008 Plos Computational Biology**_ Discovering Sequence Motifs with Arbitrary Insertions and Deletions
* _**2008 PNAS**_ Computational prediction of RNA structural motifs involved in post transcriptional regulatory processes
* _**2012 Nature**_ **TEISER** - Systematic discovery of structural elements governing stability of mammalian messenger RNAs
* _**2014 Nature Method**_ RNA motif discovery by SHAPE and mutational profiling \(SHAPE-MaP\)
* _**2015 Plos Computational Biology**_ Structure-Based Alignment and Consensus Secondary Structures for Three HIV-Related RNA Genomes

### **2. Applications**

* _**2021 Science**_ \[**TEISER**\] - A prometastatic splicing program regulated by SNRPA1 interactions with structured RNA elements



## III. RNA Secondary Structure Prediction

> * **Course**: [生物物理学（清华大学）](https://www.ncrnalab.org/courses/#biophysics)
> * **Book**:   《Biological Sequence Analysis: **Probabilistic Models** of Proteins and Nucleic Acids》by _Richard Durbin, Sean R. Eddy, Anders Krogh, Graeme Mitchison_  \([English](http://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) \| [中文](http://www.amazon.cn/dp/B003ZUIRZ2)\)

* **Energy Model** 
  * **RNAstructure/Mfold**  and **RNAfold** 
    * How do RNA folding algorithms work? \(Sean R Eddy\) [2004 _Nature Biotech_](https://www.nature.com/articles/nbt1104-1457) 
    * What is dynamic programming? \(Sean R Eddy\) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt0704-909)
  * **SuperFold** for long distance base pairs \(folding\)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)

> **RNAstructure**/**Mfold** and **RNAfold** perform good for sequence less than 200nt.
>
> **SuperFold** uses partition in RNAstructure package to predict partition functions for subsequences of long RNA, then merge the results. Therefore, it claims to perform better on long distance base pairs.

* **SCFG Model** \(Rfam/Infernal\)
  * What is a hidden Markov model? \(Sean R Eddy\) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt1004-1315) 
  * _You can read the SCFG section in the book_ [_above_](../ai/#3-1-rna-secondary-structure-prediction)_. \(Need a short tutorial for SCFG.\)_
* **Deep Learning Method** - [see Deep Learning for RNA](../ai/deep-learning-for-rna.md)

[PDFs & PPTs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=%2FRNA%20secondary%20structure%20prediction&mode=list)





