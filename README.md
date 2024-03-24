# tic-tac-toe-game
This code provides the foundational structure for a Tic Tac Toe game with drag and drop functionality for placing X and O symbols on the grid
This is a simple Tic Tac Toe game created using HTML, CSS, and JavaScript. Here's how the game works:

Grid Setup:

The game grid consists of a 3x3 layout, represented by the .grid class in the CSS.
Each cell in the grid is represented by the .cell class.

Player Interaction:

Players can interact with the game by dragging and dropping X and O symbols onto the grid.
X symbols are represented by boxes with the .draggable.x class, and O symbols are represented by boxes with the .draggable.o class.

Drag and Drop Functionality:

When a player drags an X or O box (draggable elements) and drops it onto an empty cell in the grid, the corresponding symbol is placed in that cell.
The drop functionality is handled using JavaScript event listeners (dragstart, dragover, and drop events).

Game Logic:

The game logic ensures that a cell can only be filled with an X or O symbol if it's currently empty (i.e., not already containing an X or O).
Once a symbol is placed in a cell, the corresponding box becomes un-draggable to prevent further interaction with that cell.

Winning Condition:

The game does not include specific winning condition logic in the provided code. Typically, Tic Tac Toe games check for winning combinations after each move to determine the winner.

Resetting the Game:

The resetGame() function is provided but not fully implemented in the given code snippet. It's meant to reset the game by making all X and O boxes draggable again, allowing players to start a new game.


![image](https://github.com/asmita-2003/tic-tac-toe-game/assets/161740703/ad26e844-6204-4540-bd49-b13c552a116a)

![image](https://github.com/asmita-2003/tic-tac-toe-game/assets/161740703/381ee65a-a589-440e-9930-56b4ffbe9650)

