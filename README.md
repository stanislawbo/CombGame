# Creating a Game - Project

This project was originally created as a learning experience to include mathematics, especially combinatorics, in basic web development.  
The goal was to build a small interactive game and understand how to structure a web project with images, scripts, and documentation.

This project was completed as part of a course assignment for one of my classes, allowing me to apply concepts from both mathematics and web development in a practical, interactive way.

<h1>
  <span style="font-size:56px;">How to Play</span> 
  <img src="images/player.png" alt="Player" width="40" height="40">
</h1>

• Set the size of the square ice grid and choose a natural number n for the maximum value of ice blocks.  
• The game is played on a numbered ice grid, where each cell has a number from 1 to n, which was set at the beginning.  
• Take turns moving your penguin and the CPU penguin. There are two game modes:  
• In one mode, stepping on a block decreases the number on it.  
• In the other mode, stepping out of a block decreases the number on it.  
• The winner is the player who avoids stepping on a losing block, which is 0.  
• The game runs entirely in the browser via link — no installation required.

## Features

- Two language options available for the game interface.  
- Special section explaining the game rules in detail.  
- Settings that prevent instant loss for either the player or CPU.
• For example, the game ensures a penguin does not spawn on a block with 1 at the start.
