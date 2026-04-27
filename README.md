# Investigating the relationship between GCSE attainment and deprivation in Stockport.
# Project Background 
This project investigates the relationship between GCSE attainment and deprivation in Lower Layer Super Output Areas (LSOAs) in Stockport in 2015. This research is based on 2015 data and 2011 LSOA boundaries. This is because the most recent GCSE attainment and deprivation data from open sources was from 2015 and thus must be noted as a limitation in this research due to the study area having possibly changed over the past decade (Ketchen et al, 2023). However, 2015 was the most recent time that both datasets match and thus this methodological choice was made. In addition, this research is still relevant as it still provides analysis in which Stockport has socio-economic inequalities that should be addressed by policymakers. These socio-economic inequalities may still be present today so this research could also be used as a benchmark when new data is available. 

Life time earnings, employment and economic opportunities are heavily linked to GCSE attainment and thus this research aims to highlight where support may be most needed when increasing GCSE attainment for children in Stockport (Hodge et al, 2021). In addition, understanding whether deprivation has a relationship with GCSE attainment would provide further guidance in how policymakers could increase GCSE attainment. Research has already been done on the impacts of deprivation on GCSE attainment and thus this research is to uncover this pattern for Stockport specifically (Hills et al, 2025). 

# Data 
GCSE_Results.csv - This file contains data on GCSE attainment across multiple years including 2015 for Stockport LSOAs.

IMD 2015.csv - This file contains the Index of Multiple Deprivation (IMD) rank and deciles in which different LSOAs in Stockport fall into. 

StockportLSOA.gpkg - This file contains coordinates and data on all the 2011 LSOAs in Stockport needed for spatial visualisation.  

WorkingAssignment.ipynb - This is the main Jupyter notebook containing the research analysis.

***Note - The StockportLSOA.gpkg file contains the GCSE data linked because all UK files were cut to just Sotckport's LSOAs using the GCSE_Results.csv file on QGIS. This is explained in the comments and the unwanted columns are removed during the pre-processing steps of the research. 

# Aims of the code



# References 
Hills, S. Walker, M. Guinn, J. Kent, A. 2025. The GCSE attainment gap: Assessing the influence of permenant school exclusion. British Educational Research Journal. [Online]. Vol 51(5): p.1481-1497. [Accessed: 27/04/2026]. Available from: https://doi.org/10.1002/berj.4133 

Hodge, L. Little, A. Weldon, M. 2021. GCSE attainment and lifetime earnings. [Online]. Department for Education. [Accessed: 27/04/2026]. Available from: https://assets.publishing.service.gov.uk/media/60c36f0cd3bf7f4bd11a2326/GCSE_Attainment_and_Lifetime_Earnings_PDF3A.pdf  

Ketchen, D. Roccapriore, A. Connelly, B. Using Old Data: When is it Appropriate?. Journal of Management. [Online]. Vol 49(8). [Accessed: 05/04/2026]. Available from: https://doi.org/10.1177/01492063231177785 
