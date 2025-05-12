# Gender Wage Gap in Armenia
## Statistical Analysis Project

![R](https://img.shields.io/badge/R-276DC3?style=for-the-badge&logo=r&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)


## How to Use This Repository
**Step 1**: Understand the Data Collection
Methodology: instructions.pdf

Survey questionnaire: LFS Questionarie.pdf

**Step 2**: Get the Raw Data
Download: data.xlsx

**Step 3**: Data Cleaning Process
Cleaning steps: data_cleaning.nb.html

Cleaned output: cleaned_data.xlsx

**Step 4**: Data Analysis & Visualization
Main analysis script: data_filtering.Rmd

Run results: data_filtering.nb.html

Required for maps: armenia.json

**Step 5**: Hypothesis Testing & Results
Tests performed: Hypothesis Tests List.pdf

**Final report**: Report.pdf (contains full analysis and conclusions)


| **File**                      | **Purpose**                              |
|--------------------------------|------------------------------------------|
| `data.xlsx`                   | Raw dataset (original, immutable)        |
| `cleaned_data.xlsx`           | Cleaned data (output from cleaning)      |
| `data_cleaning.nb.html`       | Data cleaning documentation              |
| `data_filtering.Rmd`          | Main analysis script (R Markdown)        |
| `data_filtering.nb.html`      | Pre-run analysis output (HTML)           |
| `armenia.json`                | Map data for visualizations              |
| `Hypothesis Tests List.pdf`   | List of statistical tests                |
| `Report.pdf`                  | Final report (results & conclusions)     |

## Project Overview
We have heard a lot that in Armenia, women are paid less than men for
the same work despite having the same education, skills, and experience. This
is not only unfair to women as individuals, but it is a type of discrimination
that significantly harms Armenia’s economy. But does this gap really exist? If
so, what factors affect this? The purpose of this research is to identify if this
problem really exists in Armenia, measure how big this wage gap is and identify
what drives this inequality. The data is taken from the LFS in Armenia, which
is officially accepted by the government. 



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
