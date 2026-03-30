---
layout: posts
title: "Layoffs Data Analysis"
date: 2023-12-09 10:00:00 +0000
categories:
  - work
tags:
  - Data Science
highlight_home: false
body_class: -page
header:
  teaser: /assets/images/layoff.png
  caption: ""
---
> Python, Pandas, Matplotlib, Plotly

[Github repository](https://github.com/snehaajoshii/LayoffsVisual/tree/main)

# Inspiration
This project was created to explore global tech layoffs from 2020 to 2023 and understand how economic shifts impacted companies and employees across different countries and regions.

The goal was to turn raw dataset information into clear, visual insights.

# What it does
This project performs exploratory data analysis and visualization on global layoffs data.

- Calculates total layoffs by year  
- Identifies countries most affected by layoffs  
- Analyzes layoffs distribution within the United States  
- Uses interactive and static visualizations to present insights  

# How it was built
- **Language:** Python  
- **Data Handling:** CSV module + basic preprocessing  
- **Visualization:** Matplotlib and Plotly Express  
- **Notebook:** Jupyter Notebook (`DataViz.ipynb`)  

Key steps:
- Loaded and cleaned dataset  
- Extracted year from date column  
- Aggregated layoffs by year and country  
- Created line chart and pie chart visualizations  

# How It Works
1. The dataset is loaded from `Layoffs Dataset.csv`  
2. Rows are parsed using Python’s CSV reader  
3. Year is extracted from the date column  
4. Layoffs are aggregated using dictionaries  
5. Visualizations are created:
   - Line chart → total layoffs over time  
   - Pie chart → top US locations by layoffs  

# Key Insights
- The United States had the highest number of recorded layoffs  
- India, Canada, and the UK followed behind  
- Layoffs peaked unevenly across 2020–2023  
- Certain US cities contributed significantly to total layoffs  

# Challenges
- Handling missing or inconsistent dataset values  
- Parsing dates and converting them into usable formats  
- Aggregating large datasets efficiently using Python  
- Choosing clear visual representations for complex data  

# Accomplishments
- Built complete end-to-end data analysis workflow  
- Created meaningful visualizations from raw data  
- Extracted insights from a real-world dataset  
- Combined static and interactive charts effectively  

# What I learned
- Data cleaning and preprocessing techniques  
- Working with real-world messy datasets  
- Creating visual storytelling with Python  
- Using Plotly for interactive visualizations  
