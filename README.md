# af_dem
Code for the publication: 
[Kauko, A., et al., Increased risk of dementia differs across cardiovascular diseases and types of dementia - Data from a nationwide study, J. Intern. Med. (2023), Online ahead of print.]()

 We analysed the association between various cardiovascular diseases and the incidence of dementia using FinnGen data.

* Data: FinnGen https://www.finngen.fi/en
* Description of variables: https://risteys.finngen.fi/
* Description of registries: https://finngen.gitbook.io/finngen-analyst-handbook/finngen-data-specifics/finnish-health-registers-and-medical-coding
* Data access: https://site.fingenious.fi/en/

```
ht_prs_preg
├── README.md                       # Overview
├── af_dem3.Rmd                     # R markdown code for the main analysis
├── af_dem3_080523.html             # html documentation for the main analysis
├── af_dem3_age.Rmd                 # Age stratified analysis
├── af_dem3_age_080523.html
├── af_dem3_sex.Rmd                 # Sex stratified analysis
├── af_dem3_sex_080523.html
├── af_dem3_ycutoff.Rmd             # Analysis with one year lag time
├── af_dem3_ycutoff_150823.html          
├── scripts
  ├── functions.R                   # Minor R functions for the analysis
├── data
  ├── variables.txt                 # List of variables that are preselected from the FinnGen phenotype file

```
