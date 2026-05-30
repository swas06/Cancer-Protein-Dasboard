# Cancer Multi-Omics Protein Structure & Pathway Analysis Dashboard

## Overview

This project aims to analyze multiple cancer types using data from The Cancer Genome Atlas (TCGA) and Genomic Data Commons (GDC). The workflow integrates gene expression analysis, protein structure prediction, pathway analysis, and visualization into a unified cancer research dashboard.

## Team

- Arkayan Pal
- Swastika Dey

## Project Objectives

- Analyze gene expression data from multiple cancer types.
- Identify highly expressed and potentially important cancer-related genes.
- Compare gene expression patterns across cancers.
- Retrieve protein information for significant genes.
- Predict protein structures using modern structure prediction tools.
- Perform pathway enrichment analysis.
- Build an interactive dashboard for visualization and exploration.

---

## Cancer Types Included

| TCGA Code | Cancer Type |
|------------|------------|
| BRCA | Breast Invasive Carcinoma |
| LUAD | Lung Adenocarcinoma |
| LIHC | Liver Hepatocellular Carcinoma |
| COAD | Colon Adenocarcinoma |
| PRAD | Prostate Adenocarcinoma |

Additional TCGA cancer datasets can be added later.

---

## Data Source

Primary dataset:

- :contentReference[oaicite:0]{index=0}
- :contentReference[oaicite:1]{index=1}

Downloaded data:

- Transcriptome Profiling
- Gene Expression Quantification
- RNA-Seq
- STAR Counts

---

## Project Workflow

```text
TCGA Data Download
        ↓
Data Organization
        ↓
Data Cleaning
        ↓
Gene Expression Analysis
        ↓
Top Gene Identification
        ↓
Cross-Cancer Comparison
        ↓
Protein Sequence Retrieval
        ↓
Protein Structure Prediction
        ↓
Pathway Analysis
        ↓
Dashboard Development
