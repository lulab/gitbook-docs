# RNA Structure

## I. RNA Structure - Experimental Methods 

### 1. Structurome

关于RNA 二级结构高通量测序方法

[PDFs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=/RNA%20Probing%20Experiments&mode=list)

### 2. RiboShape: Ribo-seq+SHAPE

* **2018** _**Cell**_  **\(e. coli, proposed a model\)** _****_- Pervasive regulatory functions of mRNA structure revealed by high-resolution SHAPE probing
* _**2014 NAR**_ **\(proposed a model\)** - Deciphering the rules by which dynamics of mRNA secondary structure affect translation efficiency in Saccharomyces cerevisiae
* **2018** _**Mol. Cell**_ **\(e. coli\)-** A Stress Response that Monitors and Regulates mRNA Structure Is Central to Cold Shock Adaptation
* **2020** _**Genome Biology**_ **\(zebrafish\)** _****_- RNA structural dynamics regulate early embryogenesis through controlling transcriptome fate and function
* _**2017 Nature**_ \(**plant**\)- Global translational reprogramming is a fundamental layer of immune regulation in plants

[PDFs](https://cloud.tsinghua.edu.cn/d/759f79f0a9c24fb7aab4/?p=/Riboshape&mode=list)



## II. RNA Structure - Computational Methods

**Course**: [生物物理学（清华大学）](https://www.ncrnalab.org/courses/#biophysics) 

> * **Book**:   《Biological Sequence Analysis: **Probabilistic Models** of Proteins and Nucleic Acids》by _Richard Durbin, Sean R. Eddy, Anders Krogh, Graeme Mitchison_  \([English](http://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) \| [中文](http://www.amazon.cn/dp/B003ZUIRZ2)\)

### 1.  2nd Structure Prediction

* **Energy Model** 
  * **RNAstructure/Mfold**  and **RNAfold** 
    * How do RNA folding algorithms work? \(Sean R Eddy\) [2004 _Nature Biotech_](https://www.nature.com/articles/nbt1104-1457) 
    * What is dynamic programming? \(Sean R Eddy\) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt0704-909)\_\_
  * **SuperFold** for long distance base pairs \(folding\)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)\_\_

> **RNAstructure**/**Mfold**  and **RNAfold** perform good for sequence less than 200nt.
>
> **SuperFold** uses partition in RNAstructure package to predict partition functions for subsequences of long RNA, then merge the results. Therefore, it claims to perform better on long distance base pairs.

* **SCFG Model** \(Rfam/Infernal\)
  * What is a hidden Markov model? \(Sean R Eddy\) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt1004-1315) 
  * _You can read the SCFG section in the book_ [_above_](../ai/#3-1-rna-secondary-structure-prediction)_. \(Need a short tutorial for SCFG.\)_
* **Deep Learning Method**
  * \*\*\*\*[2020 ICLR](https://openreview.net/forum?id=S1eALyrYDH) - RNA Secondary Structure Prediction By Learning Unrolled Algorithms \([Chinese comments](https://mp.weixin.qq.com/s/SSFOJfljhRZuOOTErNefig)\)
  * \(**Transfer learning**\) 2019 _Nature Commn._ - SPOT-RNA: RNA secondary structure prediction using an ensemble of two-dimensional deep neural networks and transfer learning

[PDFs & PPTs](https://cloud.tsinghua.edu.cn/d/9553a9a553304ff7b311/?p=%2FRNA%20secondary%20structure%20prediction&mode=list)

### 2. Structural Motif Finder

* **SCFG \( Rfam/Infernal** [https://rfam.xfam.org/](https://rfam.xfam.org/) \)
  * **SCFG**: CMfinder - [2006 _Bioinformatics_](https://www.ncbi.nlm.nih.gov/pubmed/16357030) 
  * **SCFG**: RNApromo - [2008 _PNAS_ ](https://www.ncbi.nlm.nih.gov/pubmed/18815376)
  * **CFG:** TEISER - [2012 _Nature_](https://www.ncbi.nlm.nih.gov/pubmed/22495308)  
* **Graph Kernel:** GraphProt - [2014 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/24451197)
* **SHAPE+HMM**:  PATTERNA - [2018 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/29495968)

[PDFs & PPTs](https://cloud.tsinghua.edu.cn/d/9553a9a553304ff7b311/?p=%2FRNA%20Structural%20Motif&mode=list) 

