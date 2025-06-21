# 🩺Healthcare Data ETL and Analysis Pipeline

![Healthcare Data Analysis](https://images.unsplash.com/photo-1576091160550-2173dba999ef?ixlib=rb-4.0.3&auto=format&fit=crop&w=1200&q=80)

## Overview
This project demonstrates a comprehensive ETL (Extract, Transform, Load) pipeline and data analysis workflow using real-world healthcare datasets. The project consists of two main components:

1. **Healthcare Data Cleaning & ETL**: Cleaning and validation of corrupted notifiable disease datasets from Nova Scotia's Open Data Portal
2. **COVID-19 Data Analysis**: Advanced analysis of global COVID-19 data including dimensionality reduction, distribution fitting, and correlation analysis

The project showcases essential data engineering and analysis skills including data validation, missing value imputation, consistency checking, dimensionality reduction, and statistical analysis.

## Features
- **Data Cleaning Pipeline**:
  - Duplicate detection and removal
  - Missing value imputation
  - Range error correction
  - Cross-dataset consistency validation
  - Automated data quality checks
  
- **Advanced Analysis**:
  - Principal Component Analysis (PCA) for dimensionality reduction
  - Distribution fitting using Fitter library
  - Entropy calculation for disease distribution
  - Correlation analysis of key health metrics
  
- **Visualization**:
  - Interactive disease trend visualizations
  - PCA component analysis
  - Distribution comparison plots

## Datasets
1. **Nova Scotia Notifiable Diseases Data (Corrupted Versions)**:
   - [Notifiable Diseases Counts and Rates By Zone 2014-2017](https://data.novascotia.ca/Health-and-Wellness/Notifiable-Diseases-Counts-and-Rates-By-Zone-2014-/36ek-n7n8)
   - [Notifiable Diseases Counts and Rates By Sex 2014-2017](https://data.novascotia.ca/Health-and-Wellness/Notifiable-Diseases-Counts-and-Rates-By-Sex-2014-2/hgpa-vixp)

2. **Our World in Data COVID-19 Dataset**:
   - [OWID COVID-19 Data](https://github.com/owid/covid-19-data/tree/master/public/data)

## Technical Skills Demonstrated
- **Data Engineering**: ETL pipeline development, data validation, data cleaning
- **Data Analysis**: Statistical analysis, dimensionality reduction, distribution fitting
- **Programming**: Python, Pandas, NumPy, Scikit-learn, SciPy
- **Visualization**: Matplotlib, Seaborn
- **Data Modeling**: PCA, KNN imputation, correlation analysis

##✅ Key Findings
#Healthcare Data ETL
Identified and resolved 3,000+ data quality issues across datasets
Implemented automated validation checks for data consistency
Visualized disease trends across demographic dimensions
COVID-19 Analysis
Reduced dataset dimensionality by 85% while preserving 95% of variance
Identified lognormal distribution as best fit for COVID-19 cases
Discovered strong correlation (r = 0.87) between vaccination rates and case reduction

##Dependencies
Python 3.8+
pandas
numpy
matplotlib
seaborn
scikit-learn
scipy
fitter

##✅Future Enhancements
Implement real-time data validation pipeline
Develop interactive dashboard for health metrics monitoring
Add machine learning models for disease outbreak prediction
Incorporate geospatial analysis of disease spread

##check few project visuals below: 

<img width="532" alt="image" src="https://github.com/user-attachments/assets/8679717a-9c5d-406b-910d-a2d50713ab9a" />
<img width="335" alt="image" src="https://github.com/user-attachments/assets/85e89239-041f-48fe-bf62-384bff60fb03" />
<img width="409" alt="image" src="https://github.com/user-attachments/assets/d6a39e1f-48f3-4c9d-a54c-80b5f385c90b" />



