---
layout: posts
title: "LegalTextGenerator"
date: 2024-09-18 19:27:22 +0000
categories: 
  - work
tags:
  - Machine Learning
highlight_home: false
body_class: legaltextgenerator-page
header:
  teaser: /assets/images/legal.png
  caption: ""
---
> TensorFlow, NLP, Deep Learning

[Github repository](https://github.com/snehaajoshii/LegalTextGenerator)

# Inspiration
This project was built to explore how machine learning models can generate structured, human-like legal text. The goal was to understand how character-level language models learn patterns in complex formal writing.

# What it does
The Legal Text Generator trains a neural network to produce legal-style text based on learned patterns from training data.

- **Text Generation:** Produces legal-style sentences character by character  
- **Custom Dataset:** Trained on legal PDF documents  
- **Neural Network Model:** Built using TensorFlow  
- **Preprocessing Pipeline:** Cleans and prepares text for training  

# How it was built
The project is modular and split into several components:

- `data/` → Contains legal PDF documents used for training  
- `data_loader.py` → Loads and preprocesses raw text  
- `model.py` → Defines and builds the TensorFlow model  
- `utils.py` → Helper functions for sampling and text generation  
- `main.py` → Main training and generation script  
- `checkpoints/` → Stores saved model checkpoints during training  

# How It Works
1. Legal documents are loaded from the `data/` folder  
2. Text is cleaned and converted into sequences  
3. A character-level TensorFlow model is trained on the dataset  
4. The model predicts the next character in a sequence  
5. Generated text is produced using learned patterns  

# Challenges
- Cleaning and preprocessing raw PDF text  
- Training a model on limited and specialized data  
- Balancing randomness and structure in generated output  

# Accomplishments
- Built a working character-level language model  
- Successfully generated legal-style text  
- Learned how sequence models process text data  

# What I learned
- Fundamentals of NLP and sequence modeling  
- How TensorFlow models are structured and trained  
- Importance of preprocessing in machine learning pipelines  


