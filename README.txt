# Space Shooter Game - README
## Overview
This is a space shooter game developed in Unreal Engine where the player controls a ship at the bottom of the screen. The objective is to shoot down enemy ships before they either collide with the player or reach the bottom of the screen. The game features a wave-based enemy system, various enemy types with unique behaviors, collectable power-ups, and a boss battle.
Development Context
This game was created as a university assignment for SIT151 Game Fundamentals. The base assets, resources, and core game mechanics were provided by the university. Much of the foundational game was developed following tutorials and instructions from tutors.
## Features Added Independently
The following features were developed independently without tutorial assistance:
### 1. New Enemy Types

Fast Ship: Moves quicker than standard enemies and follows a zig-zag pattern while descending. Has less health than normal ships.
Homing Ship: Remains at the top of the screen and fires homing missiles at the player that track horizontally.
Boss Ship: A larger, more durable variant of the homing ship that appears in the final wave.

### 2. Power-Up System
Three power-ups have been implemented that can be collected and stored for later use:

Invincibility: Makes the player immune to damage for 5 seconds
Faster Movement: Increases the player's movement speed for 5 seconds
Faster Bullets: Increases the player's bullet speed for 5 seconds

Power-ups spawn randomly in the play area during waves and can be activated with the R key. The current power-up is displayed with an icon in the bottom left corner.
### 3. Enemy Wave System
The game features a progressive wave system:

Waves only advance when all required enemies are defeated
Each wave has unique enemy spawn patterns and behaviors
A countdown appears between waves
The HUD displays the number of enemies remaining

### 4. Victory Condition

The game ends with a victory when the player defeats the boss in the final wave
Upon victory, all enemy ships are destroyed and no new enemies spawn

## Controls

Move: (Arrow keys or WASD)
Shoot: (Space)
Use Power-up: R

## Credits
This project uses resources from:

Alan Guyant's Millionth Vector sprites
Kenney Group's sprites
Mark Simpson's Prinz Eugn Sprites
Wouter Visser's Explosion Generator Sprites

## Technical Implementation
The game was built in Unreal Engine using Blueprint visual scripting. Key systems include:

Enemy behavior controllers
Projectile collision detection
Power-up inventory system
Wave management system
HUD with power-up indicators and enemy counters

## Student Information

Created by Thomas Fleming
Student Number: 221391076
Assignment 4 for SIT151
