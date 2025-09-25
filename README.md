Tic-Tac-Toe Project

Overview
This project is a Tic-Tac-Toe game built with the course game engine using `Bit` and `BitHolder`. It supports two players (X and O), win detection, draw detection, and saving/loading the board state.

Design Process
- Set up a 3×3 grid of `BitHolder` objects with `square.png`.  
- Used `PieceForPlayer()` to create X or O pieces depending on the current player.  
- Implemented checks for winners (rows, columns, diagonals) and draws.  
- Added `stateString()` / `setStateString()` to serialize and restore the board.

The AI uses the Negamax algorithm with alpha-beta pruning to simulate all possible moves, score outcomes for both players, and pick the move that helps its chances of winning.
