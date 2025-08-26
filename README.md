# AllergoOncology-MultiOmics

This repository hosts the processed multi-omics datasets and supporting files used in the bachelor thesis:   
**“Cross-Cancer Profiling of an Allergy-Linked Immune Signature Using Publicly Available Multi-Omics and Prognostic Data.”**

---

## Repository Contents

This repository contains four preprocessed and filtered datasets that were used in the integrative analysis:

### 1. `data/proteomics_allergy_filtered.csv`
Differential expression of allergy-associated proteins across 11 cancer types.  
- Source: Clinical Proteomic Tumor Analysis Consortium (CPTAC) via Human Protein Atlas (HPA).  
- Contains protein-level log2 fold-changes (tumor vs. matched normal).  

### 2. `data/scRNAseq_cell_types_allergy.csv`
Single-cell expression profiles of allergy-associated genes across four innate immune cell populations:  
Monocytes, Macrophages, Kupffer cells, and Microglial cells.  
- Source: Human Protein Atlas single-cell dataset (healthy tissues).  
- Includes dominant cell-type assignments after filtering.  

### 3. `data/cancer_prognosis_allergy.csv`
Prognostic associations of allergy-associated genes across 20 tumor types.  
- Source: The Cancer Genome Atlas (TCGA) via Human Protein Atlas.  
- Genes classified as favorable or unfavorable based on patient survival (Kaplan–Meier, log-rank *p* < 0.001).  

### 4. `data/dbDEMC_miRNA_allergy.csv`
Cancer-associated miRNAs overlapping with the curated allergy signature.  
- Source: database of Differentially Expressed miRNAs in human Cancers (dbDEMC).  
- Contains validated tumor vs. normal differential expression.  

---

## Citation

If you use this repository, please cite the associated thesis and underlying resources:

**Dogan, S. (2025).** *Cross-Cancer Profiling of an Allergy-Linked Immune Signature Using Publicly Available Multi-Omics and Prognostic Data.* Bachelor Thesis, Heinrich Heine University Düsseldorf & University Hospital of Cologne.  

---

## Data Sources

- **TCGA (The Cancer Genome Atlas):** [Tomczak et al., 2015](https://doi.org/10.1038/nrg3911)  
- **CPTAC (Clinical Proteomic Tumor Analysis Consortium):** [Edwards et al., 2015](https://doi.org/10.1038/nmeth.3257)  
- **HPA (Human Protein Atlas):** [Uhlén et al., 2015](https://doi.org/10.1126/science.1260419)  
- **dbDEMC (Database of Differentially Expressed miRNAs in human Cancers):** [Xu et al., 2022](https://doi.org/10.1093/nar/gkab1079)  
- **Allergy scoping review (EAACI Task Force):** DOI: [10.22541/au.174178285.56398310/v1](https://doi.org/10.22541/au.174178285.56398310/v1) 

---

## Contact

For questions, requests, or collaboration inquiries:  
📧 Dr. Rocio Rebollido-Rios -> rocio.rebollido-rios@uni-koeln.de  
📧 Sezin Dogan -> dgnsezin@gmail.com
