# impossible-tic-tac-toe

## How it works:
  1. The middle box is marked as X to make this game impossible
  2. When the player places a mark, the computer checks if there are any rows without player's mark, **AND** includes computer's mark, this provides the computer the fastest step to winning
  3. The computer checks whether or not it is winning, if so, the computer will place a mark to win the game
  4. If the computer is not winning, and the player is winning, the computer will place a mark to prevent the player from winning
  5. A code will check for the winner every time after player places a mark. Either win, loss or tie, the game will end and neither of them can place a mark
  6. A message will pop up indicating win, loss or tie.
