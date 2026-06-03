---
layout: project
type: project
image: img/Screenshot 2026-06-02 201123.png
title: "Bubble Pop"
date: 2025
published: true
labels:
  - Visual Studio
  - C/C++
  - SFML
summary: "Game of Bubble Pop like the mobile game"
---

<img class="img/Screenshot 2026-06-02 201123.png">

This was the first time I worked with graphics and didn't have a program that only ran in the terminal. If there are 3 or more bubbles of the same color touching each other and are hit by the same color then they dissapear and the score gets added to the counter. As the game goes on balls are added layer by layer and the game ends when there is no room between the layer and the center where the ball shoots out of.

<div class="text-center">
  <img class="img-fluid" src="../img/Screenshot 2026-06-02 201132.png" alt="Gameplay Screenshot">
</div>

Developing this game taught me the advantages of using C++ rather than C. I used inheritance to make each ball from the parent object so the only thing that was different from each of them was the color property that each one had. It also taught me how to use SFML where I used the borders of the ball images to detect if the ball with the same color has been collided and to use the keyboard as input to control the ball and where you want to shoot it.
