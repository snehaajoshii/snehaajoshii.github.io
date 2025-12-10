---
layout: posts
title: "SentiShelter"
date: 2023-10-22 12:00:00 +0000
categories: 
  - work
tagline: "Climate Change and Housing Sentiment Analysis"
tags:
  - Data Science
description: Analyze Reddit discussions on climate change and housing.
highlight_home: true
header:

teaser: https://blenwbegashaw.github.io/sentishelter/assets/logo-removebg.png
caption: SentiShelter
---

I collaborated with 3 people for this project. As a group, we combined our skills in data science, NLP, web development, and visualization to explore how climate change discussions affect housing sentiment.

[Live Website](https://blenwbegashaw.github.io/sentishelter/)  
[Chatbot](https://huggingface.co/spaces/blenbegashaw/sentishelter-chatbots/)
[Github Repo](https://github.com/BlenWBegashaw/sentishelter)

# Inspiration
We created SentiShelter to help people understand how climate change conversations influence the housing market. From rising insurance rates to homes becoming less sustainable, we wanted to provide a tool that visualizes sentiment trends and highlights key topics and locations.

# What it does
SentiShelter analyzes Reddit comments from 2010-2022, tracking sentiment over time related to climate change and housing. Key features include:

- **Sentiment Analysis:** Identify positive, negative, or neutral sentiment in discussions about climate and housing.
- **Topic Clusters:** Extract major topics and trends from discussions.
- **Interactive Website:** Users can explore data visualizations and access a chatbot to learn more about the dataset.
- **Data Visualization:** Bar charts, line graphs, and scatter plots show sentiment trends over time.

## Final Product

<video width="800" height="450" controls poster="/BlenWBegashaw.github.io/assets/logo-removebg.png">
  <source src="/assets/New%20Recording%20-%2012_9_2025,%2010_09_35%20PM.mp4" type="video/mp4">
</video>


# How we built it
- **Data Source:** Kaggle Reddit Climate Change Dataset (2010-2022)  
- **Processing:** Python, SpaCy NLP for cleaning and extracting entities like people and locations  
- **Visualization:** Matplotlib and Seaborn for sentiment trends, topic clusters, and frequency charts  
- **Website:** Responsive HTML/CSS/JS site with integrated Hugging Face chatbot  

### Sample Kaggle Data Science Work

- **Average Sentiment Analaysis per month**  
  ![Top Entities](/assets/images/kaggle2.png)

- **Cleaning the Dataset** 
  ![Topic Clusters](/assets/images/kaggle4.png)

# Challenges we ran into
- **Large Dataset:** Required sampling to maintain performance without losing insights  
- **Entity Analysis:** Identifying meaningful relationships between people, locations, and sentiment was complex  
- **Visualization:** Presenting data clearly while maintaining an interactive user experience  

# Accomplishments that we are proud of
- Successfully combined **NLP, data visualization, and web development**  
- Developed a **user-friendly website** with clear insights  
- Integrated a **chatbot interface** for exploring climate change and housing discussions  

# What we learned
- How to extract insights from large datasets using NLP  
- How to visualize and present complex sentiment data interactively  
- How to combine Python analysis with a responsive website  

# What is next for SentiShelter
- Add **more real-time sentiment tracking** as new data becomes available  
- Expand chatbot capabilities to provide more detailed explanations of trends and insights  
- Enhance topic clustering and sentiment analysis using advanced NLP models  

# Key Features
- Explore Reddit sentiment trends (2010-2022)  
- Identify top entities (persons, locations) and their associated sentiment  
- Interactive visualizations and data exploration  
- Hugging Face chatbot integration for learning about climate and housing  



