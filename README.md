# Investigating the relationship between GCSE attainment and deprivation in Stockport.
# Project Background 
This project investigates the relationship between GCSE attainment and deprivation in Lower Layer Super Output Areas (LSOAs) in Stockport in 2015. This research is based on 2015 data and 2011 LSOA boundaries. This is because the most recent GCSE attainment and deprivation data from open sources was from 2015 and thus must be noted as a limitation in this research due to the study area having possibly changed over the past decade (Ketchen et al, 2023). However, 2015 was the most recent time that both datasets match and thus this methodological choice was made. In addition, this research is still relevant as it still provides analysis in which Stockport has socio-economic inequalities that should be addressed by policymakers. These socio-economic inequalities may still be present today so this research could also be used as a benchmark when new data is available. 

Life time earnings, employment and economic opportunities are heavily linked to GCSE attainment and thus this research aims to highlight where support may be most needed when increasing GCSE attainment for children in Stockport (Hodge et al, 2021). In addition, understanding whether deprivation has a relationship with GCSE attainment would provide further guidance in how policymakers could increase GCSE attainment. Research has already been done on the impacts of deprivation on GCSE attainment and thus this research is to uncover this pattern for Stockport specifically (Hills et al, 2025). 

# Data 
GCSE_Results.csv - This file contains data on GCSE attainment for Stockport LSOAs across multiple years including the 2015 data used in this analysis.
  - https://datamillnorth.org/dataset/stockport-gcse-results-vdmqm (Data Mill North, 2017)

IMD 2015.csv - This file contains Index of Multiple Deprivation (IMD) data for Stockport LSOAs, including deprivation rank and decile values.
  - IMD data = https://www.gov.uk/government/statistics/english-indices-of-deprivation-2015 (Gov.Uk, 2015)

StockportLSOA.gpkg - This file contains the 2011 LSOA boundary data for Stockport used for spatial visualisation.
  -LSOA boundaries = https://geoportal.statistics.gov.uk/datasets/ons::lower-layer-super-output-areas-december-2011-boundaries-ew-bfc-v3/explore?location=53.391499%2C-2.144144%2C13 (Open Geography Portal, 2023)
  
WorkingAssignment.ipynb - This is the main Jupyter notebook containing the research analysis.

***Note - The StockportLSOA.gpkg file contains the GCSE data linked because all UK files were cut to just Stockport's LSOAs using the GCSE_Results.csv file on QGIS. This is explained in the comments and the unwanted columns are removed during the pre-processing steps of the research. 

# Aims of the code



# References 
Data Mill North. 2017. Stockport GCSE Results. Stockport Metropolitan Borough Council. [Online]. [Accessed: 16/04/2026]. Available from: https://datamillnorth.org/dataset/stockport-gcse-results-vdmqm  

Gov.Uk. File 2: domains of deprivation. Ministry of Housing, Communities & Local Government. [Online]. [Accessed: 16/04/2026]. Available from: https://www.gov.uk/government/statistics/english-indices-of-deprivation-2015  

Hills, S. Walker, M. Guinn, J. Kent, A. 2025. The GCSE attainment gap: Assessing the influence of permenant school exclusion. British Educational Research Journal. [Online]. Vol 51(5): p.1481-1497. [Accessed: 27/04/2026]. Available from: https://doi.org/10.1002/berj.4133 

Hodge, L. Little, A. Weldon, M. 2021. GCSE attainment and lifetime earnings. [Online]. Department for Education. [Accessed: 27/04/2026]. Available from: https://assets.publishing.service.gov.uk/media/60c36f0cd3bf7f4bd11a2326/GCSE_Attainment_and_Lifetime_Earnings_PDF3A.pdf  

Ketchen, D. Roccapriore, A. Connelly, B. Using Old Data: When is it Appropriate?. Journal of Management. [Online]. Vol 49(8). [Accessed: 05/04/2026]. Available from: https://doi.org/10.1177/01492063231177785 

Open Geography Portal. 2023. Lower Layer Super Output Areas (December 2011) Boundaries EW BFC (V3). ONS Geography. [Online]. [Accessed: 16/04/2026]. Available from: https://geoportal.statistics.gov.uk/datasets/ons::lower-layer-super-output-areas-december-2011-boundaries-ew-bfc-v3/explore?location=53.407414%2C-2.173498%2C12  
