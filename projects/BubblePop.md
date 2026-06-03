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

<img src="../img/Screenshot 2026-06-02 201123.png" height="225px" width="225px" class="rounded-start">

This was the first time I worked with graphics and didn't have a program that only ran in the terminal. If there are 3 or more bubbles of the same color touching each other and are hit by the same color of ball then they dissapear then the score is added to the total. The project goal was to create a game that used graphics, and I it taught me how to connect objects in code to graphics and what the user sees on the front end.

<div class="text-center">
  <img class="img-fluid" src="../img/Screenshot 2026-06-02 201132.png" alt="Gameplay Screenshot">
</div>

Developing this game taught me the advantages of using C++ rather than C. I used inheritance to make each ball from the parent object so the only thing that was different from each of them was the color of the ball. This project also taught me how to use graphics and to use the images that we created for each object from the arrow, to the ball helped me realize that in video games almost everything you see is an individual object and there is just rules of how they interact with each other. For example, I was able to use the keyboard to control the ball and where to shoot it when it was connected to the starting point but when it left and touched another ball it needed to check if it is connected to another ball that is of the same color.
