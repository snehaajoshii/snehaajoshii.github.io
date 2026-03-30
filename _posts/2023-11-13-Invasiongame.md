---
layout: posts
title: "Invasion Game"
date: 2023-11-13 12:00:00 +0000
categories: 
  - work
tagline: ""
tags:
  - Game Development
highlight_home: false
body_class: invasiongame-page
header:
  teaser: /assets/images/game.png
  caption: ""
---
> Python, Pygame, Object-Oriented Programming

[GitHub Repo](https://github.com/snehaajoshii/Invasion-Game/tree/main)


# Inspiration
This project was inspired by classic arcade-style space shooter games. The goal was to build a fully playable 2D game using Python and Pygame while applying object-oriented programming principles.

# What it does
The Alien Invasion game is a space shooter where the player controls a rocket and fights waves of aliens.

- **Player Controls:** Move rocket left and right and shoot bullets  
- **Enemy System:** Aliens move in fleets and change direction at edges  
- **Collision Detection:** Bullets destroy aliens on impact  
- **Scoring System:** Tracks player progress  
- **Lives System:** Player has limited lives before game over  

# How it was built
The game is built using modular Python files:

- `alien_invasion.py` → Main game loop and event handling  
- `rocket.py` → Player-controlled spaceship  
- `alien.py` → Enemy behavior and movement  
- `bullet.py` → Projectile mechanics  
- `game_stats.py` → Score, lives, and game state  
- `settings.py` → Game configuration values  

# How It Works
1. The game initializes the screen and settings using Pygame  
2. The player controls a rocket using keyboard input  
3. Bullets are fired to destroy incoming aliens  
4. Alien fleets move across the screen and descend  
5. The game tracks score and remaining lives  
6. Game ends when lives reach zero  

# Challenges
- Managing multiple moving objects simultaneously  
- Handling collision detection between bullets and aliens  
- Structuring the game using proper OOP design  
- Debugging movement and sprite behavior  

# Accomplishments
- Built a fully playable 2D game from scratch  
- Learned real-world object-oriented programming  
- Implemented game loops, physics, and collision logic  
- Improved understanding of modular code design  

# What I learned
- How game loops work in real-time applications  
- Object-oriented programming in Python  
- Sprite management using Pygame  
- How to structure medium-sized software projects  

