# Time series analysis of the literature with fatty liver disase  
This repository contains R code for time series analysis of publication counts in fatty liver disease.  

## Data
The original records downloaded from PubMed was not included in the repository due to potential copyright infringement.     
They can be downloaded with the query described in the Supplementary data of the paper.  
Due to the large number of records, it is necessary to download records into smaller batches.  

## Environment
Under the root folder, create the following folders.  
```data/pubmed```: contains all downloaded PubMed files  
```save/pubmed```: store PubMed files converted into RDS    
```save/rds```: store RDS necesssary for data analysis  
```R markdown```: contains R markdown files for data analysis (working directory)  
```figure```: plots will be created  

## R markdown
```01_pubmed_import```: imports each PubMed files into RDS  
```02_pubmed_convert```: convert RDS into a dataframe  
```03_pubmed_cleaning```: data preprocessing and assignment of PubMed index date  
```04_pubmed_selection```: literature selection for eligible records  
```05_time_series_overall```: time series analysis of overall counts of publications containing each term  
```06_time_series_individual```: time series analysis of publication counts in NAFLD/MAFLD/MASLD category  
```07_flow_chart```: draw flow chart for literature selection  
