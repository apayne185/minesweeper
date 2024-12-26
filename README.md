# **Minesweeper Game**

This **Minesweeper** game is a simple implementation in Python using the Tkinter library for the graphical user interface. The game follows the classic rules of Minesweeper, where the player must reveal cells on a grid while avoiding hidden bombs. The code also includes features like an undo button and a CPU player for automated moves.

## Table of Contents

- [**Installation**](#installation)
- [**Usage**](#usage)
- [**Known Issues**](#known-issues)
- [**Future Improvements**](#future-improvements)
- [**Contributing**](#contributing)

## **Installation**

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/Minesweeper.git
   ---


**Note:** If you have specific details for sections like "Contributing" or "License," you can also make them bold for emphasis.

2. Install requirements

   ```bash
   pip install -r requirements.txt
   ---


## Usage
Once the game is launched, the player can interact with the grid by clicking on cells. The left-click will reveal a cell, and the right-click will flag or unflag a cell as containing a bomb.

### Key Features:
- Left-click: Reveals the cell. If a bomb is revealed, the game ends.
- Right-click: Flags or unflags a bomb.
- Undo: Allows the player to undo the last move.
- CPU Player: Click the "CPU Player" button to let the CPU make moves automatically.

#### Win Condition:
The game is won when all non-bomb cells are revealed without triggering any bombs.
#### Lose Condition:
The game is lost if a bomb is revealed.
   

## **Known Issues**

- The CPU player does not play right after the main player, the user has to click a button to give it a chance to make a move

## **Future Improvements**

- Better CPU capabilities: we make it able to choose cells strategically not just in order
- Difficulty Levels: Adding multiple difficulty levels by adjusting the size of the grid and the number of bombs.
- Enhanced GUI: A more polished user interface with features like timer, score, and more visual enhancements.

## **Contributing**

- Baptiste Etroy
- Aya-Yasmine Belloum
- Ronald Beltran
- Anna Payne
