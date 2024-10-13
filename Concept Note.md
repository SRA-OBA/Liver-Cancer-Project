**Discovery of Therapeutic Biomarkers and their Potential Inhibitors for Liver Cancer Therapy Using Bioinformatics Approaches**

 

**Project Proposal by Team CancerCodes Crackers**

 

**Introduction**

The proposed research aims to identify therapeutic biomarkers from liver cancer samples in Black or African American populations using data from The Cancer Genome Atlas (TCGA). This study will employ differential expression analysis and gene functional enrichment analysis through R Studio, followed by the identification of potential inhibitors or activators derived from phytocompounds, specifically from _Calotropis procera_ (alternatively, from existing drugs using FDA-approved drug repurposing appraoch). The project will also involve molecular docking, ADMET profiling, (and possibly molecular dynamics simulations).

 

**Objectives**

<!--[if !supportLists]-->·       <!--[endif]-->Identify therapeutic biomarkers in liver cancer samples using TCGA data.

<!--[if !supportLists]-->·       <!--[endif]-->Perform differential expression analysis to identify upregulated and downregulated genes.

<!--[if !supportLists]-->·       <!--[endif]-->Conduct gene functional enrichment analysis to understand the biological pathways involved.

<!--[if !supportLists]-->·       <!--[endif]-->Identify potential phytocompounds that can act as inhibitors or activators of the identified genes.

<!--[if !supportLists]-->·       <!--[endif]-->Perform molecular docking studies to evaluate the interaction between phytocompounds and target proteins.

<!--[if !supportLists]-->·       <!--[endif]-->Conduct ADMET profiling of the top 10 compounds based on docking results.

<!--[if !supportLists]-->·       <!--[endif]-->Run molecular dynamics simulations to assess the stability and activity of the protein-ligand complexes.

 

**Materials and Methods**

 

**Data Collection**

<!--[if !supportLists]-->·       <!--[endif]-->Source: TCGA liver cancer dataset (LIHC).

<!--[if !supportLists]-->·       <!--[endif]-->Population: Focus on Live cancer samples generally  

** **

**Differential Expression Analysis**

<!--[if !supportLists]-->·       <!--[endif]-->Tool: R Studio with packages such as \`DESeq2\` or \`edgeR\`.

<!--[if !supportLists]-->·       <!--[endif]-->Process:

<!--[if !supportLists]-->i.                 <!--[endif]-->Normalize data.

<!--[if !supportLists]-->ii.               <!--[endif]-->Identify differentially expressed genes (DEGs) with a significance threshold (e.g., FDR < 0.05).

 

**Gene Functional Enrichment Analysis**

Tool: R packages like \`clusterProfiler\` or \`GOstats\`.

Process:

<!--[if !supportLists]-->i.                 <!--[endif]-->Analyze DEGs for enrichment in biological pathways using Gene Ontology (GO) and KEGG databases.

 

**Identification of Phytocompounds**

Source: Literature review for reported compounds from _Calotropis procera_.

Analysis: Use databases like IMPPAT, Dr. Duke and/or PubChem to gather information on bioactive compounds.

 

**Molecular Docking**

Software: AutoDock Vina or similar tools.

Process:

<!--[if !supportLists]-->i.                 <!--[endif]-->Prepare protein structures from PDB files.

<!--[if !supportLists]-->ii.               <!--[endif]-->Dock phytocompounds against target proteins derived from DEGs.

 

**ADMET Profiling**

Software: Use online tools like SwissADME or ADMETlab.

Process:

Evaluate the pharmacokinetic properties of the top 10 compounds based on docking scores.

 

**Molecular Dynamics Simulation (Possible technique addition)**

Software: GROMACS or AMBER.

Process:

Set up simulations for the best protein-ligand complexes in a physiological environment.

 Analyze stability through root mean square deviation (RMSD) and root mean square fluctuation (RMSF).

 

**Timeline**

|                                                                                  |                                                                                            |                |
| -------------------------------------------------------------------------------- | ------------------------------------------------------------------------------------------ | -------------- |
|  **Phase**                                                                       |  **Expected Outcome**                                                                      |  **Duration**  |
|  <!--[if !supportLists]-->1.     <!--[endif]-->Data Collection                   |  Gather TCGA liver cancer samples.                                                         |  Week 1        |
|  <!--[if !supportLists]-->2.     <!--[endif]-->Differential Expression Analysis  |  Identify upregulated and downregulated genes using R Studio.                              |  Week 1        |
|  <!--[if !supportLists]-->3.     <!--[endif]-->Functional Enrichment Analysis    |  Determine biological pathways associated with identified DEGs.                            |  Week 2        |
|  <!--[if !supportLists]-->4.     <!--[endif]-->Phytocompound Identification      |  Compile a list of potential phytocompounds from Calotropis procera.                       |  Week 2        |
|  <!--[if !supportLists]-->5.     <!--[endif]-->Molecular Docking                 |  Evaluate binding interactions between phytocompounds and target proteins.                 |  Week 3        |
|  <!--[if !supportLists]-->6.     <!--[endif]-->ADMET Profiling                   |  Assess the pharmacokinetic properties of the top 10 compounds from docking results.       |  Week 3        |
|  <!--[if !supportLists]-->7.     <!--[endif]-->Molecular Dynamics Simulation     |  Simulate protein-ligand interactions in a physiological environment to assess stability.  |  Week 4        |
|  <!--[if !supportLists]-->8.     <!--[endif]-->Data Analysis & Reporting         |  Compile findings, analyze results, and prepare a final report or presentation.            |  Week 4        |

 

**Suggested Control Drugs**

1\. Sorafenib

2\. Lenvatinib

3\. Regorafenib

 

These drugs are commonly used in hepatocellular carcinoma treatment and can serve as benchmarks for evaluating the efficacy of identified phytocompounds.

 

**Novelty and Worth Exploring**

This project concept is novel as it focuses specifically on therapeutic biomarkers in liver cancer within a racial context, addressing disparities in cancer treatment outcomes. The integration of phytocompound screening adds a unique dimension to traditional therapeutic approaches, potentially leading to innovative treatment options tailored for underrepresented populations.

 

**Conclusion**

The outlined project aims to leverage existing genomic data while incorporating novel methodologies to explore therapeutic avenues in liver cancer patients. By combining computational biology with traditional pharmacology, this research has the potential to contribute significantly to personalized medicine and health equity in oncology.

 

**References**

\[1] https\://www\.ncbi.nlm.nih.gov/pmc/articles/PMC10216530/

\[2] https\://www\.biorxiv.org/content/10.1101/2023.02.21.529336v1.full.pdf

\[3] https\://www\.nature.com/articles/s41467-023-39055-7

\[4] https\://www\.ncbi.nlm.nih.gov/pmc/articles/PMC10162392/

\[5] https\://karger.com/lic/article/10/6/593/828602/Associations-of-Serum-Tumor-Biomarkers-with

\[6] https\://www\.mdpi.com/2227-9059/11/7/1852

\[7] https\://www\.sciencedirect.com/science/article/pii/S2405844023064411

\[8] https\://www\.biorxiv.org/content/10.1101/2023.02.21.529336v1.full
