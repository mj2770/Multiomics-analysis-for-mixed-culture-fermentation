# Multiomics Analysis Pipeline for Mixed-Culture Fermentation
---
* Author: Minxi Jiang
* Version: 2.0
* Date: lastly updated on 6/9/2024
---

## Overview
This repository contains a comprehensive multiomics analysis pipeline tailored for mixed-culture fermentation studies. The pipeline encompasses the analysis of 16S rRNA gene, metagenomics, and metatranscriptomics data. It outputs community-level alpha diversity (Shannon diversity and evenness), beta-diversity (Bray-Curtis matrix), and PCoA plots of samples. Additionally, it includes RDA analysis for assessing the environmental impact on community structure. 

---
![Multiomics analysis pipeline](https://github.com/mj2770/Multiomics-analysis-for-mixed-culture-fermentation/blob/main/Analysis_pipeline_v1-02.png)


## Key Features
- **16S rRNA Analysis**: Community-level alpha and beta diversity, PCoA plots.
- **Metagenomics Analysis**:
  - **Read-based classification**: Dominant genus identification and functional potential.
  - **Optional assembly-based method**.
- **Metatranscriptomics Analysis**:
  - **Global functional analysis**: Using eggNOG functional categories.
  - **Acidification pathway analysis**: Custom curated database for acidification metabolic pathways.
- **Integration**:
  - **RefSeq annotation**: Tracking enzyme function contribution and potential origin.
  - **Genus-level pathway tracking**: Analysis of acidification-related pathways.
  - **Cross-feeding analysis**: Flux-balance based metabolic model to propose and validate inter-genus interactions.

## Publications
This pipeline has been applied in the following two studies:
1. [Paper Title 1](https://www.sciencedirect.com/science/article/pii/S0960852423014979?via%3Dihub)
2. [Paper Title 2](10.1101/2023.05.23.541846)



