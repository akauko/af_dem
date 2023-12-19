# af_dem
Code for the project: 
[Kauko, A., et al., Increased risk of dementia differs across cardiovascular diseases and types of dementia - Data from a nationwide study, J. Intern. Med. (2023), Online ahead of print.]()

Miller, E.C., et al., Risk of Midlife Stroke After Adverse Pregnancy Outcomes: The FinnGen Study, Stroke (2023), Online ahead of print.](https://doi.org/10.1111/joim.13733)

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
├── af_dem3_age.Rmd                 # R markdown code for the age stratified analysis
├── af_dem3_age_080523.html         # html documentation for the age stratified analysis
├── af_dem3_sex.Rmd                 # R markdown code for the sex stratified analysis
├── af_dem3_sex_080523.html         # html documentation for the sex stratified analysis
├── scripts
  ├── functions.R                   # Minor R functions for the analysis
├── data
  ├── variables.txt                 # List of variables that are preselected from the FinnGen phenotype file

```
