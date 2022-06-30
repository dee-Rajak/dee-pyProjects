# Alien_Invasion
Name : `Dhireen Kumar Rajak`
Date : Thu, 23 Jun 2022 @ 10 : 16 AM
tags : #pyProjects
### Project No. : 1
---
## Intro
In this project, we’ll set up Pygame, and then create a rocket ship that
moves right and left and fires bullets in response to player input. We’ll create a fleet of aliens to destroy, and then continue to refine the game by setting limits on the number of ships you can use and adding a scoreboard.

## What's the plan ?
In Alien Invasion, the player controls a rocket ship that appears at the bottom center of the screen. The player can move the shipright and left using the arrow keys and shoot bullets using the spacebar. When the game begins, a fleet of aliens fills the sky and moves across and down the screen. The player shoots and destroys the aliens. If the player shoots all the aliens, a new fleet appears that moves faster than the previous fleet. If any alien hits the player’s ship or reaches the bottom of the screen, the player loses a ship. If the player loses three ships, the game ends.

***Phase 1***
- We’ll make a ship that can move right and left and fires bullets when the player presses the spacebar.
    - Make sure ship don't go out of edges.
    - Make sure ship fires limited number of bullets
    - Make sure to delete the bullets, which are out of screen. (It consumes Memory.)

***Phase 2***
- We'll make an Alien Ship, and make a fleet out of it, and make it move, bounce off the edge, and drop down after each bounce off.
    - Make sure Alien ship doesn't go off the edges.
    - Make sure to keep space between the ships in the fleet.
    - Fleet must be below half the screen.



---

## Install Pygame
Type the given command in the terminal prompt.
`python -m pip install --user pygame`

![[Pasted image 20220623102554.png]]
