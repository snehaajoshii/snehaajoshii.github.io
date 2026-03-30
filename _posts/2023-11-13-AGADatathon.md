---
layout: posts
title: "Graduation Rates & Federal Funding Analysis"
date: 2023-11-13 12:00:00 +0000
categories:
  - work
tagline: ""
tags:
  - Data Science
highlight_home: false
body_class: datathon-page
header:
  teaser: /assets/images/aga.png
  caption: ""
---
> Python, Pandas, NumPy, SciPy, Statsmodels, Scikit-learn, Matplotlib, Seaborn, Google Sheets

[Github Repo](https://github.com/snehaajoshii/AGA-Datathon)

# Inspiration
We were interested in understanding how education outcomes in the United States are influenced by broader socioeconomic and innovation-related factors. Specifically, we wanted to investigate whether federal funding, unemployment, and scientific innovation (such as patents) had any measurable impact on graduation rates across different states and racial groups from 2000–2020.

# What it does
This project analyzes the relationship between graduation rates and key economic and demographic indicators:

- **Regression Analysis:** Explores how unemployment, patents, and R&D funding affect graduation rates.
- **Multilinear Modeling:** Evaluates the combined effect of multiple variables on graduation outcomes.
- **Demographic Analysis:** Breaks down results by racial groups across U.S. states.
- **Correlation Study:** Identifies relationships between federal R&D funding, patents, GDP, and workforce size.
- **Data Visualization:** Uses heatmaps, scatter plots, and bar charts to illustrate trends.

# How I built it
- **Data Sources:** BLS labor data, NSF innovation indicators, National Student Clearinghouse graduation data, and KFF demographic datasets.
- **Data Cleaning:** Preprocessed datasets using Google Sheets and Python (Pandas) to standardize and merge multi-source data.
- **Statistical Modeling:** Built regression and multilinear regression models using Python (SciPy, Statsmodels).
- **Visualization:** Created graphs and heatmaps using Matplotlib, Seaborn, and Google Sheets.
- **Exploratory Analysis:** Conducted correlation analysis and subgroup (race-based) modeling.

# Challenges I ran into
- Data integration from multiple inconsistent sources  
- Handling outliers (e.g., West Virginia)  
- Low R² values in regression models  
- Multicollinearity between federal funding, patents, and workforce variables  

# Accomplishments that I am proud of
- Built multiple regression models across 20 years of national data  
- Identified statistically significant relationships between key variables  
- Developed race-based models showing differences in predictive strength  
- Created comprehensive visualizations including heatmaps and stacked charts  

# What I learned
- How to implement and interpret linear and multilinear regression in Python  
- Limitations of statistical modeling in real-world policy datasets  
- How demographic segmentation changes model interpretation  
- How correlated socioeconomic indicators can distort regression results  

# What is next for this project
- Improve prediction using machine learning models beyond regression  
- Add additional variables (education funding, policy differences)  
- Build an interactive dashboard (Streamlit or Flask)  
- Extend dataset beyond 2020 to include post-COVID trends
