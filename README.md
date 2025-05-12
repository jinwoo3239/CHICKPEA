# *Integrative Analysis of Microbial and Metabolic Responses to Chickpea Treatment*

## About

This repository contains the code and data corresponding to the paper *(current revision, May 2025)*:  
*Integrative Analysis of Microbial and Metabolic Responses to Chickpea Treatment*

All datasets and related code used in the analysis are shared here for transparency and reproducibility.

**Authors:**  
Jinwoo Kim¹²†, Jiwoon Kim¹†, and Hakdong Shin¹²\*

¹ Department of Food Science and Biotechnology, College of Life Science, Sejong University, Seoul 05006, South Korea  
² Carbohydrate Bioproduct Research Center, Sejong University, Seoul 05006, South Korea  

† These authors contributed equally to this work.  
\* Correspondence: [hshin@sejong.ac.kr](mailto:hshin@sejong.ac.kr)

## Prerequisites

- Python ≥ 3.7  
- numpy  
- pandas  
- matplotlib  
- seaborn  
- scipy  
- statsmodels  
- scikit-learn

## Folder Structure

### `1_Microbiome_Raw_data_preprocessing_Qiime`  
Contains sequence files, QIIME 2 output files, and preprocessing scripts used for microbiome analysis.  
This includes raw data processing, quality filtering, and generation of feature tables.

### `2_Microbiome_analysis`  
Includes exported data from QIIME 2 and subsequent analyses performed using [MicrobiomeAnalyst](https://www.microbiomeanalyst.ca/).  
This folder also contains code for generating microbiome-related figures based on the analysis results.

### `3_Metabolomics_analysis`  
Includes preprocessing scripts and analysis code for LC-MS metabolomics data.  
This folder contains processed data and figure generation scripts used in the study.


## License

The code and datasets in this repository are provided for personal and academic reference only.  
For more information, see the [LICENSE](LICENSE) file.
