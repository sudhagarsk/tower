# Tower of Hanoi Game

This project implements the Tower of Hanoi game using HTML, CSS, and JavaScript. It visually simulates the movement of disks from one peg to another according to the classic rules of the Tower of Hanoi puzzle.

## Features

- **Interactive Puzzle**: Users can input the number of disks and watch them move between pegs based on the Tower of Hanoi solution.
- **Dynamic Animation**: The disks move automatically from the source peg to the destination peg, following the recursive solution.
- **Custom Disk Input**: Players can specify how many disks they want to play with by entering a number.

## Technologies Used

- **HTML5**: Structure of the web page.
- **CSS**: Styling for the pegs and disks.
- **JavaScript**: Game logic and animation.

## How It Works

1. **User Input**: The user enters the number of disks.
2. **Game Initialization**: The disks are stacked on the first peg, sorted by size.
3. **Move Disks**: Clicking the "Make Move" button triggers the recursive Tower of Hanoi algorithm, and the disks are moved from the source peg (`A`) to the destination peg (`C`), using the auxiliary peg (`B`).
4. **Game Completion**: The game will continue to move the disks until all are successfully transferred to the destination peg.

## Installation and Usage

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/tower-of-hanoi-game.git
