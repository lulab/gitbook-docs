# RNA Structure Prediction

> * [**PDFs**](../ai/)
> * ✅ : Recommended

## 0. RNA Secondary Structure Prediction

> ✅ **Course**: [生物信息学（清华大学）](https://www.ncrnalab.org/courses/#bioinfo);  [生物物理学（清华大学）](https://www.ncrnalab.org/courses/#biophysics);
>
> **Book**:   《Biological Sequence Analysis: **Probabilistic Models** of Proteins and Nucleic Acids》by _Richard Durbin, Sean R. Eddy, Anders Krogh, Graeme Mitchison_  ([English](http://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) | [中文](http://www.amazon.cn/dp/B003ZUIRZ2))

> * **Energy Model** - **RNAstructure/Mfold**  and **RNAfold**&#x20;
>   * ✅ How do RNA folding algorithms work? (Sean R Eddy) [2004 _Nature Biotech_](https://www.nature.com/articles/nbt1104-1457)&#x20;
>   * What is dynamic programming? (Sean R Eddy) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt0704-909)
> * **SCFG Model** (Rfam/Infernal)
>   * ✅ What is a hidden Markov model? (Sean R Eddy) [2004 _Nature Biotech_](http://dx.doi.org/10.1038/nbt1004-1315)&#x20;
>   * _You can read the SCFG section in the book_ _above (_《Biological Sequence Analysis》_)._&#x20;
> * **Deep Learning Method** - [see Deep Learning for RNA](../ai/deep-learning-for-rna.md)



* ✅ \[review] **2023 BIB** - Recent trends in RNA informatics: a review of machine learning and deep learning for RNA secondary structure prediction and RNA drug discovery
* \[review] **2022 PNAS** - Thoughts on how to think (and talk) about RNA structure

## II. RNA Tertiary Structure Prediction

> Learn from Protein structure prediction:
>
> * 2017 Science - Protein structure determination using metagenome sequence data&#x20;
> * ✅ 2021 Nature – AlphaFold2: Highly accurate protein structure prediction with AlphaFold

* ✅ [**2021 Science**](https://www.science.org/doi/10.1126/science.abe5650) - **ARES:** Geometric deep learning of RNA structure
* 2022 bioRxiv - Accurate de novo prediction of RNA 3D structure with transformer network
* [**2022 bioRxiv**](https://www.biorxiv.org/content/10.1101/2022.05.15.491755v1) - **DeepFoldRNA**: De Novo RNA Tertiary Structure Prediction at Atomic Resolution using Geometric Potentials from Deep Learning
* [**2022 arxiv**](https://arxiv.org/abs/2207.01586) - **E2Efold-3D**: End-to-End Deep Learning Method for accurate de novo RNA 3D Structure Prediction
* [**2022 bioRxiv**](https://www.biorxiv.org/content/10.1101/2022.09.09.507333v1) - Accurate prediction of nucleic acid and protein-nucleic acid complexes using **RoseTTAFoldNA**

## III. Structure Motif Finder

* **Short-distance folding**:  RNAstructure; RNAfold (free energy minimization methods)
* ✅ **Long distance (>200nt) pairing**:   **SuperFold** for long distance base pairs (folding)  [2014 _Nature Methods_](https://www.ncbi.nlm.nih.gov/pubmed/25028896)
* **Motif finder:**
  * **SCFG:** [Rfam/Infernal](https://rfam.xfam.org/);  CMfinder ([2006 _Bioinformatics_](https://www.ncbi.nlm.nih.gov/pubmed/16357030)_)_; RNApromo - [2008 _PNAS_ ](https://www.ncbi.nlm.nih.gov/pubmed/18815376)
  * ✅ **CFG:** TEISER ([2012 _Nature_](https://www.ncbi.nlm.nih.gov/pubmed/22495308))
  * **Graph Kernel:** GraphProt - [2014 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/24451197)
  * **SHAPE+HMM**:  PATTERNA - [2018 _Genome Biology_ ](https://www.ncbi.nlm.nih.gov/pubmed/29495968)PATTERNA: transcriptome-wide  search for functional RNA elements via structural data signatures

> * **RNAstructure**/**Mfold** and **RNAfold** perform good for sequence less than 200nt.
> * **SuperFold** uses partition in RNAstructure package to predict partition functions for subsequences of long RNA, then merge the results. Therefore, it claims to perform better on long distance base pairs.

### **1. Motif finding methods**

* _**1994 Proc Int Conf Intell Syst Mol Biol**_ Fitting a mixture model by expectation maximization to discover motifs in biopolymers
* _**2005 NBT**_ Assessing computational tools for the discovery of transcription factor binding sites
* _**2006 Bioinformatics**_ CMfinder: a covariance model based RNA motif finding algorithm
* _**2008 Plos Computational Biology**_ Discovering Sequence Motifs with Arbitrary Insertions and Deletions
* _**2008 PNAS**_ Computational prediction of RNA structural motifs involved in post transcriptional regulatory processes
* _**2014 Nature Method**_ RNA motif discovery by SHAPE and mutational profiling (SHAPE-MaP)
* _**2015 Plos Computational Biology**_ Structure-Based Alignment and Consensus Secondary Structures for Three HIV-Related RNA Genomes

### **2. Applications**

* _**2021 Science**_ \[**TEISER**] - A prometastatic splicing program regulated by SNRPA1 interactions with structured RNA elements



## IV. Structure Probing

### 1. Structure probing methods

关于RNA 二级结构高通量测序方法 (see more in **PDFs**)

### 2. Structure probing data analysis

* [**2022 Nature Methods**](https://www.nature.com/articles/s41592-022-01605-0) - RNA secondary structure packages evaluated and improved by high-throughput experiments
* _**2021 Genome Biology**_ - diffBUM-HMM a robust statistical modeling approach for detecting RNA flexibility changes in high-throughput structure probing data

