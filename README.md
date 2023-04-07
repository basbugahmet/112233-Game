# 11-22-33: One-Player Number Matching Game

## Overview


**Poster**

![poster](https://raw.githubusercontent.com/basbugahmet/112233-Game/main/poster.jpg?token=GHSAT0AAAAAACBDJH4DSP6LT4IGYXIQF2ESZBPN6GA)

This project is a one-player number matching game, where the player aims to get the highest score by matching the same numbers side by side. The game is played on a 3x30 board, initially filled with 30 random numbers (1, 2, and 3). The player moves a cursor with the arrow keys on the keyboard and moves numbers under the cursor with the WASD keys. The game rules allow moving single numbers only, and if two identical numbers come together on the same line, they get deleted from the board, and the player's score increases by 10 points. New two random numbers are generated and placed randomly on the board.

## Game Rules

1.  The game is played on a 3x30 board.

2.  In the beginning, the board is randomly filled with 30 numbers which can be 1, 2, or 3.

3.  The arrow keys on the keyboard are used to move the cursor, and WASD keys are used to move the number under the cursor.

4.  WASD keys can move only the single numbers (the left and right side of the number should be empty):
    -   W: Moves the number one square up.
    -   S: Moves the number one square down.
    -   A: Moves the number to the left as much as it can go.
    -   D: Moves the number to the right as much as it can go.

5.  If two identical numbers come together on the same line (by player moves or randomly):
    -   Matching numbers are deleted from the board.
    -   The player's score increases by 10 points.
    -   New two random numbers are generated and randomly placed on the board.

6.  The game continues until there are no moves left (i.e., all numbers are matched).
    
7.  The player can restart the game at any time by pressing the "R" key on the keyboard.
    
8.  The player's highest score should be stored in a file, and the program should display it at the start of each new game.

## Sample Screens

Here are some sample screens from the game with different scores:

**Main Menu**

![mainMenu](https://raw.githubusercontent.com/basbugahmet/112233-Game/main/SampleScreenshots/mainMenu.jpg?token=GHSAT0AAAAAACBDJH4DDBGT37NCSL7UDAEMZBPOD6Q)







**In-Game**

![inGame](https://raw.githubusercontent.com/basbugahmet/112233-Game/main/SampleScreenshots/inGame.jpg?token=GHSAT0AAAAAACBDJH4D6LXI5R4J2Y6BILRMZBPODCQ)


## Installation and Usage

To run the game, you can follow these steps:

1.  Clone or download the project from GitHub.
2.  Open the project folder in your preferred `C#` IDE or code editor.
3.  Run the `Program.cs` file to start the game.
4.  Use arrow keys to move the cursor and WASD keys to move the number under the cursor.
5. Earn points and Enjoy :)


## Contributions
Thanks  for  contributing  to  our  project! The  following  people  have  contributed  to  this  project: 


- Kübra Özalp
- Eylem Etleç
