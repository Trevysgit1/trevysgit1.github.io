---
layout: project
type: project
image: img/connectfour.png
title: "Connect Four"
date: 2024
published: true
labels:
  - Visual Studio
summary: "Simple game of Connect Four that I made for an assignment"
---

<img class="img/connectfour.png">

This was one of the first times I fully built a program and game. Although there it is simple you are still able to play the game like you would in person but on a program. There isn't any graphics or animations for the chips, instead I used the letters R and Y for the chips each player uses. 

<div class="text-center">
  <img class="img-fluid" src="../img/Connect4ex.png" alt="Connect 4 screenshot">
</div>

I just used a 2D array to make the board to play on then to get the "gravity" part of the chips to work I checked if they were out of bounds of the 2D array or if there was a chip below them to not move down and if there was a spot below them that didnt have any value I would move the chip down until it was out of bounds. Checked if the player has made a winning move by traversing in each possible direction to check if there are four of the same chip in a row for a player to win.
