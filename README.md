# Gender Wage Gap in Armenia
## Statistical Analysis Project

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## Project Overview
We have heard a lot that in Armenia, women are paid less than men for
the same work despite having the same education, skills, and experience. This
is not only unfair to women as individuals, but it is a type of discrimination
that significantly harms Armenia’s economy. But does this gap really exist? If
so, what factors affect this? The purpose of this research is to identify if this
problem really exists in Armenia, measure how big this wage gap is and identify
what drives this inequality. The data is taken from the LFS in Armenia, which
is officially accepted by the government. More about the data collection and
consistency is provided in the next section.



## Installation & Usage
### Setup
1. Clone repository
2. Install required packages:  
      install.packages(c("tidyverse", "readxl", "ggplot2", "sf", "broom", "knitr", "dplyr"))
## Run Analysis
Execute in order:
- data_cleaning.Rmd → Generates cleaned_data.xlsx
- data_filtering.Rmd → Produces:  
    - Tables for statistical analysis
    - Visualizations (HTML reports)
