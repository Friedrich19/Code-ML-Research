# Radiomics-Driven Classification of Clear Cell Renal Cell Carcinoma Using Meta-Learning From Medical Imaging

## 1. Project Description

This repository contains the implementation code for the radiomics-based classification framework proposed in the study entitled:

"Radiomics-Driven Classification of Clear Cell Renal Cell Carcinoma Using Meta-Learning From Medical Imaging"

The project includes radiomics feature extraction, feature selection, and stacking ensemble classification for clear cell renal cell carcinoma (ccRCC) using CT and MR imaging data.

---

## 2. Dataset Information

### TCGA-KIRC Dataset
Image data were obtained from The Cancer Imaging Archive (TCIA):

TCGA-KIRC Collection  
[https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR](https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR)

The dataset contains CT and MR images of clear cell renal cell carcinoma cases from The Cancer Genome Atlas (TCGA) project.

### Clinical / Metadata Information
Clinical metadata and phenotype information were obtained from the GDC TCGA-KIRC phenotype repository:

[https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net](https://xenabrowser.net/datapages/?dataset=TCGA-KIRC.clinical.tsv&host=https%3A%2F%2Fgdc.xenahubs.net)

---

## 3. Code Description

| File Name                     | Description                                                         |
|-------------------------------|---------------------------------------------------------------------|
| feature_extraction.ipynb      | Radiomics preprocessing, feature extraction, and feature selection  |
| model_classification.ipynb    | Machine learning model training and evaluation                      |

---

## 4. Usage Instructions

1. *Load Datasets:*  
   for feature extraction
     Image -> [https://www.kaggle.com/datasets/friedrich19/nifti-renal-cancer-clear-cell](https://www.kaggle.com/datasets/friedrich19/nifti-renal-cancer-clear-cell)
     Metadata -> [https://www.kaggle.com/datasets/friedrich19/metadata](https://www.kaggle.com/datasets/friedrich19/metadata)

2. *Feature Extraction:*  
   Use feature_extraction.ipynb and use Image and Metadata to extract radiomics feature and perform feature selection.

3. *Model Classification:*  
   Use model_classification.ipynb use the output file from step 2 (Feature Extraction) to start the model classification.

---

## 5. Requirements

The implementation was developed using Python 3.11.

PyRadiomics was installed directly from the official GitHub repository:
[https://github.com/AIM-Harvard/pyradiomics](https://github.com/AIM-Harvard/pyradiomics)

Required libraries include:

- numpy
- pandas
- scipy
- scikit-learn
- matplotlib
- seaborn
- SimpleITK
- nibabel
- git+https://github.com/AIM-Harvard/pyradiomics.git
- pymrmr
- deap
- openpyxl
- tqdm
- scikeras
- tensorflow
- xgboost

Install dependencies using:

pip install -r requirements.txt

---

## 6. Citation

If you use this repository or dataset, please cite the associated manuscript and the following dataset references:

### TCGA-KIRC Dataset
Akin O, et al.
TCGA-KIRC Collection, The Cancer Imaging Archive (TCIA).
[https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR](https://doi.org/10.7937/K9/TCIA.2016.V6PBVTDR)

### PyRadiomics
van Griethuysen JJM, et al.  
Computational Radiomics System to Decode the Radiographic Phenotype.  
Cancer Research. 2017.  
[https://doi.org/10.1158/0008-5472.CAN-17-0339](https://doi.org/10.1158/0008-5472.CAN-17-0339)

---

## 7. License

This repository is intended for academic and research purposes only.

---

## 8. Code Repository and DOI

Zenodo DOI:
[https://doi.org/10.5281/zenodo.20079714](https://doi.org/10.5281/zenodo.20079714)

GitHub Repository:
[https://github.com/Friedrich19/Code-ML-Research](https://github.com/Friedrich19/Code-ML-Research)
