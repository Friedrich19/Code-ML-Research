# Code-ML-Research

## 1. Title

*Project Name:* Radiomics-Driven Classification of Clear Cell Renal Cell Carcinoma Using Meta-Learning From Medical Imaging  
*Image data:* TCIA -> TCGA-KIRC -> https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR  
*Phenotype data:* GDC TCGA-KIRC Phenotype  

---

## 2. Code / Dataset Description

This project consists of five different scripts to handle race-based grouping, Differentially Expressed Gene (DEG) analysis, ROC analysis, and the development of machine learning models for different racial groups (White and Black). The datasets include gene expression and phenotype data for prostate cancer diagnosis.

---

## 3. Dataset Information

- *Image Dataset:*  
  Contains image data from clear cell renal cell carcinoma.  
  [Link](https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR)

- *Phenotype Dataset:*  
  Contains clinical information about the patients.
  [Link](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net&removeHub=https%3A%2F%2Fxena.treehouse.gi.ucsc.edu%3A443)

---

## 4. Code Description

| File Name              | Description |
|------------------------|-------------|
| feature_extraction.ipynb      | Radiomics feature extraction and feature selection    |
| model_classification.ipynb    | Performs model classification with csv radiomics data |

---

## 5. Usage Instructions

1. *Load Datasets:*  
   for feature extraction
     Image -> [https://www.kaggle.com/datasets/friedrich19/nifti-renal-cancer-clear-cell](https://www.kaggle.com/datasets/friedrich19/nifti-renal-cancer-clear-cell)
     Metadata -> [https://www.kaggle.com/datasets/friedrich19/metadata](https://www.kaggle.com/datasets/friedrich19/metadata)

2. *Feature Extraction:*  
   Use feature_extraction.ipynb and use Image and Metadata to extract radiomics feature and perform feature selection.

3. *Model Classification:*  
   Use model_classification.ipynb use the output file from step 2 (Feature Extraction) to start the model classification.

---

## 6. Citation
Not applicable.

## 7. License & Contribution Guidelines
Not applicable.

## 8. Code Repository or DOI

[![DOI]
