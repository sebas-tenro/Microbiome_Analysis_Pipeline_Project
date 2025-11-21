# Analysis of Gut Microbiome Changes in INSTI-Treated People Living with HIV
### UBC MICB 475 — Computational Microbiology Project

This repository contains the full analysis pipeline used to investigate how Integrase Strand Transfer Inhibitor (INSTI) treatment affects the gut microbiome composition 
of people living with HIV. The project combines microbiome bioinformatics, statistical analysis, functional pathway prediction, and machine learning.
This work resulted in a peer-reviewed publication in the Undergraduate Journal of Experimental Microbiology & Immunology (UJEMI+), 2025.

## 🔬 Project Overview
Our team analyzed publicly available 16S rRNA sequencing data (Taylor et al., 2020) to identify microbial and functional differences between INSTI-treated and non-INSTI-
treated individuals.
Using tools such as QIIME2, phyloseq, DESeq2, PICRUSt2, and random forest models, we explored how INSTIs modulate microbial composition, diversity, and predicted 
metabolic pathways.
This repository includes all scripts, data processing steps, figures, and documentation used to generate the results for our published study.

## 🧪 Methods & Tools Used
- Bioinformatics & Analysis
  - QIIME2
  - Phyloseq (alpha & beta diversity)
  - DESeq2 (differential abundance)
  - Indicator species & core microbiome analysis
  - PICRUSt2 functional pathway prediction
  - Machine learning (KNN, Random Forest) using R and tidymodels
  - ggplot2 for data visualization

- Programming
  - R
  - RStudio
  - UNIX
  - tidyverse

## 👤 My Contributions
As part of this team project, I contributed to both the computational analysis and the published manuscript. My key contributions include:
- Preprocessing metadata and constructing phyloseq objects
- Performing alpha and beta diversity analyses
- Running DESeq2 for differential abundance
- Implementing Random Forest classification to detect microbial patterns
- Generating several figures used in the final manuscript
- Co-writing sections of the Methods and Results
- Maintaining project organization and documentation0
  
## 📄 Publication
Tenorio Romero, S.*, Sobczak, E.*, Drotsky, J., Huang, E., Wiebe, E. (2025).
Higher Clostridia Expression Is Associated with Integrase Strand Transfer Inhibitor Treatment in People Living with HIV.
Undergraduate Journal of Experimental Microbiology and Immunology (UJEMI+), 11, 1–13.
(*co-first authors)
PDF of the publication is included here:
[TenorioRomero_et_al_2025.pdf](https://ojs.library.ubc.ca/index.php/UJEMI/article/view/200793)

## 🧭 How to Run the Analysis
1. Install required tools and R packages
2. Download metadata and sequencing files (links provided in metadata/)
3. Run preprocessing through QIIME2
4. Open RStudio and execute scripts in the following order:
   - 1_diversity.R
   - 2_differential_abundance.R
   - 3_functional_pathways.R
   - 4_machine_learning.R
5. Figures are saved automatically in the figures/ folder.

Full instructions are found inside each analysis folder.
