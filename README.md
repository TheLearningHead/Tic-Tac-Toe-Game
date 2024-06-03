# Tic-Tac-Toe Game

This repository contains a simple implementation of the Tic-Tac-Toe game in Python. The game allows you to play against an unbeatable AI player.

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Python 3 installed on your local machine.
- Git installed on your local machine (optional, for cloning the repository).

## How to Play

### Game Rules:
- The game is played on a 3x3 grid.
- Players take turns placing their respective markers ('X' for the user and 'O' for the AI) on the grid.
- The first player to get three of their markers in a row (horizontally, vertically, or diagonally) wins the game.
- If all 9 squares are filled and no player has achieved a win, the game is a tie.

### Setup:
1. Clone the repository to your local machine:
   ```
   git clone https://github.com/TheLearningHead/Tic-Tac-Toe-Game.git
   ```
2. Navigate to the directory:
   ```
   cd Tic-Tac-Toe-Game
   ```
3. Run the game:
   ```
   python tic_tac_toe.py
   ```

### Gameplay Instructions:
- You will be prompted to choose whether you want to start the game as the user ('X') or let the AI start as 'O'.
- Enter your move position based on the numbered positions shown on the board.
- The AI player will make its move after you. The AI player uses a strategic approach to maximize its chances of winning or forcing a tie.
- The game continues until either a player wins or the board is full.

### Example Gameplay:
```
The position for each box is as follows : 
 | 1 | 2 | 3 | 
 | 4 | 5 | 6 | 
 | 7 | 8 | 9 | 
Do you wish to start the game?(Y/N) : Y
Enter your move position: 5
 |   |   |   | 
 |   | X |   | 
 |   |   |   | 

AI player is thinking...
 | O |   |   | 
 |   | X |   | 
 |   |   |   | 

Enter your move position: 7
 | O |   |   | 
 |   | X |   | 
 | X |   |   | 

AI player is thinking...
 | O |   | O | 
 |   | X |   | 
 | X |   |   | 

Enter your move position: 2
 | O | X | O | 
 |   | X |   | 
 | X |   |   | 

AI player is thinking...
 | O | X | O | 
 |   | X |   | 
 | X | O |   | 

Enter your move position: 6
 | O | X | O | 
 |   | X | X | 
 | X | O |   | 

AI player is thinking...
 | O | X | O | 
 | O | X | X | 
 | X | O |   | 

Enter your move position: 9
 | O | X | O | 
 | O | X | X | 
 | X | O | X | 

Its a tie!
```
