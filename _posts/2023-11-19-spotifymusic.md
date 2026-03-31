---
layout: posts
title: "Spotify Tune Suggest"
date: 2023-11-19 19:27:22 +0000
categories:
  - work
tags:
  - Machine Learning
highlight_home: false
body_class: eduowl-page
header:
  teaser: /assets/images/spotify.png
  caption: ""
---
> Python, Spotify API, Pandas, Content-Based Filtering, Recommendation Systems

[Github repository](https://github.com/snehaajoshii/music-recommendation-spotify)

# Inspiration
I built this project out of curiosity about how music recommendation systems work in platforms like Spotify. I wanted to understand how audio features and listening behavior can be used to suggest new songs that match a user’s taste.

# What it does
This project is a music recommendation system built using Spotify data:

- **Playlist Data Extraction:** Fetches songs and metadata from Spotify playlists  
- **Content-Based Filtering:** Recommends songs based on similarity of audio features (danceability, energy, etc.)  
- **Hybrid Recommendations:** Combines similarity scoring with popularity and recency weighting 
- **Audio Feature Analysis:** Uses Spotify’s track features to compare songs  

# How I built it
- **Spotify API:** Used to retrieve playlist and track data  
- **Authentication:** Implemented OAuth using client credentials  
- **Data Processing:** Cleaned and structured data using Pandas  
- **Recommendation Engine:** Built content-based and hybrid filtering logic  
- **Project Structure:**
  - `main.py` → entry point for testing recommendations  
  - `client_credentials.py` → handles Spotify authentication  
  - `get_playlist_data.py` → fetches playlist data  
  - `recommendations.py` → recommendation algorithms  

# Challenges I ran into
- Handling Spotify API authentication and token refresh  
- Cleaning inconsistent audio feature data  
- Balancing similarity vs popularity in recommendations  
- Choosing meaningful features for comparison  

# Accomplishments that I am proud of
- Built a working recommendation system using real Spotify data  
- Implemented both content-based and hybrid recommendation methods  
- Structured the project into clean, reusable Python modules  
- Successfully integrated Spotify API authentication  

# What I learned
- How recommendation systems work in real-world applications  
- How to use Spotify’s API and audio feature data  
- Feature engineering for similarity-based models  
- Designing simple hybrid ranking systems  

# What is next for this project
- Build a Streamlit web app for interactive recommendations  
- Improve ranking using embeddings or deep learning models  
- Add user-based collaborative filtering  
- Deploy as a live music recommendation tool  
