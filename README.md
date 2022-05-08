# Mandatory-Tic-tac-toe
Create a board using a 2-dimensional array and initialize each element as empty.
  Represent empty using hyphen '-' symbol.

Check whether the board is filled or not.
  Iterate over the board and return false if the board contains an empty sign or else return true.

Check whether a player has won or not.
  Check all the possibilities.
  Check for all the rows, columns, and two diagonals.

Show the board as it will appeare multiple times to the users while they are playing.

Start the game.
  Select the first turn of the player randomly.
  Write an infinite loop that breaks when the game is over (either win or draw).
    Show the board to the user to select the spot for the next move.
    Ask the user to enter the row and column number.
    Update the spot with the respective player sign.
    Check whether the current player won the game or not.
    If the current player won the game, then print a winning message and break the infinite loop.
    Next, check whether the board is filled or not.
    If the board is filled, then print the draw message and break the infinite loop.
    
Finally, show the user the final view of the board.
