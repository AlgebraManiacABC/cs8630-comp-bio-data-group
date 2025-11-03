# Dataset Details

## Dataset Source
The dataset used in this project is the **Genomics of Drug Sensitivity in Cancer (GDSC)** dataset.  
It can be accessed via Kaggle or the official GDSC website:  
- [Kaggle Link](https://www.kaggle.com/code/samiraalipour/genomics-of-drug-sensitivity-in-cancer)  
- [Official GDSC Database](https://www.cancerrxgene.org/)

## Detailed Column Descriptions

### 1. `GDSC2-dataset.csv`
| Column | Description |
|--------|--------------|
| **DATASET** | Identifier for the specific GDSC dataset version. |
| **NLME_RESULT_ID** | Unique ID for the non-linear mixed effects model result. |
| **NLME_CURVE_ID** | Identifier for the dose–response curve fitted by NLME. |
| **COSMIC_ID** | Unique identifier for the cell line from the COSMIC database. |
| **CELL_LINE_NAME** | Name of the cancer cell line used in the experiment. |
| **SANGER_MODEL_ID** | Identifier used by the Sanger Institute for the cell line model. |
| **TCGA_DESC** | Cancer type description (TCGA classification). |
| **DRUG_ID** | Unique identifier for the drug tested. |
| **DRUG_NAME** | Name of the drug compound. |
| **PUTATIVE_TARGET** | The presumed molecular target of the drug. |
| **PATHWAY_NAME** | The biological pathway affected by the drug. |
| **COMPANY_ID** | Identifier for the company providing the drug. |
| **WEBRELEASE** | Version/date of web release for this data. |
| **MIN_CONC** | Minimum drug concentration used in the experiment. |
| **MAX_CONC** | Maximum drug concentration used. |
| **LN_IC50** | Natural log of the half-maximal inhibitory concentration (IC50). |
| **AUC** | Area Under the Curve – a measure of drug effectiveness. |
| **RMSE** | Root Mean Square Error indicating curve fit quality. |
| **Z_SCORE** | Standardized drug response score for cross-comparison. |

### 2. `Cell_Lines_Details.xlsx`
| Column | Description |
|--------|--------------|
| **Sample Name** | Unique cell line identifier. |
| **COSMIC identifier** | Unique COSMIC database ID. |
| **Whole Exome Sequencing (WES)** | Mutation data from whole exome sequencing. |
| **Copy Number Alterations (CNA)** | Gene copy number variation data. |
| **Gene Expression** | Gene expression levels for the cell line. |
| **Methylation** | DNA methylation pattern data. |
| **Drug Response** | Response of the cell line to tested drugs. |
| **GDSC Tissue descriptor 1/2** | Primary and secondary tissue classifications. |
| **Cancer Type (TCGA label)** | Cancer type classification (TCGA standard). |
| **Microsatellite Instability Status (MSI)** | MSI status of the cell line. |
| **Screen Medium** | Growth medium used for culturing. |
| **Growth Properties** | Characteristics of cell growth in culture. |

### 3. `Compounds-annotation.csv`
| Column | Description |
|--------|--------------|
| **DRUG_ID** | Unique identifier for the drug. |
| **SCREENING_SITE** | Location where screening was performed. |
| **DRUG_NAME** | Drug compound name. |
| **SYNONYMS** | Alternate names for the drug. |
| **TARGET** | Molecular target(s) of the compound. |
| **TARGET_PATHWAY** | Biological pathway(s) affected by the drug. |

