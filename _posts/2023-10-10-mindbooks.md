---
layout: posts
title:  "MindBooks Database System"
date:   2023-10-10 12:00:00 +0000
categories: 
  - work
tagline: "Database"
tags:
  - Datascience
description: Relational Database for Bookstore Management
highlight_home: false
header:
 overlay_image: https://images.unsplash.com/photo-1512820790803-83ca734da794?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=1080
 teaser: https://images.unsplash.com/photo-1524995997946-a1c2e315a42f?crop=entropy&cs=tinysrgb&fit=max&fm=jpg&q=80&w=400
 caption: Database Project
---
> SQL,Database Design,ER Diagram

[GitHub repository](https://github.com/snehaajoshii/DatabaseRepo)


# Inspiration
The MindBooks Database System was designed to help a small bookstore efficiently manage customer orders, track bestselling books, and analyze purchasing trends. The goal was to create a structured system that improves both business operations and customer experience.

# What it does
This project is a relational database that organizes and connects key parts of a bookstore system:

- **Customers:** Stores basic information and purchase history  
- **Orders:** Tracks each purchase and shipping details  
- **Order Items:** Connects orders to specific books and quantities  
- **Books:** Maintains the store’s inventory  
- **Authors:** Stores author information and links them to books  

With this structure, the system can answer questions like:
- Which books are selling the most?
- Who are the most frequent customers?
- Which authors are most popular?

# How it was built
- Designed an **ER diagram** to map relationships between entities  
- Converted the design into a **relational schema**  
- Implemented everything using SQL  

### How It Works

1. A customer places an order, which is stored in the **Orders** table  
2. Each order contains multiple books stored in **Order Items**  
3. Book details come from the **Books** table  
4. Authors are stored separately and linked to books  
5. SQL queries are used to retrieve insights and analyze data  


# Challenges
- Structuring relationships correctly between multiple tables  
- Avoiding redundant data through normalization  
- Writing queries that accurately join multiple tables 

# Accomplishments
- Built a fully functional relational database from scratch  
- Successfully connected multiple entities using foreign keys  
- Created queries to generate useful business insights

# What I learned
- How to design and implement normalized database systems  
- Writing efficient SQL queries using joins and conditions  
- Thinking about data from both a technical and business perspective  
